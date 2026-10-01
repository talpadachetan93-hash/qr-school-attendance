# QR School Attendance — Build Ready

This archive includes the Android Gradle project files needed for a cloud APK build.

Demo accounts:
- teacher / 1234
- admin / 1234

Mobile-only cloud build:
1. Create a GitHub repository from your phone.
2. Upload the contents of this ZIP while preserving folders.
3. Open Codemagic and connect the GitHub repository.
4. Select Flutter and use the Android APK workflow.
5. Start the build and download the generated APK artifact.

Note: this is a prototype. Attendance is stored locally on the device. Firebase/cloud sync,
secure authentication, production signing, backups and privacy controls are still required
before real school deployment.
