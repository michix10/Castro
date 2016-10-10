# Changelog

- Latest production version: 2.1
- Latest beta version: 2.1 Beta 02

This changelog is for release version of Castro. Changelog for beta version can be found [here](CHANGELOG_BETA.md).

## Castro [2.1] - 10.10.2016
### Information:
- Added: New category in Other - Codecs (Detection of Audio and Video properties, check is encoder, etc.).
- Added: Technologies category for Processor (Checks support for SWP, NEON and Thumb technologies).
- Added: DSP version of CPU for recognized devices.
- Added: Technical Process of CPU for recognized devices.
- Added: Up to 100 new devices for SoC database (newly released Pixel, Pixel XL and LG V20. LG V10, LG G4, LG G5, LG G5 SE, Moto G3, all OnePlus phones, all Xiaomi phones, Galaxy S7, Galaxy S7 EDGE, Galaxy Note 7, Galaxy Note 5, Galaxy Note 4, Xperia X, Xperia X Compact, Xperia X Performance, Xperia XA, Xperia XA Ultra, Xperia XZ, Xperia E5, Xperia C4 dual, Google Pixel C, Google Tango Tablet Development Kit, Moto G4, OPPO A33 and other).
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
- Added: New category in FAQ - Abbreviations;
- Removed: Dropped support for Android 4.0.3 and earlier.
- Removed: Invites feature from Settings screen (This function wasn't popular).

### Bug fixes
- Fixed: Open GL detection on some devices.
- Fixed: View's unbinding when Fragments destroying.
- Fixed: Force close in Feedback window on tablets;
- Fixed: Force close in Processor window on tablets;
- Fixed: Feedback window title localization;
- Fixed: Force close, if Castro can’t detect CPU temperature;

## Castro [2.0.1] - 04.07.2016
### Information:
- Added: New Memory API, which now correctly detects external memory.
- Improved: Emulated external memory is no longer considered as an external memory.

### Localization:
- Added: Chinese Simplified language.
- Added: Portuguese (Brazil) language.
- Improved: Existing translations.

### Bug fixes
- Fixed: FC when creating Data reports.
- Fixed: Added the cap in Welcome window (Used when the Сamera information may not be initialized, so that Castro could continue work without FC).
- Fixed: The error that prevented the display of the Processor temperature.
- Fixed: The error that prevented the display of the Battery temperature and voltage.
- Fixed: The error due to which the available memory was not shown in percentage.
- Fixed: Wrong color in recent tasks from Premium window.
- Fixed: Humburger icon on Tablets.
- Fixed: Tablet detection.
- Fixed: BusyBox detection.

## Castro [2.0] - 01.07.2016
### Information
- Added: Processor API 2.0 (SoC identification, GPU identification, CPU temperature, Vulkan detection, Hexa and Octa cores CPU support).
- Added: Camera API 2.0 (Auto exposure and Auto white balance states, Vertical and Horizontal angle, Maximum faces in frame, Video stabilization state, Color effect, Focus, Scene and Antibanding current and supported modes)
- Added: Display density in Device category.
- Added: Voice mail state, World phone check and ICC card in Cellular category.
- Added: Wi-Fi 5GHz band check in Wi-Fi category.
- Added: New sensors support - Acceleration and Gravity.
- Added: Support for Systemless Root.
- Added: Uptime (without Deep Sleep) and Security Patch in System category.
- Improved: Detection of BusyBox.
- Improved: Detection of External memory.

### Design
- Added: Tablet design.
- Added: Night Mode [Premium].
- Added: Medium font for ActionBar in all windows.
- Added: Animation when scrolling in Feedback window.
- Improved: Design of Data reports dialog.
- Improved: Redesigned main icon.
- Improved: Overhaul design.

### Features
- Added: Initial support for Android N.
- Added: Ability to submit application.
- Added: Ability to open System Battery Settings from Battery category.
- Added: Customisable homescreen widget [Premium].
- Added: Kelvin temperature unit in Settings.
- Added: Ability to change Voltage unit in Settings.
- Added: Built-in browser to view Changelog, Medium Blog and other links.
- Added: Built-in FAQ in Settings.
- Added: Possibility to send feedback from the window About Castro.
- Improved: Data reports system to save dynamic and Camera data.
- Improved: Runtime Permissions model on Android M.

### Localization
- Added: Ask to use English in Feedback window.

### Bug fixes
- Fixed: Wrong total external memory in Memory category.
- Fixed: Flash detection in Camera category.
- Fixed: 0.1 MP Camera bug.
- Fixed: Detection of Front camera.
- Fixed: Sensors hiding in Sensors category.
- Fixed: View initialization error on various devices.

### Tools
- Updated: Zene library, to support Material Design Dialogs on Android 4.4 and older.
