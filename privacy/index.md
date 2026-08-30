---
title: Privacy Policy
---

# Privacy Policy — Sun Path & Shadow

**Last updated: 30 August 2026**

## The short version

The sun's position is closed-form geometry — given a coordinate and a moment,
the answer can be computed exactly, on your device, with no server and no data
feed. So the app's core function sends nothing anywhere.

There is no account, no login, no analytics, no advertising and no crash
reporting. I do not know which screens you open or how often you open the app.

Two things do reach other companies, and both are named in full below:

- **Every time the app starts**, it checks with **RevenueCat** whether this
  device holds a purchase. That happens for everyone, including people who have
  never bought anything, because the app has to know what to unlock before it
  draws its first screen.
- **When you open the Map screen**, the map tiles come from **Apple Maps** or
  **Google Maps**, and the area you are looking at is part of that request.

Nothing else leaves the device. Your location is not sent to me, the shadow
calculations run locally, and the camera view is never captured.

---

## Who is responsible

Sun Path & Shadow is made by **Anıl Sancar**, an independent developer.

Contact: **anilsancarr@gmail.com**

If you have a question about this policy, or a request about your data, email
that address. It is read by one person — me.

---

## What the app uses on your device

Each of these is asked for when it is first needed, with the reason on screen,
and the app keeps working if you say no.

### Location

Used to compute where the sun is from where you are standing. It is requested
only while the app is open, at balanced accuracy — the sun's apparent position
changes by well under a tenth of a degree across a city, so there is no reason
to ask for more precision. On Android the app declares both coarse and fine
location, but only ever requests balanced accuracy at runtime.

**I never receive your location, and the sun and shadow maths never sends it
anywhere.** There is no reverse geocoding: the app does not send your position
to a naming service to find out which street or town you are in, which is why it
labels your position simply as your current location. That was deliberate.

The one exception is the Map screen, described below.

### The Map screen

Maps are drawn by **Apple Maps** on iOS and **Google Maps** on Android. Like any
map, it works by requesting the tiles for the area being displayed, and when the
map opens on your position, that area is derived from it. Those requests go to
Apple or Google directly and are governed by their privacy policies, not mine —
I never see them.

If you would rather no coordinate of yours reached a mapping company, the rest
of the app works without ever opening that screen.

### Camera

Used only to show the live view behind the sun-path overlay in the sky screen.
**No photo or video is captured, saved, or transmitted.** The frames are drawn
to the screen and discarded, and nothing about them is analysed or stored.

### Motion and compass

Used to work out which way your phone is pointing so the sun can be drawn in the
right place over the camera view. Read on the device, used immediately, never
stored and never sent.

---

## What is stored on your device

- Your settings — units, time format, theme.
- The places you have saved, and the place currently selected.
- Whether you have completed the introduction.

These are stored in the device's own secure storage (the iOS Keychain, or the
Android equivalent). They stay on the device, they are not readable by other
apps, and **deleting the app deletes them**. There is no backup to any server of
mine, because I do not run one.

---

## Purchases, and why the app contacts RevenueCat at every launch

Payment itself is handled entirely by **Apple** or **Google**, depending on
where you installed the app. I never see your card, your billing address, or
your name.

To know whether a purchase is valid — and to restore it if you change phones —
the app uses **RevenueCat**, a subscription infrastructure provider.

**This check runs at every launch, not only when you buy.** The app has to know
whether to unlock the paid screens before it renders, and whether a free trial
is still available to you, and only RevenueCat can answer that. So a person who
installs the app and never spends a penny still causes these requests.

What RevenueCat receives:

- an **anonymous identifier** that the RevenueCat SDK generates on your device.
  The app does not attach your email, your name or any profile to it, and does
  not call any of RevenueCat's user-identification features.
- **your app and device context**: app version, platform and operating system
  version, the SDK's own version, and your language and store country.
- **purchase state** — which products exist for you, what you are entitled to,
  and, when you buy or restore, the **receipt** issued by Apple or Google.
- **technical information that accompanies any internet request**, including
  your IP address, from which an approximate country can be derived.

**No location, no camera data and no sensor data is ever included.**

RevenueCat processes this to validate purchases and keep them restorable. Their
privacy policy is at
[revenuecat.com/privacy](https://www.revenuecat.com/privacy/).

### Third parties and your data

Where this app shares data with a third party — RevenueCat for purchases, Apple
or Google for maps and for payment — I require that they provide the same or
equal protection of your data as this policy states, and I do not permit them to
use it for anything beyond providing that service.

---

## When you tap a link

Some taps leave the app: the Terms and Privacy links open this website, which is
hosted on **GitHub Pages**; "Manage subscription" opens the App Store or Play
Store; "Contact" opens your own mail app with a message addressed to me,
pre-filled with nothing but your platform name so I know what device you are
describing. Nothing is sent until you press send.

The app also asks once, in-app, whether you are enjoying it. If you say yes it
opens your store's own rating sheet; if you say no it opens that same mail
draft. Your answer is not recorded or transmitted anywhere.

---

## What the app does not do

- **No advertising.** There is no ad SDK in the app at all.
- **No analytics.** No usage statistics are collected, by me or anyone else.
- **No crash reporting SDK.**
- **No tracking.** Nothing is linked with data from other companies for targeted
  advertising and nothing is shared with a data broker. The app collects no
  advertising identifier and never shows the "Ask App not to Track" prompt,
  because there is nothing it would apply to.
- **No profile.** There is no account, so there is no record anywhere that ties
  this app to you as a person.

---

## Children

The app is not directed at children and collects nothing from them. It has no
social features, no messaging, no user-generated content and no advertising.

---

## How long anything is kept

Data on your device stays until you delete it in the app or delete the app.

Purchase records held by RevenueCat and by Apple or Google are kept according to
their own policies and their own legal obligations — I cannot delete an Apple or
Google purchase record, because it is a financial record.

Map requests are Apple's or Google's, and are retained under their policies. I
have no access to them and cannot delete them on your behalf; those companies'
own privacy tools are the route for that.

---

## Your rights

Depending on where you live, you may have rights under the GDPR (Europe), the
KVKK (Türkiye), the CCPA/CPRA (California) or a comparable law — to know what is
held about you, to get a copy, to correct it, to have it deleted, and to object
to processing.

In practice, almost everything this app touches is on your own device and under
your own control, and can be erased by deleting the app. For anything held in
connection with a purchase, email **anilsancarr@gmail.com** with the store
receipt or transaction identifier and I will act on it. Without something that
identifies the purchase there is genuinely no way to find a record, because
there is no account to look you up by.

If you believe your rights have been breached, you can complain to your national
data protection authority — in Türkiye, the Kişisel Verileri Koruma Kurumu.

---

## Changes to this policy

If this changes, the date at the top changes with it, and the current version
always lives at this address. Material changes will be described in the app's
release notes rather than made silently.

---

## Contact

**anilsancarr@gmail.com**
