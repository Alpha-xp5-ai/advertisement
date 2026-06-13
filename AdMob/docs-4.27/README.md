# Alpha Ads - AdMob Integration

**Engine:** UE4 4.27 | **Platform:** Android | **Version:** 1.0 | **Author:** Alpha XP

**Documentation:** https://alpha-xp5-ai.github.io/advertisement/AdMob/

---

## Overview

Alpha Ads - AdMob Integration exposes rewarded video, banner, interstitial, native, and app open ads to UE4 Blueprint projects on Android and iOS. It acts as an integration bridge to the Google Mobile Ads SDK. No C++ required.

## Features

- Full Blueprint API
- Event delegates for all ad lifecycle callbacks
- Game Instance Subsystem access
- Android armv7 + arm64 support

## Third-Party SDK

| Field | Value |
|---|---|
| SDK | Google Mobile Ads SDK |
| Provider | Google LLC |
| Android | `com.google.android.gms:play-services-ads:20.6.0` (via Gradle) |
| iOS | `Source/ThirdParty/AdMobSDK/iOS/GoogleMobileAds.framework.zip` |
| License | Google APIs Terms of Service |
| Site | https://developers.google.com/admob |

> You must independently agree to the Google AdMob terms and set up your own AdMob account, App ID, and ad unit IDs.

---

## Setup

1. Copy plugin to your project Plugins/ directory.
2. Enable in Edit > Plugins.
3. Enter your App ID and ad unit IDs in Edit > Project Settings > Alpha Ads - AdMob Integration.
4. Rebuild and package Android Shipping.

---

## License

Integration code is subject to the Fab product page terms. Bundled SDK files have their own licenses (see ThirdPartyNotices.md).
