# Changelog

- Latest production version: 2.5
- Latest beta version: 2.5 Beta 02

This changelog is for release version of Castro. Changelog for beta version can be found [here](CHANGELOG_BETA.md).

## Castro [2.5] - 23.12.2017
### Information
- Added [Cellular]: New category - Speed;
- Added [Cellular]: Download network speed;
- Added [Cellular]: Upload network speed;
- Added [Device]: sRGB support.

### Design
- Added: Support for Adaptive Icons.
- Updated: Overhaul design of Other window.
- Updated: Promotion screenshots with updated screens and separation of basic and premium features [NOT RELEASED].
- Updated: Icons size in Sensors list.
- Updated: Width of Licesnses dialog in settings.
- Imroved: Permormance of all vector icons using AVDO tool.

### Features
- Added [Premium]: Notification with realtime Download and Upload speed measuring.
- Added: Native support for fonts.
- Added [Build 60]: Danish, Czech and Portuguese (Brazil) languages.
- Updated: Runtime permissions handling library.

### Fixes
- Fixed: Bug, when device name squeezed out Premium badge in Navigation Drawer.
- Fixed: White toolbar's background color, when toolbar collapsed.
- Fixed: Crashes on WelcomeActivity.
- Fixed: Accent color picker mixed layout.
- Fixed: Incorrect colors with enabled Night mode.
- Fixed [Build 59]: Reverted missing application icon.
- Fixed: Correct changelog (for release version) displays in Settings window.

## Castro [2.4] - 08.10.2017
### Information
- Added [Sensors]: More sensors type - Game Rotation Vector and Rotation Vector.
- Added [Sensors]: Graph to display realtime changes in sensor's values.
- Added [Sensors]: Maximum events count.
- Added [Sensors]: Maximum delay between events.
- Added [Sensors]: Minimum delay between events.
- Added [Sensors]: Reporting mode of sensor.
- Added [Sensors]: Check for Dynamic sensor.
- Added [Sensors]: Check for Wake-Up sensor.

### Design
- Added: Toolbar shadow when scrolling in some windows (more coming during beta).
- Updated: Overhaul design of Export information dialog.
- Updated: Overhaul design of Open source licenses dialog.
- Updated: Overhaul design of Sensors window.
- Updated: Overhaul design of About Castro window.
- Updated: Medium icon in About Castro window.

### Features
- Added: Firebase Analytics, Firebase Crash Reporting and Firebase Performance Monitoring modules instead of Crashlytics.
- Added: Initial support for Android O.
- Added: Rate us button in About Castro window.
- Added: Anonymous reports support in Export information dialog.
- Added: Support for CSV format of reports in Export information dialog.
- Updated: Library to work with runtime permissions.
- Updated: List of Open-Source libraries used by application.
- Updated: Theme Engine now supports hot swap of accent color.
- Removed: Feedback button from About Castro window.

### Fixes
- Fixed: Colors of Other cards in Night mode.

## Castro [2.3] - 12.05.2017
### Information
- Added [Battery]: "Unknown" statuses for Charge state and Health state fields.
- Added [Wi-Fi]: New category - Technologies.
- Added [Wi-Fi]: Check for Device-to-AP RTT support.
- Added [Wi-Fi]: Check for Wi-Fi Direct support.
- Added [Camera]: Current and Supported Flash modes.
- Added [Camera]: Current and Supported White-Balance modes.
- Added [Processor]: New devices in database: BlackBerry (Aurora, DTEK50, DTEK60, KEYOne, Priv), LG (G6), Huawei (P10, P10 Plus), Xiaomi (MI 5C, MI PAD 3), Samsung (Galaxy Tab S3, Galaxy S8, Galaxy S8+), Sony (Xperia XZ, XZS, XA1).
- Added [Processor]: New types of SoC in database: Xiaomi Surge S1, MediaTek MT8176, Snapdragon 820 APQ8096, Snapdragon 835 MSM8998, Exynos 9 Octa 8895M.

### Design
- Updated: Icon for accessing Battery's system settings.

### Features
- Added: Support for new "tall" displays (Samsung Galaxy S8 and LG G6).
- Added: Android 7.1 Shortcuts to create reports.
- Added: Ability to access system settings for Memory, Wi-Fi, Cellular right from Castro by clicking icon in Toolbar.
- Added: Missing string about DashClock widgets in Go Premium window.
- Improved: RTL support.
- Improved: Tablets detection method now work better.
- Improved: SIM card detection method now work better.
- Improved: Wi-Fi detection method now detects not only enabled Wi-Fi, but connected also.

### Perfromance
- Updated: All .png graphics files updated with new Google format - .webp.
- Updated: Rules for ProGuard with even more orientation steps.
- Imroved: Speed of Root detection.

### Fixes
- Fixed: Small improvements for normal widget [PREMIUM].
- Fixed: Repeatable information from export feature.
- Fixed: Normal widget's icons croping [PREMIUM].
- Removed: Degree for Kelvin temprature.

### Tools
- Updated: PDF creation engine.

## Castro [2.2.1] - 07.02.2017 | Castro [2.2.1 Build 2] - 09.02.2017
### Features
- Added: Privacy Policy in Settings window.

### Design
- Added: Color tinting for Navigation Drawer's header in tablet version [BUILD 2 ONLY].

### Localization
- Fixed: Many mistakes in all localizations [BUILD 2 ONLY].

### Fixes
- Fixed: Navigation Drawer crash on some devices.
- Fixed: Crash in Go Premium window on Android 4.4 and lower.
- Fixed: Rare crash in Battery category [BUILD 2 ONLY].
- Fixed: Rare crash in Sensors category.
- Fixed: Crash while detecting explicit type of Codecs.
- Fixed: Rare crash on start.

## Castro [2.2] - 29.01.2017
### Information
- Added [System]: SELinux state (ex. Enforcing).
- Added [Battery]: Current charge rate measuring.
- Added [Battery]: Minimal and Maximal voltage rate.
- Added [Battery]: Check for USB fast charging technology support.
- Added [Processor]: New category - Power saving.
- Added [Processor]: Check for Multi-core saving technology.
- Added [Processor]: GPU minimal and maximal frequency detection.
- Added [Processor]: GPU governor detection.
- Added [Processor]: Support for Kirin 655, Kirin 950, Kirin 960, Snapdragon 625, Snapdragon 400 (MSM8928), Snapdragon 800 (MSM8996 Lite), Snapdragon 801 (MSM8974AC v3), Exynos 7 (7578), Exynos 7 (7870), Exynos 7 (7880), MediaTek MT6580M.
- Added [Processor]: New devices in SoC database (Xperia M2 Aqua, Xperia M5, Xperia M5 Dual, Xperia T2 Ultra, Xperia T2 Ultra Dual, Xperia Z, Xperia Z3 Compact, Xperia SP, Mate 8, Mate 9, Mate 9 PRO, Nokia N1, Nokia 6, Honor 6X, Zenfone 3 ZOOM, Zenfone 6, Redmi Note 4G, MI 5s Plus, MI Mix, MI 5s, Redmi 4, Redmi 4 PRO, Redmi 4A, Redmi Note 4X, Galaxy A3 (2016), Galaxy A3 (2017), Galaxy A5 (2016), Galaxy A5 (2017), Galaxy A7 (2017), Galaxy Grand Neo Plus, Moto Z, Moto X Pure Edition, Moto Z Play Droid, OnePlus 3T, Flare X 2, Wiko Lenny3, LG Volt, LG Volt 4G, Micromax Bolt Q338, Meizu PRO 5, Tegra Note 7.
- Added [System]: Full names for OS versions (ex. Nougat 7.1.1).
- Added [Memory]: New category - Storage.
- Added [Memory]: Checks for storage encryption and protection support.
- Added [Memory]: Check for Buffer total memory.
- Added [Memory]: Check for SWAP total, available and cached memory.
- Added [Device]: Check for Fingerprint scanner availability.
- Added [Sensors]: Sensors API improved.
- Added [Sensors]: Dialog with additional infomation - Full name, Vendor, Type, Version, Resolution, Power consumption, Maximum range.
- Added [Network]: Checks for current and available TCP algorithms.

### Design
- Added: Landscape orientation for Go Premium windows.
- Updated: Theme engine to version 1.1. Added support for changing accent color of the application.
- Updated: Primary color of Sensors card in Other window.
- Updated: Round icons support for Pixel devices.

### Features
- Added: Runtime check for Identifiers permission in Device category.
- Updated: FAQ with new abbreviations and removed some incorrect information.
- Updated: Algorithm to detect unrecognized processors and devices.
- Updated: Analytics core engine.

### Fixes
- Added: Scroll in landscape orientation in About window.
- Fixed: Missing OS Version string in English localization.
- Fixed: Two-line Codec name in Codecs category displaying.

## Castro [2.1.5] - 30.10.2016
### Design:
- Added: Soft shadows for category cards in Other window;
- Added: New algorithm to scale cards for big phones and tablets in Other window;
- Improved: fixed blank status bar in Feedback window on tablets;

### Features
- Added: Initial support for Android 7.1;
- Added: Camera modes information to TXT and PDF reports;
- Added: Title and Date in TXT report;
- Improved: Organized PDF report layout (added subcategories);
- Improved: Creation date of both, TXT and PDF reports;
- Updated: Crash reporting engine;
- Updated: PDF reports creating engine;

### Bug fixes
- Improved: Overhaul performance;
- Fixed: External memory information export;
- Fixed: Bug with two Zoom in reports (now Flash and Zoom);
- Fixed: Blank status bar in Feedback window on tablets
- Fixed: Crash in Processor category, when Castro can't detect OpenGL version;
- Fixed: Crash in Processor category, when Castro can't check NEON technology support;

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
