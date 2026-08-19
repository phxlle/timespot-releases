# TimeSpot for macOS

Downloads and the [Sparkle](https://sparkle-project.org) update feed for the
TimeSpot macOS app. The app itself lives in a private repository; this repo
only hosts release artifacts.

- **Latest download:** https://github.com/phxlle/timespot-releases/releases/latest/download/TimeSpot.dmg
- **Update feed:** `appcast.xml` on the `main` branch (consumed by the app's auto-updater)

Releases are published automatically by the app repo's CI: signed with a
Developer ID certificate, notarized by Apple, and the update feed entries are
EdDSA-signed for Sparkle.
