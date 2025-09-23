# AttendGo

A simple, fast, and cross‑platform attendance management app built with Flutter. AttendGo helps teachers and organizers manage classes, add students, take attendance, export reports, and set daily reminders — all stored locally on your device.

- Cross‑platform: Android, iOS, Web, Desktop
- Local storage with backups/exports (PDF/CSV)
- Daily reminders and shareable attendance summaries

---

## Download
Get the latest app build here:

- Android APK: [Download the latest release](DOWNLOAD_LINK_PLACEHOLDER)

---

## Project Overview
AttendGo focuses on privacy and speed:
- Create classes, add students, and keep an attendance register
- Recover deleted entries via a Bin, or permanently remove them
- Export attendance as PDF, share summaries via WhatsApp
- Configure daily reminders and customize the share message

---

## Key Features
- Class and student management with pinning for quick access
- Attendance register with soft‑delete and recovery via Bin
- History log for an audit trail of attendance actions
- CSV import for quickly onboarding students (Name, Roll)
- PDF export to the device Downloads folder
- One‑tap sharing of formatted summaries (WhatsApp or web)
- Daily local notifications with configurable time
- Light/Dark/System themes

---

## Privacy & Data
- Your data is stored locally on your device using secure on‑device storage.
- No external servers or cloud sync are used by default.
- Permissions used:
  - Notifications (for daily reminders)
  - Storage/Files (to save PDFs to Downloads)
  - External app links (to open WhatsApp or browser for sharing)

---

## Platforms & Requirements
- Android: Android 7.0 (API 24) or higher recommended
- iOS: iOS 13 or higher (distribution via TestFlight or direct IPA not provided here)
- Web/Desktop: Core features may be limited compared to mobile due to plugin support

---

## How It Works
1. Create a class and add students (manually or via CSV import)
2. Mark attendance by selecting present students
3. Save the register and view history or restore from Bin if needed
4. Export a PDF report to Downloads or share a summary via WhatsApp
5. Enable daily reminders and set your preferred time

---

## Release Notes
See the latest changes and downloads on the Releases page of this repository.

- Changelog: Will be maintained alongside releases
- Known limitations: Some desktop/web features may be reduced vs. mobile

---

## FAQ
- Is my data synced to the cloud?
  - No. All data stays on your device unless you manually export/share it.
- Where are PDFs saved?
  - In your device's Downloads folder (path may vary by platform).
- Do I need WhatsApp installed?
  - Not strictly. We attempt to open WhatsApp if available, otherwise we fall back to a browser link (`wa.me`).
- What permissions are required?
  - Notifications for reminders; opening external apps for sharing.

---

## Source Code Availability
This public repository is distribution‑only. The source code is private and not available here.

- If you're interested in reviewing or contributing to the code, please request access to the private repository.
- Security researchers may also request read‑only access for audit purposes.

---

## Contributing
We welcome feedback, bug reports, and feature ideas.

- Open an issue in this public repository to report bugs or propose features
- For code contributions, please request access to the private repository and share a brief summary of what you'd like to work on
- Once approved, we will invite you to the private repo and provide contribution guidelines

You can also contact us by opening a discussion or issue with the tag `access-request`.

---

## Support & Feedback
- Issues: Use this repository's Issues tab
- Suggestions: Open a feature request issue


