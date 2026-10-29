# Privacy Policy for ApkShelf

Last updated: 29 October 2026

This policy explains what ApkShelf ("the app") does with your data. The app is developed by an individual developer based in Delhi, India. Contact: thedarkestknight3426@gmail.com

## What the app reads on your device

ApkShelf reads the list of apps installed on the current user that have a launcher icon. For each app, it reads:

- app label (name)
- package name
- version name and version code
- whether the app is a system app
- the file paths of the APK files Android has already stored for that app
- the icon Android shows for that app

ApkShelf does not read your messages, contacts, call logs, location, photos, media, microphone, or camera. It does not read any file other than the APK files above. The installed-app list is never sent off your device. Listing apps and saving APKs happen entirely on your device and do not call a server.

## Crash reports

ApkShelf uses Google Firebase Crashlytics to receive crash reports so the developer can fix bugs. This is the only service in the app that sends data over the internet. When the app crashes, Crashlytics collects:

- a crash log (stack trace and the state of the app at the time)
- diagnostic information such as device model, operating system version, and app version
- a Firebase installation identifier that is generated for the app on your device

This information is sent to Google and is used only to find and fix crashes. It does not include the list of apps installed on your device, the APK files you save, or the folder you chose. Crash reports are sent only from release builds of the app.

ApkShelf does not use Firebase Analytics, advertising, or any other tracking service. Analytics collection and the advertising ID are switched off in the app, so Google Play services cannot start usage tracking in the background.

Google processes this data under its own terms. See https://firebase.google.com/support/privacy and https://policies.google.com/privacy.

## What the app writes

When you choose to save an app, ApkShelf copies that app's APK file to a folder you select using the Android system folder picker. The copy stays on your device unless you move or share it yourself. The folder you picked is remembered only on your device, in the app's private storage. Clearing the app's data removes this.

## Permissions

ApkShelf requests no runtime permissions. It declares the internet permission only so that crash reports can be sent. It uses a `<queries>` declaration to see apps that have a launcher icon.

Apps inside a Work profile, Private Space, Secure Folder, Dual Messenger, or any other Android user profile are not shown. Some phones (for example Xiaomi) require a separate system permission before any app list is shown; if it is not granted, the list may be empty.

## Your choices and deletion

Crash reports are not linked to your name or email. To ask for crash data tied to your device to be deleted, email thedarkestknight3426@gmail.com and include the app version and device model. Uninstalling the app removes the installation identifier on your device.

## Children

ApkShelf is not directed at children.

## Contact

Email: thedarkestknight3426@gmail.com

## Changes

If this policy changes, the "Last updated" date above will change. The current version is always at this URL.
