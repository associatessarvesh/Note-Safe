---
title: Notesafe Privacy Policy
---

# Privacy Policy for Notesafe

**Last updated: July 6, 2026**

This Privacy Policy describes how Notesafe ("the App", "we", "us") handles your information. Notesafe is designed around a simple principle: **your notes never leave your device.**

## Summary

- Notesafe does not request Internet access. The app has no network permission at all.
- All notes are stored locally on your device in an encrypted database (SQLCipher).
- We do not collect, transmit, or have access to your notes, attachments, or any personal content.
- We do not use analytics, advertising, or crash-reporting SDKs.
- We do not have servers, and there is no Notesafe account or sign-in.

## Information We Do Not Collect

Because Notesafe has no Internet permission, we cannot and do not collect, transmit, or store any of the following on any server:

- Note titles, content, or attachments
- Voice memos recorded within the app
- Biometric data (fingerprint/face data never leaves the operating system's secure biometric APIs — Notesafe never sees or stores raw biometric information)
- Usage analytics, device identifiers, or advertising IDs

## Data Stored On Your Device

- **Notes and attachments** are stored in a local, encrypted (SQLCipher) database on your device.
- **App lock**: If you enable app lock, Notesafe uses Android's built-in Biometric/Device Credential APIs to verify your identity. Notesafe never receives or stores your fingerprint, face data, or device PIN — the operating system handles verification and only tells the app "authenticated" or "not authenticated."
- **Exports/backups**: If you choose to export or import notes, this happens only through a file picker you explicitly control (Android's Storage Access Framework). Notesafe does not upload this data anywhere; it is written to or read from a location you choose on your own device or your own cloud-storage app (e.g., if you pick a Google Drive-backed folder, that transfer is handled by your OS/file provider, not by Notesafe).

## Permissions We Request

| Permission | Why we request it |
|---|---|
| `USE_BIOMETRIC` | To let you lock the app with your fingerprint/face/device credential. |
| `RECORD_AUDIO` | Requested only at runtime, and only used if you record a voice-memo attachment (a premium feature). Audio is recorded straight to a local file attached to your note; it is never transmitted anywhere. |

Notesafe does **not** request the `INTERNET` permission, so no data can be sent off your device by the app.

## Purchases (Premium Features)

Premium features (such as custom app icons and voice-memo attachments) are unlocked via **Google Play Billing**. Purchase processing is handled entirely by Google Play. Notesafe only receives a purchase/entitlement status from the Google Play Billing library to unlock features locally — we do not receive your payment details (card number, billing address, etc.). Google's handling of that information is governed by the [Google Play Terms of Service](https://play.google.com/about/play-terms/) and [Google Privacy Policy](https://policies.google.com/privacy).

## Children's Privacy

Notesafe does not knowingly collect any information from anyone, including children, because the app collects no information at all — everything stays on-device.

## Data Deletion

Since all data lives only on your device, you are always in full control of it:

- Deleting a note or attachment in-app permanently removes it from the local encrypted database.
- Uninstalling the app removes all locally stored notes and attachments (unless you previously exported a copy yourself).

## Changes to This Policy

If Notesafe's data practices change (for example, if a future version adds an optional cloud-sync feature), this policy will be updated before that feature ships, and the "Last updated" date above will change accordingly.

## Contact

If you have questions about this Privacy Policy, contact: **associates.sarvesh@gmail.com**
