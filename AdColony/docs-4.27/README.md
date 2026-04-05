# Alpha Ads - AdColony Integration

**Engine:** UE4 4.27 | **Platform:** Android | **Version:** 1.0 | **Author:** Alpha XP

---

## Overview

Alpha Ads - AdColony Integration exposes rewarded video, banner, interstitial, native, app open ads to UE4 Blueprint projects on Android. No C++ required.

## Features

- Full Blueprint API
- Event delegates for all ad lifecycle callbacks
- Game Instance Subsystem access
- Android armv7 + arm64 support

## Third-Party SDK

| Field | Value |
|---|---|
| SDK | AdColony v4.8.0 |
| Provider | Digital Turbine |
| License | AdColony Publisher SDK License |
| File | `Source/ThirdParty/AdColonySDK/AdColonySDK.jar` |
| Site | https://www.adcolony.com |

> You must independently agree to the AdColony terms and set up your own account.

---

## Setup

1. Copy plugin to your project Plugins/ directory.
2. Enable in Edit > Plugins.
3. Enter credentials in Edit > Project Settings > Alpha Ads - AdColony Integration.
4. Rebuild and package Android Shipping.

---

## License

Integration code is subject to the Fab product page terms. Bundled SDK files have their own licenses (see ThirdPartyNotices.md).
