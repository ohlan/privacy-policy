# Penny Trail Privacy Policy

Effective date: May 23, 2026

PennyTrail is a personal expense tracking app. This policy explains what data the app accesses, how it is used, when it may leave your device, and how you can control it.

## Summary

- PennyTrail stores your expense data locally on your device.
- SMS-based transaction tracking is optional and requires your explicit permission.
- SMS parsing happens on your device. SMS-derived app data may be included in encrypted Google Drive backups if you enable Drive backup.
- Google Drive backup is optional and uses your own Google account.
- PennyTrail does not sell your personal data and does not use your SMS or financial data for advertising.
- PennyTrail is not a bank, broker, tax advisor, or financial advisor. Insights and classifications are informational only.

## Data We Access Or Store

Depending on which features you use, PennyTrail may access or store the following data:

### Expense And Financial Data

This includes transactions, amounts, dates, currencies, merchant or vendor names, categories, accounts or wallet labels, budgets, recurring expense rules, notes, tags, and related preferences.

This data is used to show your expense history, budgets, reminders, and spending insights.

### SMS Data

If you enable SMS auto-tracking, PennyTrail requests access to bank and transaction SMS messages through Android SMS permissions. The app may process and store SMS sender, message body snippets, received time, parsing status, matched rule information, and transaction drafts.

This data is used only to detect financial transactions, queue drafts in Inbox, improve local categorization for your account, avoid duplicate imports, and support audit/debug review of parsed transactions inside the app.

SMS access is optional. If you do not enable it, you can still use PennyTrail manually.

### Receipt Photos And Attachments

If you attach receipt photos, PennyTrail stores those images in app-private storage on your device. Receipt images may be included in encrypted Drive backups if Drive backup is enabled.

### Google Account And Drive Backup Data

If you connect a Google account for backup, PennyTrail stores the selected Google account email locally and uses Google Drive AppData storage to upload encrypted backup snapshots. Backup snapshots may include your local database and receipt attachments, including SMS-derived app data.

Backups are stored in your Google Drive AppData folder. This folder is managed by Google and is generally not visible as a normal Drive file.

### Diagnostics

PennyTrail may use Firebase Crashlytics to collect crash reports and diagnostic information such as crash stack traces, app version, device model, operating system version, and an anonymous app identifier. Crash reports are used to fix bugs and improve reliability.

Crash diagnostics should not include raw SMS bodies or full financial details. If diagnostic logs are added in the future, they should be reviewed to avoid sensitive data.

### Feedback

If you send feedback by email, your email app and email provider will process the message you send. Do not include sensitive financial information or SMS content unless you are comfortable sharing it by email.

## Permissions We Request

PennyTrail may request these Android permissions:

- SMS permissions: to read and receive bank transaction SMS messages when you enable SMS auto-tracking.
- Notification permission: to show optional reminders and summaries.
- Camera permission: to capture receipt photos when you choose to attach one.
- Internet access: for Google Drive backup, Google sign-in, Firebase Crashlytics, and remote rule or service updates if enabled.
- Exact alarm access: to support user-configured reminders at the selected time.

Permission use is limited to the app features described in this policy.

## How We Use Data

PennyTrail uses data to:

- create, edit, restore, and delete expense records;
- parse SMS messages into transaction drafts;
- suggest categories and vendors;
- detect transfers, investments, recurring payments, and spending patterns;
- show budgets and insights;
- send reminders that you enable;
- create optional encrypted backups in your Google Drive AppData folder;
- diagnose crashes and improve app reliability.

PennyTrail does not use your SMS or financial data for advertising, profiling for ads, or sale to third parties.

## When Data Leaves Your Device

Most app features work locally. Data may leave your device in these cases:

- If you enable Google Drive backup, encrypted backup snapshots are uploaded to your Google Drive AppData folder using your Google account.
- If the app reports a crash through Firebase Crashlytics, diagnostic crash data is sent to Firebase/Google.
- If you send feedback by email, the information you include is sent through your email provider.
- If remote rule updates are enabled, the app may contact a remote endpoint to fetch parsing rules. The app should not send your SMS body or transaction history for rule updates.

## Backup And Sync

Drive backup is optional. If enabled, PennyTrail creates encrypted snapshots before upload. The encryption key is managed on your device using Android Keystore and Google Tink.

PennyTrail currently keeps a limited number of recent backup snapshots. Older snapshots may be deleted by the app when backup cleanup runs.

Disconnecting your Google account or wiping local data stops local use of that account in PennyTrail, but it may not delete backup snapshots that were already uploaded to Google Drive AppData. To fully remove cloud backups, use any delete-backup feature provided in the app when available, or manage app data through your Google account settings.

## Data Retention And Deletion

Local transactions, SMS-derived drafts, settings, accounts, budgets, categories, recurring rules, and attachments remain on your device until you delete them, wipe local data, uninstall the app, or the app removes them as part of a cleanup feature.

Deleted transactions may remain in Trash until you restore them, empty Trash, or an automatic retention cleanup removes them.

The Settings screen provides a local wipe option. Local wipe is intended to delete local app data on the device. It does not delete Google Drive backups that were already uploaded.

If you disable SMS auto-tracking, PennyTrail stops future SMS ingestion. Existing local SMS-derived records may remain until you delete or wipe local data.

## Security

PennyTrail relies on Android app-private storage and the Android security model to protect local data from other apps. Optional Drive backup snapshots are encrypted before upload.

No app or system can guarantee absolute security. Keep your device protected with a screen lock and only install apps from trusted sources.

## Children

PennyTrail is intended for personal finance use by adults. It is not directed to children. If you believe a child has provided personal data through the app, contact us so we can help remove it where possible.

## Your Rights And Choices

Depending on your jurisdiction (such as under the GDPR, CCPA, or DPDP Act), you may have certain rights regarding your personal data. Because PennyTrail is designed as a local-first application, you have direct control over your data. You can:

- access your data at any time within the app;
- export your local transaction data to a CSV file;
- delete specific records, or wipe all local app data permanently using the "Wipe all data" option in Settings;
- uninstall the app to remove local app data from the device, subject to Android and backup behavior;
- use PennyTrail without SMS auto-tracking;
- deny or revoke SMS, notification, or camera permissions in Android settings;
- disable SMS auto-tracking in PennyTrail settings;
- disconnect Google Drive backup.

## Third-Party Services

PennyTrail may use:

- Google Play Services and Credential Manager for Google sign-in;
- Google Drive API for optional user-controlled backup;
- Firebase Crashlytics for crash diagnostics;
- Android platform services for SMS, notifications, camera, and exact alarms.

These services are governed by their own privacy and security practices.

## Changes To This Policy

We may update this policy as PennyTrail changes. If changes are material, we will update the effective date and, where appropriate, notify users in the app or release notes.

## Contact

Developer: TranscenD

Email: ohlanpushpender@gmail.com
