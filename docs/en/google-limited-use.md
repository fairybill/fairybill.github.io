---
layout: default
title: "Google user data — Limited Use (FairyBill)"
lang: en
permalink: /en/google-limited-use/
alternates:
  - { lang: en, label: English, url: /en/google-limited-use/ }
  - { lang: fr, label: Français, url: /fr/google-limited-use/ }
  - { lang: zh, label: 中文, url: /zh/google-limited-use/ }
---

# Google user data — Limited Use (FairyBill)

FairyBill’s use of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the **Limited Use** requirements.

## Scopes

The app requests Gmail read-only access (`https://www.googleapis.com/auth/gmail.readonly`) so it can:

- Search for messages that look like household bills or utility statements.
- Optionally read Interac e-Transfer notification mail when you turn on “Sync e-Transfer” in Settings.

## Limited Use statement

FairyBill uses Gmail data **only** to provide user-facing features inside the app (bill list, summaries, reminders). Specifically:

1. **No transfer** of Gmail data to third parties except as needed to provide the feature (Google’s infrastructure), comply with law, or as part of a merger with notice — and never for unrelated advertising.
2. **No use** of Gmail data for serving ads, including retargeting or personalized ads.
3. **No use** of Gmail data for unrelated machine-learning model training (general or non-user-facing).
4. **Human access** to Gmail content is limited to security, compliance, debugging with consent, or legal requirements — not for routine operations.

Bill extraction runs on the device; we do not operate a cloud inbox copy service.

## Storage

OAuth tokens and downloaded bill-related content are stored **on your device only**.

## Revocation

You can disconnect in the app or remove FairyBill under [Google Account → Third-party access](https://myaccount.google.com/permissions).

## Contact

[spliteasyone@gmail.com](mailto:spliteasyone@gmail.com)
