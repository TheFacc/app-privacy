---
title: Expandify privacy policy
---

# Expandify privacy policy

Effective: 2026-10-21

Expandify is an Android app made by imthefacc. You save shortcuts, such as "addr", together with the full text each one stands for. When you tap the floating bubble, Expandify replaces the shortcut you just typed with its full text. This page explains what the app reads, what it keeps, and where.

**In short:** Expandify has no internet access. It has no account, ads, analytics or crash reporting. What you type is not saved, and nothing is sent to the developer or to anyone else. Your shortcuts and settings stay on your phone. They leave it only through Android's own backup, if you have it turned on, or in a backup file that you export yourself.

## What Expandify reads, and why

Expandify uses Android's Accessibility API (AccessibilityService). Before you turn it on, the app explains how it uses it and asks you to agree. Until you agree, and whenever the bubble is turned off, the service is paused and reads nothing.

While the bubble is on, Expandify can see:

- **the text field you are typing in**: its text, the cursor position, and its type (for example password or number)
- **which app is in front, and whether the keyboard is open**, so the bubble appears in the right place and stays out of apps you excluded

It reads the text of the field in these cases:

- **When you tap the bubble.** It looks at the text before the cursor, finds your shortcut and replaces it with its full text. If you tap again shortly afterwards, it adds the same text again. Expandify never types anything unless you tap.
- **When no shortcut matches.** The word before the cursor is shown briefly on the bubble. If you then drag the bubble onto "Add", that word is filled in so you can save it as a new shortcut.
- **When you start dragging the bubble.** It reads the word before the cursor once, to offer it on the "Add" target.
- **Right after an expansion.** When the field changes, Expandify checks whether the change came from you or from its own insert, so that another tap adds the text again only where it should.

All of this happens on your phone, in memory. Expandify does not save the text of your fields. The only exception is a word that you save yourself as a new shortcut.

**Password fields are never read.** Their text is skipped in every case above, Expandify never expands in them, and the bubble does not show there. Fields of the "visible password" type count as password fields too.

## Where it is kept

Everything is stored in Expandify's private storage on your phone:

- **your shortcuts**: each shortcut, its full text and when you last changed it
- **your settings**: theme, bubble look and motion, where the bubble rests on screen, when the bubble is shown, the apps you excluded (stored as their package names), the app icon you chose, and whether setup is done
- **two per-install records**: whether you agreed to the Accessibility explanation, and whether the app has already asked for notification permission

## Android backup and transfer to a new phone

Expandify allows Android's backup, but only when it is end-to-end encrypted with your phone's screen lock (PIN, pattern or password). If backup is turned on and your phone has a screen lock, Android copies your shortcuts and settings, encrypted, to your Google account. Without a screen lock, Expandify is left out of the cloud backup. On Android 12 and later, it also copies the same data when you move to a new phone with Android's transfer tool. Android and Google handle these copies under their own terms; Expandify does not send them and the developer cannot see them. The two per-install records above are left out of both, so a new phone always asks for your agreement again. You can turn backup off in Android's settings.

## What is not collected or shared

Expandify does not have the internet permission, so it cannot send anything anywhere. The developer receives no data from the app: no typed text, no shortcuts, no usage data, no device identifiers, no crash reports. The app contains no advertising, analytics or tracking code, and it shares nothing with third parties. Your expansion text goes into another app's field only when you tap the bubble in that app.

## Backup files you export

In Settings › Export & import you can save your data to a file and import it later, for example on a new phone. You choose what goes in it:

- **shortcuts**: each shortcut and its full text
- **personalization**: the bubble's look and motion
- **settings**: theme, shortcut and repeat options, when the bubble is shown, and the package names of the apps you excluded

The file is a plain, unencrypted JSON file. Anyone who can open it can read your shortcuts, so keep it somewhere safe. Expandify saves it only where you choose in Android's file picker. If you save it to a cloud folder, that service's terms and privacy policy apply to it. Importing reads only the file you pick.

## Permissions

- **Accessibility** (Accessibility service): to read the focused text field as described above and replace your shortcut with its full text. You turn it on in Android settings and can turn it off at any time; Expandify cannot expand anything without it.
- **Display over other apps** (`SYSTEM_ALERT_WINDOW`): to show the floating bubble, its drag targets and the quick "Add shortcut" window above the app you are typing in.
- **Foreground service** (`FOREGROUND_SERVICE`, `FOREGROUND_SERVICE_SPECIAL_USE`): to keep the bubble running while you have it turned on.
- **Notifications** (`POST_NOTIFICATIONS`), optional, Android 13 and later: to show a quiet notification with a Stop button while the bubble runs. The bubble works without it.
- **App visibility**: Expandify can see apps that have a home-screen icon, to list them when you choose apps where the bubble should stay hidden.
- **Battery**: Expandify does not ask for a battery exemption itself. The optional setup step only opens Android's battery settings, where you can choose to let it run unrestricted.

## How long data is kept, and how to delete it

- Text read from your fields is kept in memory only while it is needed. It is never written to storage.
- Shortcuts and settings are kept until you change or delete them. You can delete shortcuts one by one in the app.
- To delete everything Expandify has stored, go to Android Settings › Apps › Expandify › Storage › Clear storage, or uninstall the app.
- Android backups live in your Google account and are managed there.
- Exported files are yours. Delete them wherever you saved them.

## Security

Your data stays in the app's private storage, which Android keeps other apps from reading. The app's services can't be started by other apps. Expandify adds no encryption of its own; cloud backups are encrypted by Android with your screen lock, as described above. An exported file is not encrypted.

## Your rights

The developer holds no data about you, because nothing reaches them from the app. You can see, change, export and delete everything Expandify stores, directly in the app or through Android's settings. If you write to the developer, your email address and message are used only to reply to you. If you live in the EU or UK, you have the right to access, correct or delete personal data about you, and to complain to your local data protection authority.

## Children

Expandify is not aimed at children. It collects no personal data from anyone, children included.

## Changes to this policy

If this policy changes, the new version will be posted on this page with a new effective date. If a change affects how the Accessibility API is used, the app will ask for your agreement again.

## Contact

Questions about this policy or about Expandify: [imthefacc@gmail.com](mailto:imthefacc@gmail.com)
