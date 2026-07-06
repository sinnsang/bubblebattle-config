---
layout: default
title: BubbleBattle Privacy Policy
---

# BubbleBattle Privacy Policy

**Last updated: 2026-07-06**

The individual developer ("we", "our") values the privacy of users of the mobile game **BubbleBattle** ("the App") and complies with applicable laws. This policy explains what information the App collects and how we use it, along with your rights.

## 1. Information We Collect

The App collects the minimum information required to operate.

| Item | Collected When | Stored Where | Purpose |
|---|---|---|---|
| **Advertising Identifier** (IDFA/AAID) | App launch (auto-collected by ad SDK) | Google AdMob servers | Personalized ads, frequency capping |
| **Device unique identifier** (random string) | On first launch (auto-generated) | On-device (iOS Keychain / Android SharedPreferences) | Reconnecting to multiplayer sessions |
| **Player nickname** | Entered by user when joining a room | Firebase Realtime Database (in-memory room state) | Display to other participants |
| **Anonymous auth UID** | On app boot (Firebase anonymous auth) | Firebase Authentication | Server access permission (anonymous), room access control |
| **Game state** (HP, position, kills, etc.) | During multiplayer sessions | Firebase Realtime Database | Real-time synchronization |

**We do NOT collect**: name, email, phone number, precise location (GPS), photos, contacts, or payment information.

## 2. Purposes of Use

Collected data is used only for the following purposes:

- Multiplayer matchmaking and real-time game state synchronization
- Advertising delivery and improvement (Google AdMob)
- Fraud prevention and service improvement through statistical analysis
- App version management and required update notifications

## 3. Retention Period

- **Multiplayer room data**: Auto-deleted 6 hours after room creation, or when the last participant leaves
- **Device unique identifier**: Until the app is uninstalled (persists across reinstall on iOS, regenerated on Android)
- **Advertising identifier**: Reset/blocked immediately when reset by user in device settings
- **Anonymous auth UID**: Retained per Firebase policy for as long as the user continues to use the app without reinstalling

## 4. Third-Party Processors

We entrust data processing to the following providers:

| Provider | Purpose | Data shared | Privacy policy |
|---|---|---|---|
| **Google LLC — Firebase** | Multiplayer session storage & authentication | Anonymous UID, player nickname, game state | https://firebase.google.com/support/privacy |
| **Google LLC — AdMob** | Ad delivery | Advertising identifier, device info | https://policies.google.com/technologies/ads |

We do not sell or transfer user data for any other purpose.

## 5. User Rights and Deletion Requests

- **Opt out of personalized ads**: In device Settings → Privacy → Apple Advertising (iOS) / Android Ads (Android), reset/limit ad ID
- **Data deletion**: Uninstalling the app immediately removes on-device data (saved nickname, etc.)
- **Requests**: Contact the email below; requests will be processed within 7 business days

## 6. Children's Privacy

The App does not primarily target children under 13. If we become aware that we have collected data from a child under 13, we will delete it immediately. Children should use the App under parental supervision.

## 7. Policy Changes

If this policy changes, we will notify users via in-app announcements and by updating this page. For material changes, a notice will be displayed on app launch.

## 8. Contact

- **Developer**: Individual Developer
- **Contact email**: sinnsang@naver.com
- **Location**: Republic of Korea

---

*This policy has been prepared in accordance with Google Play Store, Apple App Store, and Google AdMob requirements.*
