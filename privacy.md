---
title: GPS Speed Privacy Policy
permalink: /privacy/
---

# GPS Speed Privacy Policy

**Effective date:** 2 October 2026

This policy covers the GPS Speed app for iPhone, including its Live Activity.

## In short

- **GPS Speed collects no data.** The developer receives nothing from the app: no location, no trips, no settings,
  no usage statistics and no identifiers.
- The app uses your location **only on your iPhone** to show your speed and to measure the trips you record.
- Your recordings are **stored only on this iPhone and in your own backups, and never sent anywhere.**
- The app has **no account, no ads, no analytics, no tracking and no network connection**.
- You can delete one recording at any time, all of them whenever no recording is in progress, or the app with all
  its data.

## What the developer collects

Nothing through the app. GPS Speed has no code that connects to the internet, and it contains no analytics,
advertising, tracking or crash-reporting software from the developer or anyone else. There is no account and no
sign-in. The developer cannot see your location, your trips or your settings. If you write to the developer by
e-mail, see "Your choices and rights".

## What the app uses on your iPhone

### Your location

GPS Speed uses your location to work out your current speed, the distance of a trip you record and how good the GPS
signal is, and, while you record, to keep a GPS track of the trip (see "What is stored"). It uses your location only:

- while the app is open and the Speed tab is on screen, to show your speed; and
- while you are recording a trip that you started (also while it is paused), on every tab of the app and in the
  background, for example while your iPhone is locked in your pocket.

When you are not recording, it stops using your location as soon as you switch to History or Settings or leave the
app. It does not use your location during the first-launch screens.

The live speed you see while you are not recording is not stored.

### What is stored

On your iPhone, the app keeps only the following:

- **Your recordings (trips):** when each trip started and ended, when you paused and resumed it, and in which time
  zone; the activity you chose (for example Cycling); the name you gave it; its statistics (distance, duration,
  moving time, maximum speed and a summary of the GPS signal quality); whether you ended it or it was saved after an
  interruption; a few technical details (an internal identifier, when it was last saved and the app version that
  recorded it); and a filtered GPS track of the trip, about one point per second. Each point holds the time it was
  measured, a position, altitude, speed and direction, the accuracy of the position, altitude and speed, and a few
  markers about the signal (for example a weak signal, or a location that iOS reported as simulated or as coming
  from an accessory). This version of the app does not show or export the track; it is kept with the trip.
- **An unfinished recording:** while a trip is being recorded, the app also keeps what it needs to continue the trip
  after an interruption: running totals, the last position it accepted and a few recent positions it is still
  checking (these are not part of the saved track), with their times, accuracies and speeds. This is deleted when
  the trip is finished.
- **A log of saves:** the app's database also records each time a recording was saved or changed (about every 20
  seconds while recording, and for example when you pause, end or rename it) and which of its details changed, but
  not their values: no positions, speeds, distances or names. The app clears this log each time it starts and
  whenever you delete a recording.
- **Your settings:** your speed units, each activity's settings (unit and Keep Screen On), the activity you used last,
  whether you have finished the first-launch screens (made your choice about location access), and a small note
  about a running recording (an internal trip identifier, its activity and three yes-or-no flags) so that the app
  can continue it after an interruption.
- **Diagnostic messages:** like most apps, GPS Speed writes short technical messages to the iOS system log on your
  iPhone, for example that a recording started (with its activity), was saved or could not be saved. They never
  contain your location, speeds, distances or recording names; iOS deletes them automatically after a while, and the
  developer does not receive them.

## Where it is stored

- **Only on this iPhone,** in GPS Speed's private storage, which other apps cannot read (the diagnostic messages are
  in the iOS system log).
- **Protected by iOS Data Protection,** which, when your iPhone has a passcode, encrypts it with a key tied to that
  passcode. The app can read and write its recordings once you have unlocked your iPhone at least once since it was
  turned on, so that a recording can keep saving while the iPhone is locked in your pocket.
- **In your own backups:** if you back up your iPhone (iCloud Backup, or a backup to a computer), your recordings and
  settings are part of that backup, like the data of most apps. Your backup settings and Apple's terms apply to those
  backups; the developer has no access to them.
- There is no separate cloud storage and no syncing between devices.

## What is sent where

Nothing is sent to the developer or to anyone else, and the app makes no network requests. Only these leave the app:

- **The Live Activity,** from Start to End: the app gives iOS your current speed, distance, recording time, activity
  and GPS or paused state (never your location), and iOS shows it on this iPhone and on your own devices, such as a
  paired Apple Watch or CarPlay (see "The Live Activity can be seen without unlocking").
- **Your backups,** if you make them (see "Where it is stored").
- **Privacy Policy** (Settings › About), only when you tap it, opens this page in your web browser. Your browser then
  loads it like any other website, and that website's own practices apply to the visit.
- **Open Settings** and **Open iOS Settings**, only when you tap them, open GPS Speed's page in the Settings app.

**Apple:** Apple handles the App Store download of the app. If you choose to share analytics with app developers
(Settings › Privacy & Security › Analytics & Improvements), Apple may give the developer crash reports and usage
statistics. Apple collects these under its own privacy policy. The app adds no data of its own to them.

## Permissions

- **Location, "While Using the App" only.** The app asks for this permission only when you tap Continue: on the
  first-launch screens, or later, if iOS no longer has your answer (for example after an "Allow Once" permission has
  expired), in the "Location Access Needed" banner on the Speed tab or on the Location Access page that opens when
  you tap Start or Resume. It never asks for "Always" access.
- **Background location only while you record.** From the moment you tap Start until you tap End (including while the
  recording is paused), the app can keep measuring while you use another app or your iPhone is locked. During that
  time iOS shows its blue location indicator at the top of the screen. When you are not recording, the app never uses
  your location in the background.
- **Precise Location** is needed to measure speed. If you allow only approximate location, the app may ask iOS for
  temporary precise location, at most once each time you open the app. If you decline, the app shows no speed and
  cannot record until precise location is allowed.
- You can change or remove location access at any time in Settings › Privacy & Security › Location Services › GPS
  Speed.
- **Live Activities:** the first time you record, iOS may ask whether to allow Live Activities from GPS Speed. You can
  turn them off in Settings › Apps › GPS Speed › Live Activities.
- The app asks for no other permission: no contacts, photos, camera, microphone, health data, motion data,
  notifications or tracking.

## The Live Activity can be seen without unlocking

While you record a trip, GPS Speed shows it in a Live Activity: on the Lock Screen, in the Dynamic Island, in StandBy,
in the Smart Stack of a paired Apple Watch and in CarPlay. If a recording stops unexpectedly (for example because GPS
Speed was closed and iOS did not reopen it), the Live Activity can stay with the trip's last speed, distance and
activity, its time still counting (unless the recording was paused); within about 90 seconds (up to 10 minutes if you
were standing still) it shows dashes instead of the speed and "No recent update". When you open GPS Speed again, it
either removes the Live Activity or marks it "Interrupted", with the time stopped, until you decide what to do with
the recording. Until then, iOS ends the Live Activity 8 hours after it started but can keep it on the Lock Screen for
up to 4 more hours, unless you remove it. Like every Live Activity, it **can be seen without unlocking your iPhone**,
so anyone who can see the screen can read your **speed, distance, recording time, activity, the GPS state and whether
the recording is paused or interrupted**. It **never shows your location**: no map, no place and no coordinates.

iOS shows the Live Activity on your own devices; the app does not send it to the developer or anyone else and uses no
push notifications. To stop showing it, turn off Settings › Apps › GPS Speed › Live Activities, or remove it from the
Lock Screen: GPS Speed then does not show it again for that recording. There are two exceptions: if you removed it
while GPS Speed was not running (for example after iOS closed the app), or removed one that iOS had already ended, and
the recording then continues, a new Live Activity appears.

## How long data is kept, and how to delete it

Your recordings stay on your iPhone until you delete them. Deleting cannot be undone.

- **One recording:** in History, swipe left on it and tap Delete (or touch and hold it and choose Delete), or open it
  and tap Delete Recording. Right after you end a recording, the summary offers Delete Recording (or Discard, for a
  very short recording or one with no measurable distance).
- **An unfinished recording:** choose Discard when the app asks what to do with it.
- **All recordings:** in History, tap More (…) › Delete All Recordings. This is not available while a recording is
  in progress (also while it is paused) or while the app is asking what to do with an unfinished recording.
- **Everything:** delete the app (touch and hold its icon › Remove App › Delete App). This removes all its
  recordings and settings from this iPhone. "Offload App" keeps the data.

Copies in backups made before you deleted something stay in those backups until they are replaced or deleted.
Technically, deleted data can remain in unused parts of the app's database file until that space is reused; it stays
protected by iOS and is removed together with the app. Deleting a recording also clears the log of saves (see "What
is stored").

## Your choices and rights

The developer receives no data from the app, so there is nothing to request, correct or delete about your use of it.
All data the app keeps in its own storage is on your iPhone (and in your own backups) and under your control: you can
see your recordings, their statistics and your settings in the app, delete them as described above, and turn off
location access or Live Activities at any time. This version has no export, and it does not show the positions it
stores (the GPS track of each recording, and the few positions kept to continue an unfinished one), the pause and
resume times, a recording's technical details or the log of saves. The diagnostic messages are not part of this:
they are in the iOS system log, the app does not show them, and deleting recordings or the app does not remove them;
iOS deletes them automatically after a while.

If you e-mail the developer, smartlevel GmbH uses your e-mail address and message only to answer you, and you can
ask for them to be deleted.

## Children

GPS Speed collects no personal data from anyone, including children. It has no accounts, no social features, no chat
and no ads. Parents can manage location access and Live Activities in Settings and with Screen Time.

## Changes to this policy

If this policy changes, the new version will be published at this address with a new effective date. The app cannot
tell you itself, because it has no network connection, so the App Store release notes of the version concerned will
mention the change. If a future version ever collects data, this policy and the app's privacy information in the App
Store will be updated before that version is available.

## Contact

Questions about this policy or the app's privacy: [info@smartlevel.ch](mailto:info@smartlevel.ch)

Developer: smartlevel GmbH, Ringstrasse 20, 3700 Spiez, Switzerland
