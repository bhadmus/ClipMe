# Privacy Policy

Last updated: June 4, 2026

ClipMe is a clipboard extension app for macOS. Clipboard data can contain
sensitive information, so ClipMe will never transmit clipboard contents or
snippet contents to external services without the user's consent.

This policy clarifies whether ClipMe collects personally identifying information,
whether ClipMe collects copied contents, and what network communication ClipMe
performs.

## Summary

- ClipMe does not ask users to provide names, email addresses, account
  information, or other directly identifying personal information.
- ClipMe does not transmit clipboard text, clipboard images, snippets, or other
  copied contents to ClipMe servers, Firebase, or any other third-party service.
- ClipMe's intended network communication is limited to update checks via
  `your-domain.example.com` and diagnostics/usage measurement via Firebase.
- Firebase Analytics / Firebase Crashlytics are enabled by default and can be
  disabled in ClipMe's Preferences.

## Data Stored Locally

ClipMe stores clipboard history, snippets, preferences, and related app data
locally on your Mac.

Clipboard contents and snippets are not sent to external services by ClipMe.
However, clipboard managers can store sensitive information locally. We
recommend excluding password managers and other sensitive apps from ClipMe's
history recording when possible.

ClipMe does not currently claim that locally stored clipboard history is
encrypted. If your Mac contains sensitive data, we recommend enabling FileVault
and using macOS security features appropriately.

## Network Communication

ClipMe's intended network communication is limited to the following services:

- `your-domain.example.com`: used by Sparkle to check for app updates.
- Firebase: used for analytics and crash reporting.

ClipMe does not intentionally use other network services.

## Firebase Analytics

ClipMe uses Firebase Analytics to understand basic app usage, such as the number
of users, app launches, app version, macOS version, language, and general feature
usage.

Firebase Analytics is enabled by default. You can disable analytics in ClipMe's
Preferences.

ClipMe does not use Firebase Analytics to collect user-created or copied content,
including clipboard contents, snippet contents, file contents, copied secrets,
or personal information entered by the user.

## Firebase Crashlytics

ClipMe uses Firebase Crashlytics to collect crash reports and error diagnostics.
Crash reports help us understand and fix stability problems.

Crash reports may include information such as:

- App version
- macOS version
- Device model or architecture
- Stack traces
- Crash timestamps
- Firebase installation identifiers
- Diagnostic logs added by ClipMe

ClipMe does not intentionally include clipboard contents or snippet contents in
Crashlytics logs, custom keys, or error reports.

You can disable crash reporting in ClipMe's Preferences.

## Update Checks

ClipMe uses Sparkle to check for updates from `your-domain.example.com`. Update checks may
send standard request information such as the app version, macOS version, and IP
address to the update server.

## Third-Party Processing

Firebase is provided by Google. Data sent to Firebase is processed according to
Google's Firebase terms and privacy documentation.

Sparkle is used for update checks. The update feed is hosted by ClipMe on
`your-domain.example.com`.

## User Controls

You can enable or disable analytics and crash reporting from ClipMe's Preferences.

When disabled, ClipMe will stop intentionally sending analytics and crash
diagnostic data from future app usage. Some previously sent data may remain in
Firebase according to Firebase's retention policies.

## Changes

This privacy policy may be updated when ClipMe's behavior or third-party services
change.

## Contact

For privacy or security questions, please open an issue on GitHub.

GitHub: https://github.com/your-org/ClipMe
