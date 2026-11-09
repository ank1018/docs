---
title: Aaroh privacy notice
---

# Aaroh privacy notice

**Version 0.2 · Effective 9 November 2026 · For Aaroh test builds (internal and closed testing on Google Play)**

Aaroh is a food diary and packaged-food guide for adults in India. It is made by Ankur Singh, an individual
developer in India ("we", "us"). This notice explains what data Aaroh uses, where it goes, why, how long
it is kept, and what you can do about it. Some features described here (meal reminders, My food and your shelf) are part of test build 0.2 and later.

## 1. The short version

- **Aaroh has no accounts and no Aaroh server.** Your profile, targets and food diary are stored only on your phone.
  We can't see them.
- **A few things do leave your phone:**
  - When you scan or type a barcode, the barcode goes to **Open Food Facts** to find the product.
  - Google's **ML Kit**, which reads barcodes and labels on your phone, sends Google basic technical data. It does
    not send your photos.
  - **Only if you switch them on:** crash reports (with a short note each time you use the app) go to **Sentry**,
    and usage statistics go to **PostHog**. Both are stored in the EU. Both are off until you choose.
- **No AI, no ads, no selling data.** Label photos are read on your phone. We do not sell your data or show ads.
- **Meal reminders**, if you turn them on, are set and shown by your phone. No server sends them.
- **You can delete everything** on your phone in Profile → Data and privacy → Delete all my data, or by
  uninstalling Aaroh.
- **Aaroh is for adults 18 and over.**

## 2. Data kept only on your phone

| What | Why |
|---|---|
| Name you enter, birth year (not your full date of birth), sex (optional), height, weight, activity level, diet, allergies and food restrictions, goal | To estimate your daily targets and to flag foods that may not suit your diet or allergies |
| Targets, food diary, notes, water log, recipes, saved meals, foods you added, favourites | To keep your diary |
| Copies of product details and product photos you have looked up | So products open quickly and work offline |
| **Your shelf:** the products and additives you have opened in Aaroh (name, brand, barcode, and when you first and last opened each one), and which foods you have looked at | To show your shelf in My food. Aaroh doesn't count how often you open something |
| **Reminders:** the meal times you chose, quiet hours, and a record of the last 30 days of reminders (when each was due and whether you opened it) | To send reminders at your times, skip meals you've already logged, and pause reminders that aren't being opened |
| **App activity on this phone:** how many times you've opened Aaroh, which milestones you've reached and when, and the short "small win" lines shown in the last 7 days | So a milestone shows only once, and the same line isn't repeated. This never leaves your phone |
| Photos you take of a nutrition label | To read the label **on your phone**, using Google ML Kit text recognition. The photo is never uploaded. It stays in Aaroh's temporary storage until you delete your data or uninstall Aaroh, unless Android clears it sooner. |
| Your settings, including reminders you set | To run the app. Reminders are scheduled on your phone. |

This data is not sent to us, and we can't recover it for you. We have set Aaroh so that Android doesn't copy its
data to your Google account or move it to a new phone. If you change phones, your diary stays on the old one.

## 2a. Phone permissions

| Permission | Why Aaroh asks for it |
|---|---|
| Camera | To scan barcodes and photograph nutrition labels. Asked for the first time you scan. |
| Notifications | To show meal reminders. Asked for only after you tap **Remind me** in Aaroh. If you say no, nothing else changes. |
| Run at start-up | So reminders you set are scheduled again after your phone restarts. |
| Prevent the phone from sleeping, and vibrate | So a reminder can be shown and can vibrate when it's due. |
| Internet and network status | To look up barcodes, and to tell you when you're offline. |

Aaroh doesn't ask for exact alarms, access to Do Not Disturb, your location, contacts or files.

## 3. Data that leaves your phone

### 3.1 Looking up a barcode (Open Food Facts)

When you scan or type a barcode, Aaroh sends **the barcode** to Open Food Facts, a non-profit association in France
that runs an open product database. Product pictures in Aaroh are also loaded from Open Food Facts.

Like any internet request, this shows Open Food Facts your phone's **IP address** and a label saying the request
came from Aaroh. It does not include your name, profile or diary. Open Food Facts is an independent organisation,
not our service provider. Its privacy policy says it keeps website visit logs, including IP addresses, for up to
three years: <https://world.openfoodfacts.org/privacy>

If you'd rather not send anything, you can still search Aaroh's built-in Indian foods and add foods by hand
without scanning.

### 3.2 Google ML Kit diagnostics

Aaroh uses Google's ML Kit on your phone to read barcodes and nutrition labels. ML Kit sends Google technical data
so Google can monitor and improve ML Kit: device model, Android version, app version, a random installation
identifier, performance timings and error codes. According to Google's ML Kit data disclosure, it does not send the
images or the text it reads. This happens even if analytics are off, because it is built into ML Kit.

### 3.3 Crash reports (optional, off until you switch them on)

If you switch on **Crash reports**, Aaroh sends **Sentry** (Functional Software, Inc.) a report when the app crashes
or freezes. A report contains the error and where in the code it happened, the app version, device model, Android
version, free memory and a random installation identifier.

It never contains your name, food names, searches, barcodes, nutrition values, notes, body measurements, allergies,
screenshots or what was on your screen. Reports are stored in the EU (Frankfurt). We have set Sentry not to store IP
addresses. Reports are deleted after 30 days.

While crash reports are on, Aaroh also sends Sentry a short note each time you use the app: when the use started and
ended, whether it ended in a crash, the app version and the same random identifier. We use these notes only to see
how often Aaroh crashes. They contain nothing about your food, health or what you did in the app. We're checking with Sentry how long it keeps these notes, and will update this notice.

### 3.4 Usage statistics (optional, off until you switch them on)

If you switch on **Usage statistics**, Aaroh sends **PostHog** (PostHog Inc.) records of which features are used,
such as "app opened", "food logged", "barcode scanned: found or not found", "reminder set for lunch, midday",
"reminder opened", "milestone reached: 10 products checked" and "shelf opened". Each record has the time, the app
version, basic device details and a random identifier for this installation.

It never contains your name, food names, searches, barcodes, product names, nutrition values, portions, notes, body
measurements, age, sex, diet, allergies, goals, your exact reminder times, or whether you have hidden numbers. Records are stored in the EU (Frankfurt). PostHog does not work out your
location, and we have set it to discard IP addresses. Records are kept for up to 12 months, then deleted.

We use these statistics to see whether Aaroh is useful (for example, how many people come back after a week) and
to find what to fix.

### 3.5 When you choose to share

- **Export:** "Export my data" creates a file and opens Android's share sheet. The file has your profile, targets,
  diary, water log, recipes, saved meals, foods you added, favourites, recently viewed foods, your shelf and your
  settings. It doesn't yet include your reminder times or milestone records; you can see your reminder times in Settings. It goes only where you send it. The file isn't encrypted, so share it only with people and apps you trust.
- **Report a problem:** this opens your own email app with a message to us. We receive what you send, including your
  email address. We use it only to reply and fix the problem, and we delete it within 12 months.

### 3.6 Google Play

Google Play handles installing and updating Aaroh, and testing sign-up. Google processes that under its own privacy
policy. If you have allowed Android to share usage and diagnostics data, Google also shows us anonymous crash and
performance figures in Play Console. We can't see who they come from.

## 4. Who receives data

| Recipient | What | Role | Where |
|---|---|---|---|
| Open Food Facts | Barcodes, IP address | Independent database | France |
| Google (ML Kit) | Technical diagnostics (§3.2) | Collects for its own diagnostics | Google's servers, may be outside India |
| Sentry | Crash reports, only if switched on | Our service provider | EU (Germany) |
| PostHog | Usage statistics, only if switched on | Our service provider | EU (Germany) |
| Authorities | Only when Indian law requires it | — | India |

Sentry and PostHog store data outside India, in the EU. Indian law currently allows this. We do not sell personal
data or share it for advertising.

## 5. How long data is kept

| Data | How long |
|---|---|
| Everything on your phone | Until you delete it in the app or uninstall Aaroh, except: |
| Reminder record (due and opened) | 30 days. Older records are deleted on your phone the next time Aaroh updates your reminders |
| "Small win" lines shown | 7 days, then deleted on your phone |
| Your shelf | Until you clear it (My food › Your shelf › Clear shelf history) or delete all your data |
| Crash reports | 30 days for error reports; still being confirmed with Sentry for the notes about each use (§3.3) |
| Usage statistics | Up to 12 months |
| Emails you send us | Up to 12 months after the conversation ends |
| Open Food Facts logs | Set by Open Food Facts (see §3.1) |

## 6. Your choices and rights

- **Change your mind at any time.** Switch crash reports or usage statistics off in Settings, or in Profile → Data
  and privacy. Aaroh then stops sending them and starts a new random identifier, so earlier records can't be
  linked to you. Records already sent are deleted on the schedule in §5. They aren't linked to your name, so we
  can't find them for you individually.
- **See or copy your data:** Profile → Data and privacy → Export my data.
- **Correct your data:** edit it in the app.
- **Reminders, milestones and small wins:** turn any of them off in Settings › Reminders and highlights. You can also
  turn notifications off for Aaroh in your phone's settings.
- **Clear your shelf:** My food › Your shelf › Clear shelf history. This clears the list of products, foods and
  additives you've looked at. Copies of the products themselves stay so your diary and offline pages keep working;
  to remove those too, delete all your data (§12).
- **Delete your data:** see §12.
- **Ask or complain:** write to the Grievance Officer (§9). India's Digital Personal Data Protection Act 2023 gives
  you rights to information, correction, erasure, grievance redressal and to nominate someone. We will answer such
  requests as described here, even before all of the Act's rules take effect. If you're not satisfied, you can also
  complain to the Data Protection Board of India once it accepts complaints.

## 7. Security

- All connections Aaroh makes use encryption (HTTPS).
- Your data stays in Aaroh's private storage on your phone. Other apps can't read it, and Android doesn't back it up
  or move it to another phone.
- Anyone who can unlock your phone can open Aaroh. Use a screen lock.
- If a breach affects personal data we hold, we will tell the people affected and the authorities, as the law
  requires.

## 8. Children

Aaroh is made for adults aged 18 and over. Aaroh doesn't ask your age before you use it, and has no server where it
could keep data about children. If the birth year in your profile shows you're under 18, Aaroh doesn't calculate
targets, and crash reports and usage statistics stay off. If your age isn't in your profile, you need to confirm
you're 18 or older before you can turn them on. Your diary stays on your phone either way. If you think a child is
using Aaroh, tell us.

## 9. Contact and Grievance Officer

Ankur Singh, Grievance Officer, Aaroh, India. Email: [writetoankurs@gmail.com](mailto:writetoankurs@gmail.com).

We acknowledge your message within 7 days and resolve it within 30 days.

## 10. Health information

Aaroh is a general wellness tool. It is not medical advice and not a medical device. Allergen checks can miss
ingredients: always read the pack if you have an allergy.

## 11. Changes

This is version 0.2, for test builds. If we change what leaves your phone, we update this notice and tell you in
the app before the change takes effect. Earlier versions: <https://github.com/ank1018/docs/commits/main/aaroh/privacy>.

## 12. How to delete your data

Aaroh has no accounts, so there is nothing to sign in to or close.

1. **Everything on your phone:** open Aaroh → Profile → Data and privacy → **Delete all my data**, and confirm.
   This erases your profile, targets, diary, water log, recipes, saved meals, foods you added, favourites, your
   shelf, your settings, your reminders (and cancels any that are scheduled or showing), your milestone and app
   activity records, and label photos. It also erases the copies of products you looked up, and their photos,
   because together they show what you scanned. Only the food list that comes with Aaroh stays. Or uninstall Aaroh:
   Android removes all its data and its reminders.
2. **Crash reports and usage statistics:** switch them off in Settings. Earlier records aren't linked to your name.
   They are deleted after 30 days (crash reports) or 12 months (usage statistics).
3. **Emails you sent us:** write to [writetoankurs@gmail.com](mailto:writetoankurs@gmail.com) and we'll delete them within 30 days.
4. **Open Food Facts:** to ask about their logs, contact Open Food Facts (see their privacy policy).
