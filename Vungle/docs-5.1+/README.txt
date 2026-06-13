# Alpha Ads - Vungle Integration

**Engine:** UE4 4.27 | **Platform:** Android | **Version:** 1.0 | **Author:** Alpha XP

---

## Overview

Alpha Ads - Vungle Integration exposes rewarded video, banner, interstitial ads to UE4 Blueprint projects on Android. No C++ required.

## Features

- Banner, Interstitial, and Rewarded Video ad formats
- Full Blueprint API — no C++ required
- Event delegates for all ad lifecycle callbacks (Loaded, Failed, Shown, Clicked, Closed, Rewarded)
- Game Instance Subsystem access from any Blueprint
- GDPR / CCPA / COPPA consent API
- Test mode toggle for development builds
- Bundled SDK — zero external download or setup
- Android armv7 + arm64 support
- Project Settings panel for credentials (App ID, Placement Reference IDs)
- UE 5.1+ compatible

## Third-Party SDK

| Field | Value |
|---|---|
| SDK | Vungle v4.0.2 |
| Provider | Vungle Inc. (Liftoff) |
| License | Vungle Publisher SDK License |
| File | `Source/ThirdParty/VungleSDK/VungleSDK.jar` |
| Site | https://vungle.com |

> You must independently agree to the Vungle terms and set up your own account.

---

## Setup

1. Copy plugin to your project Plugins/ directory.
2. Enable in Edit > Plugins.
3. Enter credentials in Edit > Project Settings > Alpha Ads - Vungle Integration.
4. Rebuild and package Android Shipping.

---

## Example Project

A minimal demo project is included with the plugin download under `/ExampleProject`. It contains:

- A sample Level (`L_AdsDemo`) with UMG buttons for each ad format
- A demo Blueprint (`BP_AdsManager`) showing init, load, show, and event-binding flow
- Pre-configured Project Settings using Vungle test App ID / Placement Reference IDs
- Ready-to-package Android Shipping config (armv7 + arm64)

Open `ExampleProject/AdsDemo.uproject` in UE 5.1+, enable the plugin, and Launch on an Android device to verify integration.

---

## License

Integration code is subject to the Fab product page terms. Bundled SDK files have their own licenses (see ThirdPartyNotices.md).
