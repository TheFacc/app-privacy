---
title: Notilate privacy policy
---

# Notilate privacy policy

Effective: 2026-10-25

Notilate is an Android app made by facc. It holds back notifications from apps you choose and shows them to you later, in summaries at the times you set.

**In short:** Notilate cannot connect to the internet. It has no account, ads, analytics, crash reporting or third-party tracking code, and it sends nothing to the developer or to anyone else. Your notifications are stored only on your phone. Data leaves it only in a backup file you export yourself, and that file never contains notification text.

## What Notilate reads, and why

Notilate uses Android's notification access. Before you grant it, the app explains what it reads and why. With it, Android shows Notilate the notifications on your phone. Notilate saves only those from apps you picked:

- the app, title, text and subtext
- the labels of action buttons, such as "Reply"
- its ID, arrival time, priority and category, and whether it is ongoing

This is used to hold the notification, list it in your summary, open it or run an action when you tap it, and count it in your statistics. All of it happens on your phone.

To fill the app picker, Notilate can see which apps have a home-screen icon, plus the apps that post notifications.

Hidden debug tools, unlocked from Settings, can show live notifications from any app and a diagnostics log. Both stay in memory. You can copy the log; it holds app and notification IDs, not notification text.

## What is stored, and where

Everything is in Notilate's private storage on your phone, which other apps cannot read. Notilate adds no encryption of its own. Android backup and phone-to-phone transfer are turned off for it.

- **Held notifications** stay until you open or dismiss them. Turning an app off in Notilate deletes its held copies.
- **Opened or dismissed notifications** are deleted, text included, about 42 days after they arrived, when Notilate next starts or you next open it. Some are deleted sooner. Until then only their app and arrival time are used, for statistics.
- **Settings and statistics** (summary times, theme, your app list and filters, daily counts per app, and notification times imported from a backup) stay until you change them or delete the app's data.

**Exported files.** In Settings › Backup & restore you can save a file and choose what goes in it: settings, your apps and their filters, and statistics (daily counts, plus the app and arrival time of notifications from the last 35 days). It never contains notification titles, text or actions. The file is plain, unencrypted JSON: anyone who opens it can read it. It is saved only where you choose; if that is a cloud folder, that service's terms apply. Importing reads only the file you pick.

**Deleting.** To delete everything, go to Android Settings › Apps › Notilate › Storage › Clear storage (names vary by phone), or uninstall the app. Exported files stay wherever you saved them.

## Permissions

- **Notification access**: to read, hold and act on notifications from the apps you pick. You can turn it off in Android's settings at any time.
- **Notifications**: to show your summaries and the optional "Quiet status" notification.
- **Run at startup**: to schedule summaries again after a restart.
- **Alarms & reminders** (optional): only if you turn on "Exact timing".
- **App visibility**: to list your apps in the picker, and to find some phone makers' battery settings for "Keep Notilate running".
- Wake lock, foreground service and network state come with Android's WorkManager library, which schedules summaries. Notilate does not use the network.

## What reaches the developer, and your rights

The app sends the developer nothing. If you let your phone share usage and diagnostics data with Google, Google Play may show the developer crash and performance reports for Notilate, collected by Google under its own privacy policy.

If you email the developer, your address and message are used only to answer you (legal basis: legitimate interest). They stay in the developer's Gmail account, run by Google, which may store them outside the EU and UK, and are deleted on request or once no longer needed.

If you live in the EU or UK, you can ask to access, correct or delete personal data about you, or object to its use, and you can complain to your local data protection authority.

Notilate is not aimed at children.

## Changes

If this policy changes, the new version will be posted here with a new effective date.

## Contact

Questions about this policy or about Notilate: [imthefacc@gmail.com](mailto:imthefacc@gmail.com)
