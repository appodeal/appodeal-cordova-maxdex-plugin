# Appodeal Cordova Plugin Max Dex

This is official Appodeal Cordova plugin, created to support Appodeal SDK with Apache Cordova.
This version supports android platform only. Use it in case if you receive "method ID not in [0, 0xffff]: 65536" build error with other versions.

## SDK
[![](https://img.shields.io/badge/docs-android-green.svg)](http://www.appodeal.com/sdk/cordova2)

Appodeal Android SDK already included to the plugin.

## Install

Simply go to the project folder over console/terminal and run there following command:

    cordova plugin add https://github.com/appodeal/appodeal-cordova-maxdex-plugin.git#cordova2

Google Play Services (v9+) already included to plugin dependencies.

If you have issues while installing plugin, follow the Command-line Interface Guide.

Minimum OS requirements: Android API level 9 (Android OS 2.3).

Android Appodeal SDK version 2.0.2

    
## Changelog

3.0.0 (20.06.2017)

+ Appodeal Android SDK updated to 2.02
+ Appodeal.confirm removed
+ Appodeal.canShow added
+ SetOnLoadedTriggerBoth renamed to setTriggerOnLoadedOnPrecache
+ callbacks reworked, follow docs on appodeal.com/sdk/cordova2
+ optional permissions to AndroidManifest added

2.0.1 (31.10.2016)

+ Appodeal Android SDK updated to 1.15.7
+ Android libraries and frameworks updated
