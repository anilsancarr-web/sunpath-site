---
title: Privacy Policy
---

# Privacy Policy — Sun Path & Shadow

**Last updated: 24 September 2026**

## The short version

The sun's position is closed-form geometry — given a coordinate and a moment,
the answer can be computed exactly, on your device, with no server and no data
feed. So the calculations themselves send nothing anywhere.

There is no account, no login, no advertising, and no analytics or
crash-reporting SDK. Apart from a note that the plans screen was shown,
described below, I do not know which screens you open. The launch checks
described below do let RevenueCat and Expo count how many anonymous
installations open the app, but not who you are or what you do in it.

Three things do reach other companies, and all three are named in full below:

- **Every time the app starts**, it checks with **RevenueCat** whether this
  device holds a purchase. That happens for everyone, including people who have
  never bought anything, because the app has to know what to unlock before it
  draws its first screen.
- **Every time the app starts**, it also asks **Expo**, whose update service
  delivers the app's code, whether a newer version of that code is available.
  The request carries a random identifier made on your device and
  details of the app's code — never your location, your name or your email. On
  the launch after a crash, it also carries the text of the error.
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

### Notifications

Used only for the golden-hour reminder, and only if you turn it on. The
reminders are worked out and scheduled on the device; no push token is
requested and nothing is sent to a server to deliver them.

---

## What is stored on your device

- Your settings — units, time format, theme, language, object height and the
  reminder switch.
- The places you have saved, and the place currently selected, which can be
  your own last position.
- Whether you have completed the introduction, and when the app last asked for
  a rating.

These are stored in the device's own secure storage (the iOS Keychain, or the
Android equivalent). They stay on the device and they are not readable by other
apps. **On Android, deleting the app deletes them. On iOS, the Keychain keeps
them after the app is deleted** — which is why reinstalling does not show the
introduction again — until the device is erased. There is no backup to any
server of mine, because I do not run one.

---

## Purchases, and why the app contacts RevenueCat at every launch

Payment itself is handled entirely by **Apple** or **Google**, depending on
where you installed the app. I never see your card, your billing address, or
your name.

To know whether a purchase is valid — and to restore it if you change phones —
the app uses **RevenueCat**, a subscription infrastructure provider.

**This check runs at every launch, not only when you buy.** The app has to know
whether to unlock its tools before it renders, and whether a free trial
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
- **a note each time the plans screen is shown**, saying which set of plans it
  offered. That is how I can see how many of the people who see the plans go on
  to choose one, and compare two versions of that screen. No other screen is
  reported.
- **technical information that accompanies any internet request**, including
  your IP address, from which an approximate country can be derived.

**No location, no camera data and no sensor data is ever included.**

RevenueCat processes this to validate purchases and keep them restorable. Their
privacy policy is at
[revenuecat.com/privacy](https://www.revenuecat.com/privacy/).

### Third parties and your data

Where this app shares data with a third party — RevenueCat for purchases, Expo
for app updates, Apple or Google for maps and for payment — I require that they
provide the same or equal protection of your data as this policy states, and I
do not permit them to use it for anything beyond providing that service.

---

## App updates, and why the app contacts Expo at every launch

Fixes to the app's own code can reach you without a new download from the
store, through **EAS Update**, a service run by **Expo**
(`u.expo.dev`). To find out whether one is waiting, **the app asks Expo every
time it starts**, whether or not you have bought anything. If a newer version
is available, the app downloads it from Expo and runs it.

What Expo receives:

- a **random identifier** generated on your device. It is not your
  advertising identifier, and nothing ties it to your name, your email or any
  account.
- **the app's technical context**: the platform, the app's runtime version and
  release channel, the identifiers of the code built into the app and of the
  code currently running, and those of any recent update that failed to start.
- **on the launch after a crash**, the text of the error that stopped the app
  (at most about a thousand characters), so that a broken update can be found
  and withdrawn.
- **technical information that accompanies any internet request**, including
  your IP address.

**No location, no camera data, no sensor data, no purchase details and no name
or email is ever included.**

Expo's privacy policy is at [expo.dev/privacy](https://expo.dev/privacy).

---

## When you tap a link

Some taps leave the app: the Terms and Privacy links open this website, which is
hosted on **GitHub Pages**; "Manage subscription" opens the App Store or Play
Store; "Contact" opens your own mail app with a message addressed to me,
pre-filled with nothing but the app's name as the subject. Nothing is sent
until you press send.

Now and then — at most twice a year, and only right after the app has done what
you opened it for — the app asks your store to show its own rating sheet. Apple
or Google decide whether it actually appears, and the app is never told whether
you rated it or what you wrote. It remembers, on the device only, when it last
asked.

---

## What the app does not do

- **No advertising.** There is no ad SDK in the app at all.
- **No analytics.** There is no analytics SDK. The only usage figures I see are
  counts that come with the launch checks described above: from RevenueCat, how
  many anonymous installations were active and how many saw the plans screen;
  from Expo, how many checked for and ran each update. Apple or Google may also
  share usage figures with me if you have chosen, in your device settings, to
  share analytics with app developers.
- **No crash-reporting SDK.** The one thing close to it is Expo's update check:
  on the launch after a crash it carries the text of the error, described
  above.
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

Data on your device stays until you delete it in the app. Otherwise, on Android
it goes when you delete the app; on iOS it stays until the device is erased, as
described above.

Purchase records held by RevenueCat and by Apple or Google are kept according to
their own policies and their own legal obligations — I cannot delete an Apple or
Google purchase record, because it is a financial record.

Map requests are Apple's or Google's, and are retained under their policies. I
have no access to them and cannot delete them on your behalf; those companies'
own privacy tools are the route for that.

Update checks are Expo's, and are retained under its policy.

---

## Your rights

Depending on where you live, you may have rights under the GDPR (Europe), the
KVKK (Türkiye), the CCPA/CPRA (California) or a comparable law — to know what is
held about you, to get a copy, to correct it, to have it deleted, and to object
to processing.

In practice, almost everything this app touches is on your own device and under
your own control. For anything held in
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
release notes — or, for an update delivered inside the app, on this page —
rather than made silently.

---

## Contact

**anilsancarr@gmail.com**
