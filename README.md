# Privacy Policy — Rudimentalist for iOS

**Effective date:** 2026-05-06
**Last updated:** 2026-05-06

---

## Summary (the short version)

Rudimentalist is a drumming practice app that listens through your device's microphone to detect when you hit a practice pad and score your timing against a metronome. **Your audio is processed entirely on your device, in real time, and is never recorded, saved, or transmitted to us or anyone else.** We do not collect personal information, we do not have user accounts, we do not use third-party tracking, and we do not show advertising. The only piece of data the app stores is a single number — your latency calibration offset — and it stays on your device.

The full policy below explains the details.

---

## 1. Who we are

Rudimentalist is published by Ilker Uzun ("we", "us", "our"). This privacy policy applies to the Rudimentalist iOS app (bundle identifier `com.rudimentalist.ios`) distributed through the Apple App Store.

If you have any questions about this policy or your privacy when using the app, contact us at **ios.app@rudimentalist.com**.

## 2. What information the app accesses

### 2.1 Microphone audio (processed on-device, not retained)

Rudimentalist uses your device's microphone to detect drum hits while you practise. We need the microphone because that's how the app figures out when you've struck the practice pad and how that timing compares to the metronome click.

**Critical points about how we handle audio:**

- Audio is analysed in real time, frame by frame, on your device only.
- Audio is **never recorded** to a file.
- Audio is **never saved** to disk, the cloud, or any server.
- Audio is **never transmitted** off your device — not to us, not to Apple, not to any third party.
- After each fragment of audio is analysed for timing information, it is discarded immediately.
- The app does not perform speech recognition or any other content analysis on the audio. It only measures the timing of detected percussive impacts.

The microphone is only active while a practice session, calibration session, or count-in is in progress. When you leave the practice screen, the app stops capturing audio.

iOS will prompt you for microphone permission the first time you start a practice session. You can revoke this permission at any time via iOS **Settings → Privacy & Security → Microphone → Rudimentalist**. If you revoke it, the app cannot run any practice or calibration session, but no other functionality is affected.

### 2.2 Latency calibration offset (stored locally)

The app measures your device's audio input latency once, via a guided calibration flow. The result is a single number in milliseconds (typically between 0 and 250 ms depending on your headphones and hardware) which is saved on your device using iOS's standard `UserDefaults` storage under the key `latencyOffsetMs`.

This number is:

- Not personally identifying.
- Not transmitted off your device.
- Used only to correct the timing math for hit detection so the app's scoring is fair to your hardware.
- Removed automatically when you uninstall the app.

That is the **only** piece of data the app stores about you.

## 3. What information the app does NOT access or collect

To be explicit, Rudimentalist does **not** collect, access, or transmit any of the following:

- Your name, email address, phone number, or any other contact information.
- Your location, IP address, or device identifiers (other than the standard ones Apple makes available to all apps for crash reporting — see Section 5).
- Your contacts, calendar, photos, files, or any other content on your device.
- Any audio recording (your microphone input is analysed in real time and never stored).
- Any practice history, timing scores, hit counts, or other session data beyond the current session in memory. When you close the practice screen, all session statistics are discarded.
- Any health, fitness, financial, or biometric data.
- Any advertising identifier (IDFA). Rudimentalist does not display ads or use advertising networks.
- Any cross-app or cross-website tracking. Apple's App Tracking Transparency framework is not used because there is nothing to track.

## 4. How information is shared

We do not share information about you, because we do not collect information about you. There is nothing to share, sell, rent, or trade.

We do not use third-party analytics services (Google Analytics, Firebase Analytics, Mixpanel, etc.), third-party crash reporters (Firebase Crashlytics, Sentry, Bugsnag, etc.), or third-party advertising networks. The app's source code is auditable on request — we do not include any such SDK.

## 5. Diagnostic data collected by Apple

If you have **iOS Settings → Privacy & Security → Analytics & Improvements → Share with App Developers** turned on (this is a setting you control on your device, not a setting we control), Apple collects anonymised diagnostic data including:

- App crash reports
- App launch time and energy use
- Aggregated session counts

Apple aggregates this data across many users and provides it to us through App Store Connect. We can see, for example, how often the app crashes on each iOS version — but we cannot identify individual users from this data.

We use this data only to fix bugs and improve performance. You can opt out at any time by toggling **Share with App Developers** off in iOS Settings.

This data flow is governed by [Apple's Privacy Policy](https://www.apple.com/legal/privacy/), not ours, because Apple is the party that collects it.

## 6. Children's privacy

Rudimentalist has an Apple App Store age rating of **4+**, meaning it is suitable for users of all ages. The app does not collect personal information from anyone, including children under 13 (United States) or under 16 (European Union and certain other regions). Because no data is collected, the app is naturally compliant with the Children's Online Privacy Protection Act (COPPA) and equivalent international standards.

If a parent or guardian has any concerns about a child's use of Rudimentalist, please contact us at the email address in Section 9.

## 7. Your rights under GDPR, CCPA, and similar regulations

Privacy regulations in many jurisdictions (the EU's GDPR, California's CCPA / CPRA, the UK's Data Protection Act, Brazil's LGPD, etc.) give users rights to access, correct, port, or delete personal data held about them by a service.

Because Rudimentalist does not collect or store any personal data on our servers — we have no servers — there is no data for us to provide, correct, port, or delete on request. The only data the app stores (your latency calibration offset) is on your own device, under your control, and is removed automatically when you uninstall the app.

If you are in a jurisdiction with rights of access or deletion and would like written confirmation of our data-handling practices for your records, contact us at **ios.app@rudimentalist.com** and we will respond within the timeframes required by applicable law.

## 8. Changes to this privacy policy

We may update this privacy policy from time to time, particularly if the app gains new features that involve new data flows (for example, optional cloud sync, user accounts, or third-party crash reporting in future versions). When we make a material change, we will:

- Update the **Effective date** and **Last updated** at the top of this document.
- For significant changes (any new collection, sharing, or transmission of data), notify users via an in-app notice on the next launch and require explicit acknowledgement before continuing.

The current and historical versions of this policy are available at the URL where you found this page.

## 9. Contact us

For any questions about this privacy policy or about how Rudimentalist handles your information, contact us at:

**ios.app@rudimentalist.com**

We aim to respond as soon as we can. For formal data-rights requests under GDPR, CCPA, or similar regulations, we respond within the timeframes required by applicable law (see Section 7).
