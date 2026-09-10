# NotifyDot

**Never miss what matters. Without being interrupted.**

NotifyDot puts a small red dot over other apps when the apps you choose have
notifications you haven't checked yet. The dot stays there until you check
them. No sound. No vibration. No banners.

![NotifyDot demo](notifydot-demo.gif)

## Why

There are a few apps whose messages you never want to miss — but you also
don't want your phone to buzz, ring, or pop up banners for them. Maybe it's
WeChat during work hours. Maybe it's a messaging app at night.

The problem: status-bar notification icons are easy to miss. They get
squeezed out by a crowded status bar, disappear in full-screen apps, or
pile up unnoticed while you're away from your phone.

NotifyDot gives those few apps a persistent, impossible-to-miss indicator:
a red dot that floats on top of everything — your home screen, Chrome,
other apps — until you open the app and check. No noise. No interruption.
Just a quiet "hey, something's waiting" that doesn't go away on its own.

Pick the apps you never want to miss → a red dot appears when they have
pending notifications → it disappears when you open the app.

## Status: early beta

This app is currently distributed outside Google Play as an early beta.
It is free, has no ads, no account, and no analytics.

## Permissions — and why each one is needed

- **Notification access** — to detect pending notifications from the apps you
  select. Notification *contents* (title, text, sender) are never read,
  stored, or transmitted anywhere. Only "this app has something unchecked"
  is used.
- On newer Android versions, the notification access page for NotifyDot may
  show four toggles (Real-time, Conversations, Notifications, Silent).
  NotifyDot watches all notification types from your selected apps — keep
  the defaults (all on) so nothing slips through. Turning one off means
  you'll miss that kind of notification.
- **Display over other apps** — to draw the red dot on top of other apps.
- **Ignore battery optimizations** — so the dot keeps working reliably in
  the background.

## Install

Download the APK from
[Releases](../../releases),
install it, and complete the 3-step setup inside the app. All three grants
are required.

## Privacy

NotifyDot works fully offline. It does not collect, upload, or share any
data. Your notification contents never leave your phone — the app never
even reads them.

## Feedback

Found a bug or have a feature request? Open an
[issue](../../issues) — screenshots and your phone model / Android version
help a lot.

## License

© 2026 Real Good Design. All rights reserved. The APK is provided for personal
use; redistribution or reverse engineering is not permitted.
