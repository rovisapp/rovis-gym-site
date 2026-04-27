---
layout: default
title: Privacy Policy
---

# Privacy Policy

_Last updated: 2026-04-27_

Rovis Gym ("the app") is designed to be a fully on-device tool. Your workout data stays on your iPhone, your Apple Watch, and (if you have it enabled) your iCloud account synced via Apple's standard CloudKit. **The app itself does not transmit your data to the developer or any third party.**

## What data the app stores on your device

- **Exercises, sets, weights, reps, timestamps** — everything you log during a workout.
- **Per-session heart-rate samples** (only if you opt in to heart-rate recording in Settings, and only if you grant Apple Health permission).
- **App preferences** (units, rest-timer length, notification settings, etc.).
- **Optional diagnostic logs** (only if you turn on "Record diagnostic logs" in Settings; see below).

All of this is stored locally on your device and, if iCloud sync is enabled, in your private iCloud database — which only you can access. The developer cannot access your iCloud data.

## Apple Health (HealthKit)

If you grant permission:

- **Read access** to your heart-rate data, used to display your live HR during a workout and summarize it per set.
- **Write access** to write your completed strength workouts to Apple Health so they count toward your Activity rings.

HealthKit data is stored by iOS itself, not by the app. It is never transmitted off your device by Rovis Gym. You can revoke either permission at any time from iOS Settings → Health → Data Access & Devices.

## Diagnostic logs

The "Record diagnostic logs" setting is **off by default**. When you turn it on, the app records timestamped events (e.g., "workout started," "set logged," "watch sync received") to a local file on your device.

These logs:

- Stay on your device.
- Are visible to you in-app under Settings → Diagnostics → View logs.
- Are kept for up to 14 days, then automatically deleted.
- Are **only** transmitted off your device if you explicitly tap **Settings → Diagnostics → Export logs (CSV)** and choose a destination yourself (Mail, Messages, Files, etc.) via the iOS share sheet.

The app does not send these logs anywhere automatically. The decision to share — and with whom — is entirely yours.

## What the app does not do

- The app **does not require an account**.
- The app **does not collect analytics or usage telemetry** of any kind.
- The app **does not contain advertising or tracking SDKs**.
- The app **does not share data with third parties**.
- The app **does not make network requests** other than:
  - Apple's standard system services (CloudKit, if you enable iCloud sync; HealthKit, if you grant permission).
  - The system share sheet, which only fires when you explicitly tap an export button.

## Children's privacy

Rovis Gym is not directed at children under 13 and does not knowingly collect any information from them. The app does not collect any personal information from any user.

## Changes to this policy

If this policy changes, the "Last updated" date at the top will reflect the new version. Substantive changes will be announced in the app's release notes.

## Contact

Questions about this policy? Email **uadrive1@gmail.com**.
