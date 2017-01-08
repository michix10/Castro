# Changelog

- Latest production version: 2.1.5
- Latest beta version: 2.2 Beta 01

This changelog is for beta version of Castro. Changelog for main version can be found [here](CHANGELOG_RELEASE.md).

## Castro [2.2 Beta 01] - 08.01.2017
### Information
- Added [System]: Full names for OS versions (ex. Nougat 7.1.1).
- Added [System]: SELinux state (ex. Enforcing).
- Added [Battery]: Current charge rate measuring.
- Added [Battery]: Minimal and Maximal voltage rate.
- Added [Battery]: Check for USB fast charging technology support.
- Added [Processor]: New category - Power saving.
- Added [Processor]: Check for Multi-core saving technology.
- Added [Processor]: GPU minimal and maximal frequency detection.
- Added [Processor]: GPU governor detection.
- Added [Memory]: New category - Storage.
- Added [Memory]: Checks for storage encryption and protection support.
- Added [Memory]: Check for Buffer total memory.
- Added [Memory]: Check for SWAP total, available and cached memory.
- Added [Device]: Check for Fingerprint scanner availability.
- Added [Sensors]: Sensors API improved.
- Added [Sensors]: Dialog with additional infomation - Full name, Vendor, Type, Version, Resolution, Power consumption, Maximum range.
- Added [Network]: Checks for current and available TCP algorithms.

### Design
- Updated: Theme engine to version 1.1. Added support for changing accent color of the application. **!Could be unstable. To take effect manualy restart application!.**
- Updated: Primary color of Sensors card in Other window.
- Updated: Round icons support for Pixel devices.
- Added: Landscape orientation for Go Premium windows.

### Features
- Added: Runtime check for Identifiers permission in Device category.
- Updated: Analytics core engine.

## Fixes
- Fixed: Two-line Codec name in Codecs category displaying.


## Castro [2.1 Beta 02] - 25.09.2016
### Information
- Added: Codecs API are finished now.

### Design
- Added: Graphics for Codecs module.

### Features
- Added: All strings are finalized now.
- Added: All small graphics changed to vector format.
- Added: All big graphics has optimized size now.

### Bug fixes
- Fixed: Force close in Memory category.

### Tools
- Updated: Built with Android Studio 2.2.
- Updated: Gradle plugin to version 2.2.0.
- Updated: Android Support Library to version 24.2.1.
- Removed: FastAdapter library changed with own equivalent.

## Castro [2.1 Beta 01] - 06.09.2016
### Information
- Added: New category in Other - Codecs (Detection of Audio and Video properties, check is encoder, etc.).
- Added: Technologies category for Processor (Checks support for SWP, NEON and Thumb technologies).
- Added: DSP version of CPU for recognized devices.
- Added: Technical Process of CPU for recognized devices.
- Added: Up to 100 new devices for SoC database (LG V10 (12 models), LG G4 (23 models), LG G5 (15 models), LG G5SE (3 models), Moto G3 (6 models), all OnePlus phones (X, One, Two and Three), many Xiaomi phones (Redmi Rice, Redmi 1S, MI 2, MI 2S, MI 2A, MI 3W, MI 4C, MI 4S, MI MAX, MI NOTE LTE, MI NOTE Pro, MI PAD, MI PAD 2, Mi 4i, Redmi 3S), Galaxy S7, S7 Edge, S7 Active and Galaxy Note 7).
- Added: Support for systemless Root and BusyBox (/xbin/su and other).
- Added: Build Tags field in System.
- Added: Font scale property to System.
- Added: Check for Disk Encryption in System.
- Added: Version of many Android Libraries in System (ICU, ICU CLDR, OpenSSL and ZLib).
- Improved: Speed of SoC detection.
- Improved: Speed of Root and BusyBox detection.

### Features
- Added: Device identifier to Feedback screen.
- Added: Ability to force use English language for whole application.
- Added: Memory extension for Premium Widget [PREMIUM].
- Added: All extensions support for Roman Nurik's DashClock [PREMIUM].
- Added: Vector graphics support for all Android version.
- Removed: Dropped support for Android 4.0.3 and earlier.
- Removed: Invites feature from Settings screen (This function wasn't popular).

### Bug fixes
- Fixed: Open GL detection on some devices.
- Fixed: View's unbinding when Fragments destroying.

### Tools
- Improved: Built with Android Studio 2.1.3.
- Updated: Built Tools to version 24.0.2.
- Updated: Android Support Library to version 24.2.0.
- Updated: Material Dialogs to version 0.9.0.1.
- Updated: TedPermission to version 1.0.12.
- Updated: Crashlytics to version 2.6.2.
- Updated: ButterKnife for version 8.4.0.

## Castro [2.0 Beta 05] - 02.06.2016
### Information
- Improved: External memory API to show proper information.

### Design
- Added: Night mode [Premium version].
- Simplified: All themes simplified to one theme (Made to get night theme work; There is bug in Feedback window with status bar color for now).

### Information
- Added: Plus before phone number in Cellular category.

### Features
- Added: Firebase Analytics and Firebase Crash instead of Fabric.
- Added: Ability to send invites for friends to try out Castro (Still experimenting with the placement of the item).

### Bug fixes
- Fixed: Showing total and available external memory on some devices.
- Fixed: Flash bugs in Front camera category on some devices.

### Tools
- Improved: Built with Android Studio 2.1.1.
- Updated: Android Support Library to version 23.4.0.
- Updated: Zene to version 1.2 (Now work properly with Night Theme).
- Updated: TedPermission to version 1.0.11.

## Castro [2.0 Beta 04] - 04.05.2016
### Design
- Updated: Design of Wi-Fi disabled window.

### Features
- Added: Ability to open system settings from Battery category.
- Added: Export information to PDF and Text files.
- Added: Request to use only English language, when sending feedback.
- Improved: Runtime Permissions model for Android 6.0.

### Localization
- Added: All information strings for translation.

### Bug fixes
- Fixed: Major fixes for Camera related erros.
- Fixed: Processor initialization in Welcome window.
- Fixed: Sensors hiding, if it is unavailable.
- Fixed: Error with Wi-Fi disabling.
- Fixed: Showing video stabilization in Back and Front camera categories.
- Fixed: Showing feedback button in About window on phones.

### Tools
- Improved: Built with Android Studio 2.1.
- Updated: ButterKnife to version 8.0.1.
- Updated: TedPermission to version 1.0.9.

## Castro [2.0 Beta 03] - 18.04.2016
### Design
- Added: Bottom sheet dialog to choose export method.
- Added: Back and Front camera layouts for tablet version.
- Added: Feedback layout for tablet version.
- Fixed: Separator color in Navigation Drawer for tablet version.

### Features
- Added: Homescreen widget (without Configuration window for now) [Premium Version]

### Bug fixes
- Fixed: Error when getting Camera's resolution.
- Fixed: Processor initialization in Welcome window.

### Tools
- Replaced: BottomSheetBuilder library by Android Support equivalent.
- Replaced: Typography library by own equivalent.
- Updated: Material Dialogs to version 0.8.5.8.

## Castro [2.0 Beta 02] - 08.04.2016
### Design
- Added: Tablet design for main Information windows.
- Improved: Toolbar font in Sensors, Back and Front camera.

### Information
- Added: Uptime (without Deep Sleep) in System category.
- Added: Five new devices in processor's database.
- Improved: Displaying cellular information on tablets without SIM card.

### Features
- Added: Changelog list in Settings.

### Localization
- Improved: Localization in Settings.

### Bug fixes
- Fixed: Crash caused by Remember in Welcome window.
- Fixed: View initialization error on some devices.

### Tools
- Improved: Built with Android Studio 2.0.
- Updated: Build tools to version 23.0.3.
- Updated: Gradle plugin to version 2.0.0.
- Updated: Support libraries to version 23.3.0.
- Removed: Changelog library.

## Castro [2.0 Beta 01] - 04.04.2016
- Initial Beta release.
