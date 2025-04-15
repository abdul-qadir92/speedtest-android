![LibreSpeed-Android Logo](https://github.com/adolfintel/speedtest-android/blob/master/.github/Readme-Logo.png?raw=true)
 
# LibreSpeed Android Template
The Speedtest Android template allows you to configure and distribute an Android app that performs a speedtest using your existing [LibreSpeed](https://github.com/librespeed/speedtest) server(s).

The template is easy to configure, customize and distribute.
 
## Try it

[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png"
     alt="Get it on F-Droid"
     height="80">](https://f-droid.org/packages/com.dosse.speedtest/)

Alternatively, you can [download a demo APK](https://downloads.fdossena.com/geth.php?r=speedtest-android-apk)

## Compatibility
Android 4.0.3 and up (SDK 15), all architectures.

## Features
* Download
* Upload
* Ping
* Jitter
* IP Address, ISP, distance from server (optional)
* Telemetry (optional)
* Results sharing (optional)
* Multiple Points of Test (optional)

![Screenshot](https://github.com/librespeed/speedtest-android/blob/master/.github/screenshots.png?raw=true)

## Server requirements
One or more servers with [LibreSpeed](https://github.com/librespeed/speedtest) installed.

## Donate
[![Donate with Liberapay](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/fdossena/donate)  
[Donate with PayPal](https://www.paypal.me/sineisochronic)  

## BrowserStack Integration

Generate the app apk file: 
-   `Build > Make Project` or `Build > Build Bundle(s) / APK(s) > Build APK(s)`
- File can be found in `Speedtest-Android/app/build/outputs/apk/debug`

Generate the Espresso Test apk file:
 - From your project root, run:

    `/gradlew assembleDebugAndroidTest`  [mac]
    `gradlew.bat assembleDebugAndroidTest` [Windows]
- This will generate Espresso apk test file in `Speedtest-Android/app/build/outputs/apk/androidTest/debug`

Follow the rest of the steps from the official [document](https://www.browserstack.com/docs/app-automate/espresso/getting-started)

## License
Copyright (C) 2020 Federico Dossena

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU Lesser General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/lgpl>.
