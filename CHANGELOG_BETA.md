# Changelog

- Latest production version: 1.5.1
- Latest beta version: 2.0 Beta 05

This changelog is for beta version of Castro. Changelog for main version can be found [here](CHANGELOG_RELEASE.md).

## Castro [2.0 Beta 05] - 02.06.2016
### Information
- Improved: External memory API to show proper information.

### Design
- Added: Night mode [PRO version].
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
- Added: Homescreen widget (without Configuration window for now) [PRO Version]

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
