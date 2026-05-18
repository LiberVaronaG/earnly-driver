---
layout: default
title: Support — Earnly Driver
permalink: /support/
---

# Earnly Driver — Support

**Need help?** This page covers the most common questions. If your question isn't answered below, email **earnlydriver@gmail.com** and we'll get back to you within 2 business days.

---

## Quick start

1. **Open Earnly Driver** and grant location access when prompted. Choose **Allow While Using App** first; when you start your first shift, iOS will then ask you to upgrade to **Allow Always** so the app can track you in the background.
2. **Tap Start Shift** when your delivery or rideshare block begins. If you have more than one platform enabled, the app asks which one you're driving for. It starts a timer, tracks your route, and shows a Live Activity on your Lock Screen.
3. **Drive your block** as normal. You don't need to keep the app open — it works in the background.
4. **Tap End Shift** when you finish. Enter what you got paid; the app calculates your earnings per hour, cost per mile, and net profit.
5. **Review your stats** on the Home and History tabs. Export to CSV or a tax-year PDF any time from the Export tab.

---

## Frequently Asked Questions

### Which platforms does Earnly Driver support?
Amazon Flex, Uber, Lyft, DoorDash, Instacart, Spark Driver, and GrubHub. Enable the ones you drive for in **Settings → Platforms**. When you start a shift, the app asks which platform it's for. You can also stack platforms on a single drive — see below.

### Does Earnly Driver connect to those platforms automatically?
No. Earnly Driver is an independent app and does not connect to any delivery or rideshare service. You start and end shifts manually by tapping the buttons in the app. These platforms do not provide a public API for third-party shift tracking.

### Does the app share my data with Amazon, Uber, or anyone else?
No. Earnly Driver does not communicate with any platform or any server. All your data stays on your iPhone. See our [Privacy Policy](/privacy/) for full details.

### Why does it ask for "Always" location access?
So the app can keep tracking your route after you put your phone in your pocket, lock the screen, or switch to the platform's app while driving. Location is only used **while a shift is active** — never before you tap Start Shift, never after you tap End Shift. You can verify this in **Settings → Privacy & Security → Location Services → Earnly Driver**.

### What is "Auto-track personal miles"?
It's an optional feature in **Settings → Tracking**, **off by default**. When you turn it on, the app uses motion detection to log your personal (non-work) drives in the background, so you have a record of them. Personal miles are kept completely separate — they never count toward your earnings, your work miles, or your IRS export. Work miles are always started by hand. This feature uses extra battery, and nothing leaves your iPhone.

### A personal drive wasn't logged — why?
A few reasons a personal trip may not appear:
- "Auto-track personal miles" is off, or the app doesn't have **Always** location and Motion & Fitness permission.
- The drive was under half a mile — very short drives are discarded as GPS noise.
- A work shift was active — personal tracking always stands down during a work shift.
- iOS didn't detect the start of the drive. Motion detection reacts to changes; if you were already moving when conditions changed, the app catches up as soon as it can.

### Can I turn a personal trip into a work shift?
Yes. Open the personal trip in the History tab and tap **Reclassify as work shift**. You pick the platform, trim the work window by time, and enter what you got paid. The work portion becomes a logged shift; the rest stays personal. The app never decides this for you — reclassifying is always your choice.

### Can I track more than one platform on the same drive?
Yes. If you stacked apps — say Uber and DoorDash on the same trip — start the shift on your main platform, then add the other platform's pay in the shift summary or by editing the shift later. Miles are counted once (which is IRS-correct); the pay is summed across platforms.

### Can I edit a shift after I end it?
Yes. Open any shift in the History tab and tap Edit. You can adjust earnings, tips, mileage, and notes. The shift keeps a record of the edit and the reason, for your own audit trail.

### What happens if I forget to tap End Shift?
The app keeps tracking until you remember, and reminds you with a notification. When you reopen it, tap End Shift — then edit the end time on the shift's detail screen to the correct value.

### What happens if my phone dies mid-shift?
Location points are saved continuously. When you reopen the app it detects the unfinished shift and asks you to confirm the end time — the last recorded location time, a time you enter, or keep tracking.

### Can I export my data for taxes?
Yes, from the **Export** tab:
- **CSV** — every shift with its date, times, mileage, IRS rate, estimated deduction, platform, and pay. Opens in Excel, Numbers, Google Sheets, and most tax software.
- **Tax-year PDF** — a one-page summary for a chosen year: total business miles, standard-mileage deduction, gross income by platform, a self-employment tax estimate, and a monthly chart.

Share either via email, save to Files, or AirDrop to your Mac.

### Does the app estimate my taxes?
It estimates your **IRS standard-mileage deduction** and your **self-employment tax** to set aside, based on the shifts you logged. It does **not** file taxes, calculate income tax, or provide tax advice. Consult a tax professional for your specific situation.

### What does the Expenses screen do?
The IRS lets you deduct your vehicle cost two ways: the **standard mileage** method (a fixed rate per business mile) or the **actual expense** method (your real operating costs — gas, oil changes, repairs, insurance, registration). You generally use one or the other per vehicle.

In **Settings → Expenses** you log your real operating costs — each with a date, an amount, a category, and a business-use percentage (the share of that cost that was for work, since a car you also drive personally isn't 100% business). The screen shows both methods side by side for the current tax year, so you can see which one would give the bigger deduction.

It deliberately excludes depreciation and lease costs — those are the highest-risk pieces and need a tax professional. The comparison covers operating expenses only and is not tax advice.

### How does the app estimate my fuel cost per shift?
This is separate from the Expenses screen. Set your vehicle and fuel price in **Settings → My vehicle**. The app then estimates each shift's fuel cost from your miles, your vehicle's efficiency, and the fuel price, and subtracts it to show your net earnings per shift.

### What are "stations"?
A station is a location you save — for example a delivery warehouse — in **Settings → My stations**. When you arrive at a saved station, the app can send a reminder to start your shift. It never starts a shift automatically; tapping Start Shift is always your action.

### Can I use Siri?
Yes. You can say "Start shift in Earnly Driver" or "End shift in Earnly Driver." For the most reliable results, record your own phrase in the Shortcuts app — see **Settings → Accessibility** for guidance.

### Can I see my route on a map?
Yes. Open any completed shift or personal trip in the History tab to see the full route drawn on a map, with start and end points.

### Will my data sync between iPhones?
Not in the current version. Your data is stored locally on the iPhone where you record it. If you switch iPhones, restore from an iCloud or encrypted local backup of your old phone — the app's data is included in standard iPhone backups. We're evaluating optional iCloud sync for a future version.

### What iPhones does it support?
iPhone running **iOS 18.5 or later** — iPhone XS / XR (2018) and newer.

### Is there an Android version?
Not currently. Earnly Driver is iOS-only.

### Will it drain my battery?
Location tracking uses the most efficient iOS APIs available — expect roughly 4–6% battery drain during a 4-hour active shift on a modern iPhone. "Auto-track personal miles," if you turn it on, uses some additional background battery. If you see significantly more, email us with your iPhone model.

### The app crashed / shows wrong data / froze
Email **earnlydriver@gmail.com** with:
- iPhone model and iOS version (Settings → General → About)
- What you were doing when it happened
- Approximate date and time of the issue

If data looks wrong but the app otherwise works, try force-closing and reopening it first.

### How do I delete all my data?
Delete the app from your iPhone (long-press the icon → Remove App → Delete App). All data is removed with the app. There are no servers to clear; nothing is retained anywhere.

---

## Contact

**Email:** earnlydriver@gmail.com
**Response time:** within 2 business days (often faster)
**Language:** English or Spanish — both are fine

For privacy-specific questions, see the [Privacy Policy](/privacy/).

---

*Earnly Driver is an independent app and is not affiliated with, endorsed by, or sponsored by Amazon.com, Inc., Uber Technologies, Inc., Lyft, Inc., DoorDash, Inc., Maplebear Inc. (Instacart), Walmart Inc. (Spark Driver), or Just Eat Takeaway.com (GrubHub), or any of their subsidiaries. All platform and trademark names are the property of their respective owners.*
