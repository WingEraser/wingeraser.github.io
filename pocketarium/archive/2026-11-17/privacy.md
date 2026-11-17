---
title: Pocketarium Privacy Policy (17 November 2026)
layout: default
permalink: /pocketarium/archive/2026-11-17/privacy/
---

> **Archived version — effective 17 November 2026.** The current version is at
> [https://wingeraser.github.io/pocketarium/privacy/](https://wingeraser.github.io/pocketarium/privacy/).

# Pocketarium Privacy Policy

**Last updated:** 17 November 2026<br>
**Effective date:** 17 November 2026

**Canonical version of this policy:**
https://wingeraser.github.io/pocketarium/privacy/

Pocketarium is an unofficial, fan-made Pokédex and team-building app for Android,
published by **Ka Wing Chin** ("Pocketarium", "we", "us", "our"). This
policy explains what information the app handles, why, and what you can do about
it.

This policy applies to the Pocketarium Android application (package
`com.wingeraser.pocketarium`) (the "Service"). It does not apply to third-party
sites or apps we link to.

The policy is published at the URL above so it can be updated without an app
release. That page is not itself part of the Service.

If you do not agree with this policy, please do not use the Service.

---

## 1. The short version

- **We do not operate a server that stores your trainer data.** Your teams,
  Pokédex progress, favorites, profile, and photo stay on your device.
- **Backup is optional and goes to your own Google Drive**, in a private
  app-specific folder we cannot read.
- **We do not ask for your legal name, email address, phone number, contacts,
  precise location, camera, or microphone.**
- **The app shows ads** through Google AdMob. Google may use device identifiers —
  including the Android Advertising ID — to personalize ads and measure them,
  subject to your consent choices.
- **Crash reporting is on by default** and can be turned off. **Usage analytics is
  off by default** and only runs if you turn it on.
- **We do not sell your personal information for money.**

---

## 2. Information the app handles

### 2.1 Data you create in the app (stored on your device)

| What | Examples | Stored where |
|---|---|---|
| Trainer profile | Display name, trainer ID, gender, home region, favourite types, personal tagline | App-private database on your device |
| Profile photo | An image you select with Android's system photo picker | Copied into app-private internal storage |
| Gameplay content | Teams, builds, nicknames, My Pokédex entries, favorites, badges | App-private database on your device |
| Settings | Theme, font, layout, search mode, analytics and crash-reporting switches, ad-free timer | App-private preferences on your device |

This data is used only to run the app's features. **We do not receive it.** It is
deleted when you delete it in the app, clear the app's storage, or uninstall the
app. You can remove all of it at once in **Settings → Data → Delete all data**.

You are not required to provide any of this data. The trainer name, photo, tagline,
and other profile fields are optional; leaving them blank does not prevent you from
using any feature.

The photo picker is handled by Android. The app does not request broad access to
your photo library, and it does not request camera or microphone access.

### 2.2 Google Drive backup (optional, off by default)

If you connect Google Drive and start a backup, the app sends a JSON snapshot of
your trainer profile, teams, builds, Pokédex entries, favorites, and settings to
the **private `appDataFolder` of your own Google Drive account**. This uses the
`drive.appdata` OAuth scope, so the files are not visible in your normal Drive
list and are only accessible to Pocketarium.

- We do not have access to your Google Drive and never receive a copy.
- The photo itself is not uploaded; the snapshot contains only a local file
  reference to it.
- Automatic backup is optional and runs only after you enable it.
- The app keeps between 1 and 100 backup files (10 by default), deleting the
  oldest beyond that limit.
- You can delete backups in the app (Settings → Backup) or all at once in
  **Settings → Data → Delete all data**. You can also remove Pocketarium's access
  in your Google Account permissions.

Google processes this data under its own terms and privacy policy.

Local data is not transferred automatically when you move to a new device. The
in-app Google Drive backup described above is the way to carry your data across
devices.

### 2.3 Advertising (Google AdMob)

The app displays ads supplied by **Google AdMob** (Google Mobile Ads SDK, AdMob
application ID `ca-app-pub-2121193044752436~5708354684`). To serve and measure ads,
Google and its ad partners may process:

- your **Android Advertising ID (AD ID)** and app-set ID;
- IP address (which may be used to infer approximate location);
- device and app information (model, OS version, language, app version);
- ad interactions (impressions, clicks, video completion);
- consent signals and choices you make in the consent form.

Ads may be **personalized** or **non-personalized** depending on your consent and
your device settings. In the EEA, the UK, and Switzerland, the app uses Google's
User Messaging Platform (UMP) to ask for consent before personalized ads are
requested, and you can change your choice at any time in **Settings → Privacy &
ad consent**. Where US state privacy laws require it, a similar choices form may be
shown.

You can reset or delete your Advertising ID and opt out of ad personalization in
**Android Settings → Privacy → Ads**.

Watching an optional rewarded video makes the app ad-free for 30 minutes. That is
a free feature; there are no in-app purchases or subscriptions.

### 2.4 Usage analytics (Firebase Analytics) — off by default

Usage analytics is **disabled by default**. If you switch it on in
**Settings → Analytics → Usage analytics**, Firebase Analytics collects:

- app events (screens viewed, features used) and session information;
- app and device information (app version, OS version, device model, language,
  country derived from IP);
- a pseudonymous app-instance identifier;
- diagnostic information about SDK performance.

We use this only to understand which features are used and to improve the app. We
do not use it to identify you, and we do not combine it with your trainer profile.
Advertising-ID collection for analytics is disabled in the app configuration.

You can turn analytics off at any time; this stops further collection.

### 2.5 Crash reporting (Firebase Crashlytics) — on by default

Crash reporting is **enabled by default**. When the app crashes or becomes
unresponsive, Crashlytics collects:

- the crash stack trace and the state of the app at the time;
- app version, device model, OS version, and available memory/disk;
- a randomly generated Crashlytics installation identifier.

This is used to diagnose and fix defects. It does not include your teams,
Pokédex progress, trainer name, or photo. You can turn it off in
**Settings → Analytics → Crash reporting**.

### 2.6 Network requests

The app makes HTTPS requests to:

- Google servers (ads, analytics if enabled, crash reporting, Drive if enabled);
- `raw.githubusercontent.com`, to fetch Pokémon artwork when a bundled asset is
  missing;
- `pokeapi.co`-derived data is bundled in the app at build time; the app does not
  send your data to PokéAPI.

These requests necessarily disclose your IP address and basic request metadata to
those providers.

### 2.7 Sharing features

Team and build sharing encodes your team data into a link. If you share that link,
the payload — which may include team names and nicknames you chose — is handled by
the app you send it through. A `pocketarium://` link opens Pocketarium on a device
where the app is installed. Do not include personal information in team names or
your tagline if you plan to share them.

### 2.8 Communications

If you use **Send feedback**, your email app opens with a pre-filled message
addressed to `wingeraser@gmail.com`. Nothing is sent until you press send. If you
email us, we receive your email address and whatever you include, and we use it
only to answer you.

We may also see reviews and ratings you post on Google Play, under Google's terms.

---

## 3. What we do not collect

We do not request or receive:

- your legal name, email address, or phone number (unless you email us);
- precise location (GPS);
- contacts, calendar, SMS, or call logs;
- microphone or camera access;
- health, biometric, or financial information;
- passwords or payment card details — the app has no accounts and no purchases.

We do not build advertising profiles of you ourselves, and we do not sell personal
information for money.

---

## 4. Why we process information (legal bases)

Where the GDPR or UK GDPR applies, we rely on:

| Purpose | Legal basis |
|---|---|
| Running the app's on-device features | Performance of a contract (Art. 6(1)(b)) |
| Optional Google Drive backup you start | Performance of a contract / your request (Art. 6(1)(b)) |
| Personalized advertising and optional analytics | Your consent (Art. 6(1)(a)) — withdrawable at any time |
| Non-personalized advertising, fraud prevention, security | Legitimate interests (Art. 6(1)(f)) |
| Crash reporting and app stability | Legitimate interests (Art. 6(1)(f)); you can object |
| Responding to your messages | Legitimate interests / pre-contractual steps |
| Legal compliance | Legal obligation (Art. 6(1)(c)) |

We do not process special-category data and we do not carry out automated
decision-making with legal or similarly significant effects.

---

## 5. Who we share information with

We do not sell your personal information for money. We share it only as
described here:

| Recipient | Purpose | Data |
|---|---|---|
| **Google LLC / Google Ireland Ltd** — AdMob | Advertising, measurement, consent management | Advertising ID, IP, device/app data, ad interactions, consent signals |
| **Google** — Firebase Analytics | Usage analytics, only if you opt in | App events, device/app data, pseudonymous instance ID |
| **Google** — Firebase Crashlytics | Crash diagnostics, on by default | Crash traces, device/app state, installation ID |
| **Google** — Identity / Drive API | Optional backup you start | OAuth token, backup file in your own Drive |
| **GitHub, Inc.** (`raw.githubusercontent.com`) | Artwork fallback | IP address, requested URL |
| **Your email provider and ours** | Feedback you choose to send | Email content you write |

For advertising, Google acts as an independent controller for some processing and
may use data across apps and sites; see Google's
[Privacy & Terms](https://policies.google.com/technologies/partner-sites). Our
agreements with Google require it to protect data consistently with this policy
and applicable law.

We may also disclose information if required by law, to enforce our Terms, or to
protect rights and safety. If the app or its assets are transferred to a successor,
information may transfer with them, subject to this policy.

Under some US state laws, sharing identifiers for cross-context behavioural
advertising may count as "sharing" or a "sale". You can opt out through the
in-app consent/choices form and your Android ad settings.

---

## 6. International transfers

Google processes data in the United States and other countries. Where personal
data leaves the EEA, the UK, or Switzerland, we rely on:

- the **EU-US Data Privacy Framework** (and its UK Extension and Swiss-US
  framework) where the recipient is certified; and
- the **European Commission's Standard Contractual Clauses** and the UK
  International Data Transfer Addendum where required.

You can ask us for more information about the safeguards we use.

---

## 7. Retention

| Data | How long |
|---|---|
| On-device app data | Until you delete it in the app, clear app storage, or uninstall |
| Google Drive backups | Until you delete them; the app keeps 1–100 (default 10), deleting the oldest automatically |
| Crash reports | Up to 90 days in Firebase Crashlytics by default |
| Analytics data | As configured in our Firebase project (up to 14 months) |
| Ad data | Per Google's retention policies |
| Emails you send us | As long as needed to handle your request, then up to 24 months |

We do not use a single fixed retention period for all data, because each
category has different purposes and providers.

---

## 8. Security

- On-device data sits in the app's private sandbox, protected by Android's app
  isolation and your device lock.
- All network traffic uses HTTPS/TLS.
- Google Drive backups use OAuth with the narrow `drive.appdata` scope.
- We do not run a backend that stores your data, which removes a large class of
  risk.
- Access tokens are short-lived and are not stored by the app.

No method of transmission or storage is completely secure. You are responsible for
keeping your device and Google Account secure.

---

## 9. Your choices and controls

| Choice | Where |
|---|---|
| Turn usage analytics on/off | Settings → Analytics → Usage analytics |
| Turn crash reporting on/off | Settings → Analytics → Crash reporting |
| Change ad consent / personalized ads | Settings → Privacy & ad consent (EEA/UK/CH and where required) |
| Reset or delete Advertising ID | Android Settings → Privacy → Ads |
| Connect or disconnect Google Drive | Settings → Backup |
| Delete backups | Settings → Backup → History |
| Delete all data | Settings → Data → Delete all data (optionally including Google Drive backups) |

---

## 10. Your rights

### 10.1 EEA, UK, and Switzerland

You have the right to access, correct, delete, restrict, or object to processing of
your personal data, to data portability, and to withdraw consent at any time
(without affecting processing already carried out). You also have the right to
lodge a complaint with your local supervisory authority — in the Netherlands, the
Autoriteit Persoonsgegevens.

Because most data never leaves your device, you can delete it at any time in
**Settings → Data → Delete all data**, or by uninstalling the app. That control can
also remove the backups stored in your Google Drive. We cannot access or delete
files in your personal Google Drive ourselves; you can also remove them in Drive or
by revoking Pocketarium's access in your Google Account.

### 10.2 California (CCPA/CPRA)

We collect the following categories of personal information: identifiers
(Advertising ID, IP address, app-instance ID), internet or network activity (app
usage, ad interactions), and approximate geolocation derived from IP. We do not
collect sensitive personal information for the purpose of inferring
characteristics. Sources, purposes, and recipients are described in sections 2 and
5.

You have the right to know, delete, correct, and obtain a copy of your personal
information, to opt out of the sale or sharing of personal information, to limit
the use of sensitive personal information, and not to be discriminated against for
exercising these rights. You may use an authorized agent. We do not knowingly sell
or share the personal information of consumers under 16.

To opt out of sharing for personalized advertising, use the in-app consent form
and Android's ad settings, or email us. We aim to respond within 45 days.

### 10.3 Other US states

Residents of states with comprehensive privacy laws (including Virginia,
Colorado, Connecticut, Utah, Texas, Oregon, and Montana) have rights to confirm,
access, correct, delete, and obtain a portable copy of their data, and to opt out
of targeted advertising, sale, and certain profiling. You may appeal a refusal by
replying to our decision; we will explain the outcome in writing.

### 10.4 How to exercise your rights

Email **wingeraser@gmail.com** with the right you want to exercise. We may ask for
information needed to verify your request. We will respond within the time required
by law (normally one month under the GDPR and 45 days under the CCPA). Exercising
your rights is free. Most local data can also be deleted immediately in
**Settings → Data → Delete all data**.

---

## 11. Children's privacy

Pocketarium is **not directed to children under 13** (or under 16 in the EEA and
UK). We do not knowingly collect personal information from children. The app is
not configured for child-directed advertising.

If a child has used the app, you can remove the data by deleting it in the app,
clearing the app's storage, or uninstalling the app. For Google Drive backups,
delete them in the app or in the Google Account used for the backup.

---

## 12. Cookies and similar technologies

The Android app does not use browser cookies. It uses local storage and SDK
identifiers (such as the Advertising ID and app-instance ID) for the purposes
described above.

This policy page is hosted by GitHub Pages. GitHub may process technical
information such as your IP address in its server logs when you open it, under
GitHub's privacy statement.

We do not currently respond to browser "Do Not Track" signals.

---

## 13. Third-party links and Pokémon trademarks

The app links to third-party sites (for example PokéAPI, Google, and font and icon
projects). We are not responsible for their privacy practices; review their
policies.

Pokémon, Pokémon character names, and Pokémon artwork are trademarks of Nintendo,
Creatures Inc., and GAME FREAK inc. Pocketarium is an unofficial fan-made
application and is not affiliated with, endorsed, or sponsored by Nintendo,
GAME FREAK, or The Pokémon Company.

---

## 14. Changes to this policy

We may update this policy from time to time. We will post the new version at the
canonical URL above and update the "Last updated" date. If a change materially
affects your rights, we will provide additional notice in the app before it takes
effect. Continued use after the effective date means you accept the updated
policy.

---

## 15. Contact us

- **Data controller:** Ka Wing Chin
- **Email:** wingeraser@gmail.com
- **Location:** Enschede, the Netherlands
- **Postal address:** available on request for legal correspondence

We answer privacy questions and requests at the email address above.
