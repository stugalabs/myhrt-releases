# MyHRT for Android: direct download

MyHRT is a private hormone replacement therapy (HRT) tracker. All data stays on your device, encrypted. The app has no internet access, no account and no tracking.

This repository hosts the official APK for people who prefer not to use Google Play. It contains no source code.

## Download

Get the latest version here: [Releases](https://github.com/stugalabs/myhrt-releases/releases/latest)

- Same app and same signature as the Google Play version, so your data carries over if you switch.
- The app can't update itself. Check Releases for new versions, or add this repository to Obtainium.
- Android will ask you to allow installs from your browser or file manager. That's normal for apps installed outside the Play Store.
- To check a download: each release page lists the APK's SHA-256, and the app's signing certificate has the SHA-256 fingerprint `e4b9d88edcc12904fa9680d59508ddaf42e3af80bebe2f168d44702d1a6bb1f4`. Run `apksigner verify --print-certs MyHRT-1.2.0.apk` (from the Android SDK build tools) and compare. A file with a different certificate is not the build we publish.

## Support the project

MyHRT is free, with no ads and no tracking. If you'd like to help, there are several ways, and most of them cost nothing: [myhrt.health/support](https://myhrt.health/support/)

## Important

- For adults (18+) only.
- MyHRT is a tracking tool, not a medical device, and gives no medical advice. Use it to track treatment prescribed by a healthcare professional.
- [Website](https://myhrt.health) · [Terms](https://myhrt.health/terms/) · [Privacy policy](https://myhrt.health/privacy/) · [Contact](https://myhrt.health/contact/)

© Stuga Labs. All rights reserved.
