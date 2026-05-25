---
layout: default
title: Privacy Policy
---

# BillCard Privacy Policy

**Effective Date:** 2026-05-25
**Last Updated:** 2026-05-25

BillCard ("the App") is a personal credit card bill tracker developed and operated by an individual developer ("we", "us"). This policy explains what data the App handles and how.

## TL;DR

BillCard does not collect, transmit, sell, or share any of your personal data. Everything you enter stays on your device. There is no account, no server, no analytics, no ads, and no trackers.

## What Data the App Stores

The App stores the following information **locally on your device only**, inside the standard iOS application sandbox:

- Credit card metadata: bank name, last 4 digits, card holder name (optional), statement day, due day, credit limit, color, annual fee.
- Bills: statement date, due date, amount, notes.
- Payments: amount and timestamp.
- App preferences: selected interface language, biometric lock toggle, onboarding completion flag.

We deliberately ask for **only the last 4 digits** of your card number. The App never stores, requests, or transmits the full PAN (Primary Account Number), CVV, expiration date, or any data that could authorize a transaction.

## iCloud Sync (Optional)

If iCloud sync is enabled in a future version of BillCard, your data will be synchronized through **Apple's CloudKit private database**. This means:

- The data is stored under your own Apple ID's iCloud account.
- We, the developer, **cannot access this data**. CloudKit private databases are end-to-end isolated to each user; Apple does not grant developers visibility into them.
- Sync is end-to-end encrypted between your devices when iCloud Advanced Data Protection is on.

You can disable sync at any time from system Settings → [Your Name] → iCloud → BillCard.

## Data We Do NOT Collect

- We do not collect device identifiers (IDFA, IDFV, MAC address, etc.).
- We do not collect IP address, location, contacts, photos, or any other system-level data.
- We do not use analytics SDKs (no Google Analytics, Firebase, Sentry, Crashlytics, etc.).
- We do not embed advertising networks.
- We do not include third-party tracking pixels or beacons.

## Crash Reports

If you have iOS "Share With App Developers" enabled in system Settings, Apple may forward anonymized crash logs to us through Xcode Organizer. These reports contain no personal data (no card information, no usage patterns, only a symbolicated stack trace). You can disable this in iOS Settings → Privacy & Security → Analytics & Improvements.

## Notifications

BillCard schedules local notifications on your device for statement and due-date reminders. These are processed entirely by iOS and never leave your device. We do not send push notifications from a server.

## Biometric Authentication

The optional Face ID / Touch ID / passcode lock uses Apple's `LocalAuthentication` framework. Biometric data never leaves the Secure Enclave on your device and is not accessible to us.

## Children

BillCard is not directed at children under 13. We do not knowingly collect any data from anyone, including children.

## Changes to This Policy

If we change this policy, the updated version will be published at the same URL with a revised "Last Updated" date.

## Contact

Questions? Email: **iwbinb@gmail.com**

That is the only contact channel.
