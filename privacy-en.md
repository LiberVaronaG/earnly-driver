---
layout: default
title: Privacy Policy — Earnly Driver
permalink: /privacy/
---

# Privacy Policy

**Last updated:** May 18, 2026
**Effective date:** May 18, 2026

Earnly Driver ("the App") is developed and operated by **Liber Varona** ("we," "us," or "the Developer"). This Privacy Policy describes how the App handles your information.

**Summary:** Earnly Driver runs entirely on your iPhone. It has no servers, no user accounts, no analytics, and no advertising. Your shift data, personal-trip data, and location history stay on your device. The only data that ever leaves your device does so when you explicitly choose it — by exporting a CSV or PDF, or by turning on the optional "Look up addresses" setting (off by default), which sends only the start and end coordinates of a shift or personal trip to Apple to resolve a street address. We cannot see, access, or recover your data, and the Developer never receives it.

---

## 1. Information We Collect

Earnly Driver collects only the information you explicitly provide while using the App, the location data required to track a work shift you have started, and — only if you opt in — the location and motion data required to detect your personal drives.

### 1.1 Shift information you enter or generate
- Work shift start and end times
- The platform you drove for (for example Amazon Flex, Uber, Lyft, DoorDash, Instacart, Spark Driver, GrubHub), including more than one platform when you stack apps on a single drive
- Mileage (calculated from GPS during a tracked shift, or entered and edited by you)
- Earnings you choose to enter: gross pay, tips, and the pay from any additional platforms you stacked
- Personal notes you choose to add to a shift
- Reason for any edits you make to a saved shift (kept for your own audit trail)

### 1.2 Vehicle, expense, and tax information you enter
- Vehicle make, model, year, and fuel type
- Fuel price per gallon or per kWh, if you choose to enter it (used to estimate fuel cost)
- Vehicle operating expenses you log — for example gas, oil changes, repairs, insurance, registration — including the amount, date, category, and the business-use percentage you assign to each
- Your hourly take-home goal, if you choose to set one
- Your U.S. state, if you choose to set it
- Saved "stations" — locations you name and save (for example a delivery warehouse), each stored as a name, a coordinate, a radius, an optional resolved street address, an optional quiet-hours window, and any free-text note you add (such as a gate code or parking instructions)

### 1.3 Location data — work shifts
When you tap **Start Shift**, the App begins recording your device's location in order to calculate distance driven, route, duration, and effective hourly rate. Location tracking automatically stops when you tap **End Shift**.

- Location is collected **only** while a work shift is active and you have explicitly started it.
- Location is collected in the background so the App can keep tracking when your screen is locked or another app is open during your shift.
- Your location is **not** transmitted off the device, except for the optional address lookup described in Section 4.

### 1.4 Location and motion data — personal trips (optional, off by default)
Earnly Driver includes an optional feature, **Auto-track personal miles**, found in Settings. It is **off by default**. You must turn it on yourself.

When — and only when — you enable it:
- The App uses Apple's **Core Motion** framework to detect when you are driving in a vehicle. Motion data is processed entirely on your device and is never transmitted anywhere.
- When a personal (non-work) drive is detected, the App records its route, distance, and times as a "personal trip," stored locally on your device.
- Personal trips are kept completely separate from work data. They never count toward your earnings, your "miles today," your monthly totals, or your IRS export.
- Personal-trip tracking automatically stands down whenever a work shift is active. Work miles are always started by you, by hand — the App never converts a detected drive into a work shift automatically.
- You can turn this feature off at any time in Settings. When it is off, no motion or background location data is collected for personal trips.

### 1.5 Information we do NOT collect
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

The App uses the data you enter and the location data you authorize **only** for the purposes you installed the App for:

- Calculating total miles driven per shift, week, and month
- Calculating your real earnings per hour, cost per mile, and net profit after fuel
- Estimating your IRS standard-mileage deduction
- Comparing the standard-mileage method against your logged actual operating expenses
- Estimating self-employment tax to set aside
- Showing your shift history and personal-trip history
- Helping you decide whether a delivery block or offer is worth accepting
- Exporting your own data when you choose to (CSV or PDF export to the Files app or via the iOS Share Sheet)

We do not use your data for any other purpose. We do not profile you, score you, sell insights about you, or share your data with anyone.

---

## 4. Sharing of Information

We do **not** sell, rent, trade, or share your personal data with any third party.

There are three situations in which your data may leave your device, and each occurs only at your explicit direction:

1. **CSV and PDF export.** You can export your shift history as a CSV file, or a tax-year summary as a PDF. The export is delivered through the iOS Share Sheet, and you choose where it goes (email, Files, AirDrop, etc.). Until you initiate an export and choose a destination, your data stays on your device.
2. **Standard iPhone backup.** As noted in Section 2, your data is included in your iPhone's standard backup if you have backups enabled. This is governed by Apple's iCloud terms and your device settings, not by us.
3. **Optional address lookup.** The **Look up addresses** setting is **off by default**. If you turn it on, then each time a work shift or personal trip ends, the App sends only the start and end GPS coordinates of that shift or trip to Apple's geocoding service to obtain a human-readable street address shown in the detail screen. Only those coordinate pairs are sent; no other shift, trip, earnings, or vehicle data, and nothing to the Developer. You can turn this off at any time in Settings, and it never runs while it is off. This uses Apple's CLGeocoder and is subject to Apple's privacy terms.

---

## 5. Your Rights and Controls

Because all data stays on your device, you have complete control:

- **Delete a shift or personal trip:** Open it in the History tab and delete it. Deleted items go to Trash and can be restored for 30 days, after which they are permanently removed.
- **Delete all data:** Delete the App from your iPhone. All data is removed with the App per iOS sandbox rules.
- **Revoke location access:** Go to **Settings → Privacy & Security → Location Services → Earnly Driver** and change permissions at any time. Note that disabling location while a shift is active will prevent the App from calculating distance for that shift.
- **Revoke motion access:** Go to **Settings → Privacy & Security → Motion & Fitness** and change the permission at any time. You can also turn off **Auto-track personal miles** directly in the App's Settings.
- **Export your data:** Use the **Export** function in the App to receive a CSV or PDF of your history.

We cannot delete data on your behalf because we do not have access to it. We cannot recover data on your behalf for the same reason. If you uninstall the App without exporting first, the data is permanently lost (unless restored from a device backup).

---

## 6. Children's Privacy

Earnly Driver is a tool for gig and delivery drivers, who must be adults to drive for the delivery and rideshare platforms the App supports. The App is not directed to children under 13, and we do not knowingly collect any information from anyone, including children.

---

## 7. Permissions Requested

The App requests the following iOS permissions:

| Permission | Why | When |
|---|---|---|
| **Location — While Using** | To track distance and route during a work shift | Only while a shift is active |
| **Location — Always** | To keep tracking a shift when the screen is locked or another app is open, and — only if you turn on Auto-track personal miles — to detect personal drives in the background | During an active shift; for personal trips only if you opt in |
| **Motion & Fitness** | To detect when you are driving, so the App can log personal trips automatically | Only if you turn on Auto-track personal miles in Settings (off by default) |
| **Notifications** | To remind you if you forget to end a shift, to surface the Live Activity counter, to nudge you on arrival at a saved station, and to let you know when personal-trip tracking is running | Optional. The App functions without notifications enabled |

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

Earnly Driver uses Apple's own frameworks (CoreLocation, CoreMotion, MapKit, SwiftData, ActivityKit, WidgetKit, App Intents, UserNotifications, and CLGeocoder for the optional reverse geocoding feature). Apple's privacy practices for these frameworks are described in Apple's own privacy policy at <https://www.apple.com/legal/privacy/>. When you use the optional reverse geocoding feature, your shift or trip coordinates are sent to Apple's geocoding service and are subject to Apple's privacy practices, not the Developer's.

If you choose to use the App's Siri shortcuts, your spoken commands are processed by Apple's Siri and are subject to Apple's privacy practices. The App itself only receives the resulting "start shift" or "end shift" action.

---

## 10. Changes to This Policy

If we update this Privacy Policy in a future version of the App, the updated policy will be published at this URL and the "Last updated" date at the top will change. Material changes will be highlighted in the App's release notes.

---

## 11. Contact

If you have questions about this Privacy Policy or about how the App handles data, contact the Developer at:

**Email:** earnlydriver@gmail.com

We typically respond within 2 business days.

---

*Earnly Driver is an independent app and is not affiliated with, endorsed by, or sponsored by Amazon.com, Inc., Uber Technologies, Inc., Lyft, Inc., DoorDash, Inc., Maplebear Inc. (Instacart), Walmart Inc. (Spark Driver), or Just Eat Takeaway.com (GrubHub), or any of their subsidiaries. All platform and trademark names are the property of their respective owners.*
