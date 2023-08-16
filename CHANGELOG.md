## Platform Specifics
The following setting options available on both iOS and Android: openAppSettings, openWIFISettings, openLocationSettings, openSecuritySettings, openBluetoothSettings, openDataRoamingSettings, openDateSettings, openDisplaySettings, openNotificationSettings, openSoundSettings

### iOS
All three options open the current 'app' settings section if there are settings defined.  If no current settings are defined for the app the iPhone Settings Screen will be displayed.

### Android
Each option will open and display the corresponding screen: WIFI, Location, or Security, etc.

## 4.1.6
Ability to open personal hotspot settings.
Ability to open custom intents.

## 4.1.5
Ability to open developer settings.  ** App user will need to have enabled developer mode on their device in order for this feature to open the developer settings screen.

## 4.1.4
Migration from jcenter() to mavenCentral()

## 4.1.3
Added Android open Lock & Password settings.

## 4.1.2
Update Android compileSdkVersion to 31.
Removed deprecated calls in Registrar
Migrated plugin to v1.12: https://docs.flutter.dev/development/packages-and-plugins/plugin-api-migration

## 4.1.1
Ability to open VPN settings.
Ability to open device settings screen.

## 4.1.0
Null safety support.
Ability to open settings as a new task on Android.
Updates to README.

## 4.0.4
Updated plugin to support android new package api for post 1.12 flutter.

## 4.0.3
Bug fix for Android openNotificationSettings.

## 4.0.2
Adding in NFC settings access for Android. iOS will still rely on App Settings.

## 4.0.1+1
Update Android compileSdkVersion to 30.

## 4.0.1
Added Battery Optimization settings access for Android.  iOS will still rely on App Settings.

## 4.0.0
Updates Gradle wrapper distribution from 4.6 -> 6.2.2

Updates Kotlin plugin version from 1.3.50 -> 1.3.70

Updates Android Gradle plugin from 3.5.1 -> 3.6.1

Updates compileSdkVersion from 28 -> 'android-R'

Also removes generated/non-essential files, updates .gitignore to the latest flutter create standard and "fixes" faulty example test. Tested and working on Android R. Should probably be tested on lower API devices as well.

## 3.0.1
Added Internal Storage settings access for Android.  iOS will still rely on App Settings.

## 3.0.0+1
Update plugin version in `.podspec`

## 3.0.0
Upgrade to Swift version: 5.0.1 - This version will only work on projects running Swift 5.0.1

## 2.0.2
Legacy Swift 4 support.

## 2.0.2
Added Date, Display, Notification, and Sound settings access for Android.  iOS will still rely on App Settings.

## 2.0.1+1
Added Bluetooth & Data Roaming settings access for Android (more to come).  iOS will still rely on App Settings.

## 2.0.0
Update AGP, migrate to `AndroidX`

## 1.0.6+2
Added missing `podspec` description

## 1.0.6+1
  ***iOS TIP: If using Objective-C for iOS in your project, you will need to add `use_frameworks!` to your `Runner project podfile` in order to use this Swift plugin:***
    
    - target 'Runner' do
        use_frameworks!

## 1.0.6

Add openAppSettings() to access platform specific 'app' settings menu.

## 1.0.5

Ensure the plugin stays compatible with iOS8+.
Declare Swift compatibility version 4.2.

## 1.0.4

Upgrading Kotlin version from: ext.kotlin_version = '1.2.71' to ext.kotlin_version = '1.3.20'


## 1.0.3

Adding additional documentation.
