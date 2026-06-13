# Alpha Ads - Unity Ads Integration

**Engine:** UE4 4.27 | **Platform:** Android | **Version:** 1.0 | **Author:** Alpha XP

---

## Overview

Alpha Ads - Unity Ads Integration exposes rewarded video, banner, interstitial ads to UE4 Blueprint projects on Android. No C++ required.

## Features

- Banner, Interstitial, and Rewarded Video ad formats
- Full Blueprint API — no C++ required
- Event delegates for all ad lifecycle callbacks (Loaded, Failed, Shown, Clicked, Closed, Rewarded)
- Game Instance Subsystem access from any Blueprint
- GDPR / CCPA / COPPA consent API
- Test mode toggle for development builds
- Bundled SDK — zero external download or setup
- Android armv7 + arm64 support
- Project Settings panel for credentials (Game ID, Placement IDs)
- UE 4.27 compatible

## Third-Party SDK

| Field | Value |
|---|---|
| SDK | Unity Ads v2.0.5 |
| Provider | Unity Technologies |
| License | Unity Ads SDK Terms |
| File | `Source/ThirdParty/UnityAdsSDK/UnityAdsSDK.jar` |
| Site | https://unityads.unity3d.com |

> You must independently agree to the Unity Ads terms and set up your own account.

---

## Setup

1. Copy plugin to your project Plugins/ directory.
2. Enable in Edit > Plugins.
3. Enter credentials in Edit > Project Settings > Alpha Ads - Unity Ads Integration.
4. Rebuild and package Android Shipping.

---

## Example Project

A minimal demo project is included with the plugin download under `/ExampleProject`. It contains:

- A sample Level (`L_AdsDemo`) with UMG buttons for each ad format
- A demo Blueprint (`BP_AdsManager`) showing init, load, show, and event-binding flow
- Pre-configured Project Settings using Unity Ads test Game ID / Placement IDs
- Ready-to-package Android Shipping config (armv7 + arm64)

Open `ExampleProject/AdsDemo.uproject` in UE 4.27, enable the plugin, and Launch on an Android device to verify integration.

---

## License

Integration code is subject to the Fab product page terms. Bundled SDK files have their own licenses (see ThirdPartyNotices.md).
