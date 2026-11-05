Try To Do List: Education — Backup & Onboarding update

Based on the previously tested timer-fix build. This update adds:
- First-use Moss introduction explaining assignments, next steps, progress, timer, and local data storage.
- Backup status showing the date of the last exported/restored backup.
- A backup reminder after 14 days without a recorded backup, with Back up now and Remind me next week options.
- Import records the backup timestamp from the imported file.

Upload the CONTENTS of this ZIP to the root of your existing GitHub Pages repository, replacing the existing files. Do not create a nested folder. The service-worker cache version is bumped to v4.

Important: student data remains stored locally in each browser/device. Exported backups are manual files; this update does not create cloud sync or automatic off-device backups. A reminder appears when the app is opened after the reminder interval.

Validation: JavaScript syntax checked; ZIP structure checked. Not yet live-device tested. Keep your current deployment/backup until the new version is verified.
