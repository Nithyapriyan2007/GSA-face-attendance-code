# GSA Face Attendance: files for the GitHub repo

Unzip at the ROOT of the repo (D:\gsa) and allow overwrite. Paths match the repo exactly.

- `apps/face_attendance/`  the separate Android app (Flutter + Kotlin, GdFace SDK), README, INSTALL, DEPLOYMENT, CONFIGURATION, KNOWN_LIMITATIONS, TESTING_REPORT
- `.github/workflows/build-face-apk.yml`  builds the APK on GitHub (needs secret ANDROID_KEYSTORE_B64 for a stable signing key)
- `apps/api/migrations/0007_face_attendance.sql`, `apps/api/src/routes/face.ts`  backend routes and tables
- `apps/api/tests/`  API tests (face_api_test.py, face_api_extra_test.py, reset_face_state.sql)
- `apps/web/src/pages/FaceAttendance.tsx`  admin page

Not included on purpose: face models (164 MB, install on the phone), APKs, signing keystore, secrets.
Snapshot of git commit c878696 on main. The rest of the repo is unchanged.

Push: cd D:\gsa; git add -A; git commit -m "Face attendance"; git push origin main
