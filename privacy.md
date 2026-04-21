---
layout: default
title: Privacy Policy — Social Battery
---

# Privacy Policy

*Last updated: April 21, 2026*

## Overview

Social Battery ("the app") is built with privacy first. We collect minimal data, store as much as possible on-device, and never sell your information.

## Data We Collect

**On-device only (never leaves your phone):**

- Your social battery level and history
- Your task completions and habits
- Your buddy selection and preferences
- Notification preferences and schedules

**If you purchase a subscription (via RevenueCat):**

- Purchase receipt (processed by Apple)
- Subscription status (managed by RevenueCat)
- No payment details are ever stored by us

## Anonymous Identifier

The app generates a random UUID v4 on first launch, stored locally on your device. This identifier is not linked to your name, email, Apple ID, or any personal information. It is used solely to associate your anonymous usage events and subscription status across app sessions. It is not an advertising identifier and is never shared with data brokers.

## Data We Do NOT Collect

- No account or email required
- No location data
- No contacts or address book access
- No advertising identifiers (IDFA)
- No cross-app tracking
- No personal or wellness content from your tasks

## Third-Party Services

**PostHog** — anonymous usage analytics. We send product events (app opened, onboarding progress, tutorial steps, paywall views, subscription events, task creation and completion counts, widget interactions) identified only by your anonymous UUID. Events contain only enum values, counts, booleans and timestamps — no personal data, no task titles, no wellness content, no advertising identifiers. No cross-app tracking occurs, so no App Tracking Transparency prompt is required. Session recording is disabled. Subject to [PostHog's Privacy Policy](https://posthog.com/privacy).

**Supabase** — secure backend storage. We store your anonymous UUID along with onboarding preferences (language, experience level, preferred time, tone, buddy selection) and any feedback you choose to submit. Data is insert-only; we cannot read individual records from the client. Subject to [Supabase's Privacy Policy](https://supabase.com/privacy).

**RevenueCat** — subscription management. RevenueCat receives your anonymous UUID and Apple purchase receipt to verify and manage your subscription. No payment card details are ever stored by us or RevenueCat. Subject to their [privacy policy](https://www.revenuecat.com/privacy).

**Apple App Store** — all purchases and subscriptions are processed by Apple and subject to [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

## Notifications

The app may send local notifications (morning reminders, battery check-ins). These are scheduled entirely on-device. No data is sent to any server to trigger these notifications. You can disable them at any time in iOS Settings.

## Data Retention

Your battery levels, tasks, buddy preferences, and settings are stored locally on your device using MMKV. Deleting the app removes this local data permanently.

Anonymous onboarding preferences and feedback submitted through the app are stored on Supabase servers linked to your anonymous UUID. To request deletion of this data, contact us at [privacy@socialbattery.app](mailto:privacy@socialbattery.app).

## Children's Privacy

Social Battery is not directed at children under 13. We do not knowingly collect personal information from children under 13.

## Changes to This Policy

We may update this policy as the app evolves. We'll update the "Last updated" date above. Continued use of the app after changes constitutes acceptance.

## Contact

Questions about your privacy? [privacy@socialbattery.app](mailto:privacy@socialbattery.app)
