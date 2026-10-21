---
title: Expandify privacy policy
---

# Expandify privacy policy

Effective: 2026-10-21

Expandify is an Android app made by imthefacc. You save shortcuts, such as "addr", together with the full text each one stands for. When you tap the floating bubble, Expandify replaces the shortcut you just typed with its full text.

**In short:** Expandify cannot connect to the internet. It has no account, ads, analytics or crash reporting, and it sends nothing to the developer or to anyone else. What you type is not saved. Your shortcuts and settings stay on your phone. They leave it only through Android's backup and phone-to-phone transfer, or in a file you export yourself.

## What Expandify reads, and why

Expandify uses Android's Accessibility API (AccessibilityService). Before you turn it on, the app explains how it uses it and asks you to agree. Until you agree, and whenever the bubble is turned off, it is paused and reads nothing.

While the bubble is on, it can see the text field you are typing in (its text, cursor position and type, for example password or number), which app is in front, and whether the keyboard is open. It uses the app and keyboard state only to place the bubble and keep it out of apps you excluded. It reads the text of the field only:

- **when you tap the bubble**, to find the shortcut before the cursor and replace it with its full text. If no shortcut matches, the word before the cursor is shown briefly on the bubble so you can save it.
- **when you drag the bubble**, to offer the word before the cursor on the "Add" target.
- **right after an expansion**, to check the field again so a quick second tap repeats it in the right place.

Expandify never types anything unless you tap, and only into the field you are typing in. All of this happens in memory on your phone. The text is never saved, except a word you choose to save as a shortcut.

**Password fields are skipped.** Expandify does not read, expand in or show the bubble on fields that the app you are using marks as password fields, "visible password" ones included. It cannot recognize a password field that the app leaves unmarked.

To let you pick apps where the bubble stays hidden, Expandify can see which apps have a home-screen icon. Its other permissions only serve the bubble: display over other apps to draw it, a foreground service to keep it running, and an optional notification with a Stop button.

## What is stored, and where

Expandify keeps your shortcuts (and when you last changed each), your settings, including the package names of apps you excluded, and whether you agreed to the Accessibility explanation. They stay in its private storage on your phone, which other apps cannot read. Expandify adds no encryption of its own.

**Android backup.** If backup is on and your phone has a screen lock, Android may back up your shortcuts and settings to your Google account, end-to-end encrypted with your screen lock. Without a screen lock, Expandify is left out of the backup. On Android 12 and later, Android's transfer tool can also copy them directly to a new phone. Google handles these copies under its own terms, and the developer cannot see them. Records tied to this install, such as your Accessibility agreement, are never copied, so a new phone asks again. You can turn backup off in Android's settings.

**Exported files.** In Settings › Export & import you can save your shortcuts, bubble look and settings to a file, wherever you choose. The file is plain, unencrypted JSON: anyone who opens it can read your shortcuts, so keep it safe. If you save it to a cloud folder, that service's terms apply.

**Deleting.** Shortcuts and settings stay until you change or delete them. To delete everything, go to Android Settings › Apps › Expandify › Storage › Clear storage, or uninstall the app. Backups are managed in your Google account. Exported files stay wherever you saved them.

## What reaches the developer, and your rights

The app sends the developer nothing. If you let your phone share usage and diagnostics data with Google, Google Play may show the developer crash and performance reports for Expandify, collected by Google under its own privacy policy.

If you email the developer, your address and message are used only to answer you (legal basis: legitimate interest). They stay in the developer's Gmail account, run by Google, which may store them outside the EU and UK, and are deleted on request or once no longer needed.

If you live in the EU or UK, you can ask to access, correct or delete personal data about you, or object to its use, and you can complain to your local data protection authority.

## Changes

If this policy changes, the new version will be posted here with a new effective date. If a change affects how the Accessibility API is used, the app will ask for your agreement again.

## Contact

Questions about this policy or about Expandify: [imthefacc@gmail.com](mailto:imthefacc@gmail.com)
