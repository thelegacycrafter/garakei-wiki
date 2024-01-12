---
weight: 1
title: "APKs"
description: "How to get APKs for your Keitai/Garakei."
---
# APKs guide

## Installation steps
This is a general list of steps for sideloading APKs via ADB on Android devices. Please check your model's wiki page for any further info.
### Initial setup
These steps only need to be done for the first time.
1. Enable Developer Options by going to `Settings`, `About phone`, and tapping `Build number` seven times. The exact menu layout may depend on the phone model - sometimes the build number is under `Software info` or similar.
2. Go back to Settings, you will now see `Developer options`. Go there and enable `USB debugging`.
3. Download Android platform tools (which includes ADB) to your PC from [Android's developer site](https://developer.android.com/tools/releases/platform-tools#downloads).
4. Extract the platform tools ZIP you downloaded.
### APK installation
1. Find the APK you want to install and download it to your computer. You can find APKs from the list at the bottom of this page, or from various other sites.
2. Plug your phone into your computer.
3. Go to the Android platform tools folder that you extracted previously, and open it in a command prompt or terminal.
4. Write `adb install ` (with a space at the end) into the command prompt, but don't press Enter yet. On Linux, write `./` before `adb`.
5. Locate your downloaded APK in the file manager, and drag the APK file into the command prompt window.
6. Press Enter.

## Websites with APKs
* [F-Droid](https://f-droid.org/en/): Repository of open-source Android apps, many of which work well on low-end devices like Garakeis.

## Useful APKs
* [Key Mapper](https://github.com/keymapperorg/KeyMapper/releases/tag/v2.6.0): Allows rebinding hardware keys to different keycodes or custom actions.
