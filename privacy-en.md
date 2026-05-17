---
layout: default
title: Privacy Policy — Earnly Driver
permalink: /privacy/
---

# Privacy Policy

**Last updated:** May 17, 2026
**Effective date:** May 17, 2026

Earnly Driver ("the App") is developed and operated by **Liber Varona** ("we," "us," or "the Developer"). This Privacy Policy describes how the App handles your information.

**Summary:** Earnly Driver runs entirely on your iPhone. It has no servers, no user accounts, no analytics, and no advertising. Your shift data and location history stay on your device by default. The only data that ever leaves your device does so when you explicitly choose it — by exporting a CSV, or by turning on the optional "Look up shift addresses" setting (off by default), which sends only your shift start/end coordinates to Apple to resolve a street address. We cannot see, access, or recover your data, and the Developer never receives it.

---

## 1. Information We Collect

Earnly Driver collects only the information you explicitly provide while using the App, and the location data required to track an active shift you have started.

### 1.1 Shift information you enter
- Shift block start and end times
- Mileage (when manually edited; otherwise calculated from GPS)
- Personal notes you choose to add to a shift
- Reason for any edits you make to a saved shift (for audit trail purposes)

### 1.2 Location data (only during an active shift)
When you tap **Start Shift**, the App begins recording your device's location in order to calculate distance driven, duration, and effective hourly rate. Location tracking automatically stops when you tap **End Shift**.

- Location is collected **only** while a shift is active and you have explicitly started it.
- Location is collected in the background so the App can keep tracking when your screen is locked or another app is open during your shift.
- We do **not** transmit your location off the device, with one optional exception you control: if you turn on **Look up shift addresses** in Settings (off by default), only the coordinates of your shift's start and end points are sent to Apple's geocoding service to resolve a street address. Nothing else is sent, and nothing is ever sent to the Developer. See Section 4.

### 1.3 Information we do NOT collect
- We do not collect your name, email address, phone number, photo, or any other identifying information.
- We do not require you to create an account or sign in.
- We do not collect device identifiers (IDFA, advertising ID, etc.).
- We do not use analytics SDKs (Firebase Analytics, Mixpanel, Amplitude, Google Analytics, etc.).
- We do not use crash reporting SDKs (Crashlytics, Sentry, etc.).
- We do not use advertising networks.
- We do not track you across other apps or websites.

---

## 2. How Your Data Is Stored

All data described in Section 1 is stored **locally** on your iPhone using Apple's SwiftData framework. The data resides in the App's private sandbox container, encrypted at rest by iOS.

- The data is **not** synced to iCloud unless and until a future version of the App offers that feature and you explicitly opt in. The current version does not sync any data anywhere.
- Except for the optional address lookup described in Section 4, the data is **not** transmitted to any server. The Developer operates no server and never receives your data under any circumstances.
- The data is included in your standard iPhone backup (iCloud Backup or encrypted local backup) only if you have those backups enabled in your iPhone Settings. Those backups are controlled entirely by Apple and your Apple ID; the Developer has no access to them.

---

## 3. How We Use Your Data

The App uses the data you enter and the location data you authorize **only** for the purposes you started the App for:

- Calculating total miles driven per shift, week, and month
- Estimating your IRS mileage deduction based on the standard rate
- Showing your shift history
- Exporting your own data when you choose to (CSV export to the Files app or via Share Sheet)

We do not use your data for any other purpose. We do not profile you, score you, sell insights about you, or share your data with anyone.

---

## 4. Sharing of Information

We do **not** sell, rent, trade, or share your personal data with any third party.

There are three situations in which your data may leave your device, and each occurs only at your explicit direction:

1. **CSV export.** You can tap **Export Data** to generate a CSV file containing your shift history. The export is delivered via the iOS Share Sheet, and you choose where it goes (email, Files, AirDrop, etc.). Until you initiate this export and choose a destination, your data stays on your device.
2. **Standard iPhone backup.** As noted in Section 2, your data is included in your iPhone's standard backup if you have backups enabled. This is governed by Apple's iCloud terms and your device settings, not by us.
3. **Optional address lookup.** The **Look up shift addresses** setting is **off by default**. If you turn it on, then each time you end a shift the App sends only the start and end GPS coordinates of that shift to Apple's geocoding service to obtain a human-readable street address shown in Shift Detail. Only those two coordinate pairs are sent; no other shift data, and nothing to the Developer. You can turn this off at any time in Settings, and it never runs while it is off. This uses Apple's CLGeocoder and is subject to Apple's privacy terms.

---

## 5. Your Rights and Controls

Because all data stays on your device, you have complete control:

- **Delete a shift:** Open any shift in the history tab and tap delete.
- **Delete all data:** Delete the App from your iPhone. All data is removed with the App per iOS sandbox rules.
- **Revoke location access:** Go to **Settings → Privacy & Security → Location Services → Earnly Driver** and change permissions at any time. Note that disabling location while a shift is active will prevent the App from calculating distance for that shift.
- **Export your data:** Use the **Export Data** function in the App to receive a CSV file of all your shift history.

We cannot delete data on your behalf because we do not have access to it. We cannot recover data on your behalf for the same reason. If you uninstall the App without exporting first, the data is permanently lost (unless restored from a device backup).

---

## 6. Children's Privacy

Earnly Driver is intended for use by Amazon Flex delivery drivers, who must be at least 21 years old to drive for Amazon Flex in the United States. The App is not directed to children under 13 and we do not knowingly collect any information from anyone, including children.

---

## 7. Permissions Requested

The App requests the following iOS permissions:

| Permission | Why | When |
|---|---|---|
| **Location — Always** | To track distance and route during a shift, including when the screen is locked or another app is in the foreground | Only while a shift is active. Tracking stops automatically when you tap End Shift. |
| **Notifications** | To remind you to start a shift block on time, and to surface the Live Activity counter on your Lock Screen during an active shift | Optional. The App functions without notifications enabled. |
| **Motion & Fitness** *(if requested in a future update)* | To improve distance accuracy when GPS signal is weak | Not requested in the current version. |

You can grant, deny, or revoke any of these permissions at any time in **Settings → Privacy & Security**.

---

## 8. Security

Your data is protected by the standard iOS security model:
- Encrypted at rest on your device using Apple's data protection
- Stored in the App's private sandbox, inaccessible to other apps
- Protected by your iPhone passcode, Face ID, or Touch ID

Because we do not transmit or store your data on any server, there is no server-side breach risk.

---

## 9. Third-Party Services

Earnly Driver does not integrate with any third-party SDKs, analytics platforms, advertising networks, or social media tools.

Earnly Driver uses Apple's own frameworks (CoreLocation, MapKit, SwiftData, ActivityKit, UserNotifications, and CLGeocoder for the optional reverse geocoding feature). Apple's privacy practices for these frameworks are described in Apple's own privacy policy at <https://www.apple.com/legal/privacy/>. When you use the optional reverse geocoding feature, your shift coordinates are sent to Apple's geocoding service and are subject to Apple's privacy practices, not the Developer's.

---

## 10. Changes to This Policy

If we update this Privacy Policy in a future version of the App, the updated policy will be published at this URL and the "Last updated" date at the top will change. Material changes will be highlighted in the App's release notes.

---

## 11. Contact

If you have questions about this Privacy Policy or about how the App handles data, contact the Developer at:

**Email:** earnlydriver@gmail.com

We typically respond within 2 business days.

---

*Earnly Driver is an independent app and is not affiliated with, endorsed by, or sponsored by Amazon.com, Inc. or any of its subsidiaries. "Amazon Flex" is a trademark of Amazon.com, Inc.*
