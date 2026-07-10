# Festi — Privacy Policy

_Last updated: July 10, 2026_

Festi ("the app", "we") is operated by **Dylan Hackenbrook**. This policy explains
what the app collects, how it's used, and how to delete it. Questions: **dhackenbrook@gmail.com**.

## The short version
- We don't ask for your email, phone number, or payment details.
- We don't show ads and we don't track you across other apps or websites.
- **"Share my location" is on by default** so friends can find you during the festival —
  you're asked on first launch whether to keep it on, you can turn it off anytime in the
  app, and only your accepted friends can ever see it.
- You can delete your account and all of its data from inside the app at any time.

## What we collect
You're signed in automatically with an **anonymous account** (a random ID) the first time
you open the app — no personal details required. Tied to that account, we store only what
the features need:

- **Anonymous account ID and friend code** — to identify your data and let friends add you.
- **Display name** — optional, only if you set one.
- **Favorite artists** — the artists you star, to build your schedule.
- **Friend connections** — friend requests you send/accept.
- **Precise location** — **"Share my location" is on by default** (you're asked on first
  launch whether to keep it on, and can turn it off anytime), and location is only used
  **during the festival's run.** Used to show your position, current stage, and — while
  you're walking — your **direction of travel and speed** to your accepted friends (their
  map can also show the **GPS accuracy radius** of your pin, so it's honest about how
  precise it is), and to compute festival "badges." Collected while sharing is on,
  **including in the background** so friends keep seeing your live position even when the
  app isn't open. Controls: turn sharing off entirely, **hide your location from individual
  friends**, or **share only when within 1 km of a venue** (this "near only" option is
  **on by default** for new installs). Turning sharing off stops collection and deletes your
  shared position; shared positions also **auto-expire after ~10 hours**. On Android a
  persistent notification shows while it's active.
- **"Meet Here" pins** — if you drop a meetup pin, the location you choose and its label are
  shared with the friends you share location with, and **auto-expire after 1 hour**.
- **"Find nearby" Bluetooth signal** — while the app is open with sharing on, your phone
  broadcasts a **random Bluetooth identifier that changes every ~15 minutes** so a friend
  standing nearby can follow a hot/cold signal-strength meter to you. The identifier contains
  no personal data, and only your accepted friends can link it to you (the same access rules
  as your location). Bystanders can't identify or follow you across changes. It stops when
  you close the app or turn sharing off.
- **"Bump to connect" location** — if you tap Bump to add a friend in person, we briefly use
  your current GPS position, plus the moment your phones physically tap (detected by the
  accelerometer — only that timestamp is sent, never your motion data), to match you with
  another nearby person who is also bumping. Both are used only to find that match and are
  discarded shortly after.
- **Push notification token** — if you turn on "alert when a friend joins my stage," we store
  your device's push token so we can send that notification (e.g. "Alex is at Mainstage").
- **Derived activity stats** — computed from your location only while sharing is on: total time
  at the festival, time at individual stages/venues, distance walked, and how long and on which
  nights you stay into the late-night/early-morning hours. Used to award festival "badges" and
  "achievements." These are visible to your accepted friends (badges are a friendly competition);
  you can stop them accruing by turning sharing off.
- **Safety reports & blocks** — if you block or report another user, we store that so we can keep
  you apart and review the report. Report reasons you submit are visible only to the app operator.

Set reminders are scheduled **on your device**; no personal data leaves the phone for them.
Your **battery level** is also read **on your device only**, to automatically lower GPS
accuracy when your battery runs low — it is never stored or sent anywhere.

## How we use it
Only to provide the app's features (schedule, map, friends, meetups, reminders). We do
**not** sell your data or use it for advertising.

## Who it's shared with
- **Other users:** your **accepted friends** can see your display name, your activity
  stats/badges, and — while you have sharing on — your location and meetup pin. Someone you've
  sent or received a friend request from can see your display name so they can recognize you;
  **no one else can read your profile.** Access is enforced server-side (row-level security).
- **Service providers (processors):**
  - **Supabase** — hosts our database and authentication.
  - **Mapbox** — provides the maps; receives map-tile requests to render the map.
  - **Expo** — delivers push notifications to your device.
  - **Spotify** — opening an artist launches a Spotify search; that's an external service
    governed by Spotify's own privacy policy.

## Retention & deletion
We keep your data until you delete it. To delete everything, in the app go to
**Settings → Account & data → Delete account & data**. This permanently removes your
profile, favorites, friends, shared location, meetup pin, activity stats/badges, and any
blocks or reports you created. (A fresh, empty anonymous account is created so you can keep
using the app.)

## Location, specifically
Location is **precise**, **on by default**, and **revocable** at any time — toggle "Share my
location" off in the app, or revoke the permission in your device settings. On first launch
the app asks whether to keep sharing on **before** any location permission is requested, and
records your answer. New installs also default to sharing **only within 1 km of a venue**,
so you aren't broadcasting from home or your hotel unless you choose to.

## Children
Festi isn't directed to children under **16**. We don't knowingly collect data from them.

## Changes
We may update this policy; material changes will be noted here with a new date.

## Contact
**Dylan Hackenbrook** — **dhackenbrook@gmail.com**
