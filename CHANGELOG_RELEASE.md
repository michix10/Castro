# Changelog

- Latest production version: 2.8.8
- Latest beta version: Unavailable

This changelog is for release version of Castro. Changelog for beta version can be found [here](CHANGELOG_BETA.md).

## Castro [2.8.8] - 01.11.2018
## Information
- Added [Processor]:  New devices in database: Google (Pixel 3, Pixel 3 XL), OnePlus 6T, Xiaomi (Mi MIX 3, Pocofone F1, Black Shark), Huawei (Mate 20, Mate 20 PRO, Mate 20 Lite), LG V40 ThinQ, Nokia (7.1, 7.1 Plus), Razer Phone 2, Asus ROG Phone.
- Added [Processor]: New SoC in database:  Kirin 710, Kirin 980.

## Features
- Added: Support for Android App Bundle to reduce final APK size

## Castro [2.8.7] - 02.10.2018
## Information
- Removed [Device]: Removed Google Play Services identifier.
- Removed [System]: LineageOS version.
- Removed [Battery]: LineageOS performance profile.

## Other
- Updated: Privacy Policy with new information.

## Castro [2.8.6] - 07.08.2018
## Information
- Added [Processor]: New devices in database: Xiaomi (MI A2, MI A2 Lite), Samsung (TAB S4), Honor (Play) and Huawei (Nova 3I).

### Features
- Added: Basic support for Android Pie (9.0).
- Added: Belarusian language.

## Castro [2.8.5] - 18.07.2018
## Information
- Added [Processor]: New devices in database: Xiaomi (Mi PAD 4, Redmi 6, Redmi 6A, Redmi 6 Pro), Vivo (Nex S, Nex A).
- Added [Processor]: New SoC in database: MediaTek (Helio P22, Helio A22).

### Features
- Improved: Scroll resets after category changes.

## Design
- Improved: Removed capitalizer for each letter in Premium window.

### Fixes
- Fixed: Crash on devices with old Android versions.
- Fixed: Crash on Devices category.

## Castro [2.8.2] - 21.06.2018
### Fixes
- Fixed: Font size for titles in Settings.
- Fixed: Crash in Device category (Google Services Framework ID).
- Fixed: Crash in translators list.

## Castro [2.8.1] - 19.06.2018
### Design
- Improved: Margins for default "data" fields.
- Improved: Titles font size.

### Fixes
- Fixed: Added missing localization files
- Fixed: Added Portugal flag in traslators list.
- Fixed: Crash in Codecs list.

## Castro [2.8] - 18.06.2018
### Information
- Added [Bluetooth]: Added new category - Bluetooth in Other. It will check for Low Energy and other technologies support. Also can check connected devices properties.
- Added [Processor]: New devices in database - Primo N2,  OnePlus 5,  Xiaomi (MI 6X, MI 8, MI 8 SE, Redmi S2), BlackBerry KEY2, Nokia (3.1, 5.1, 6.1, 8 Sirocco, X6), LG V35 ThinQ, Meizu (15, 15 Lite, 15 Plus, E3).
- Added [Processor]: New SoC in database - Snapdragon 660, Snapdragon 710.
- Added [Device]: In identifiers section added Google Services Framework ID.
- Added [Device]: In identifiers section added IMEI 2 for dual-sim devices.
- Added [Device]: In identifiers section added MEID 1 and MEID 2 for CDMA devices.
- Added [Device]: New section - HDR. It will check for display's HDR support.
- Added [System]: In OS section added P check support (will it be Pineapple?).
- Added [System]: In miscellaneous section added version of Google Play Services.
- Added [System]: In miscellaneous section added version of Java Runtime.
- Improved [Wi-Fi]: In properties section Signal field now shows in percents.
- Improved [Processor]: In CPU section Supported ABI field will display 64-bit ABI aswell.

### Design
- Added: Main font for all section titles is now Roboto Monospace.
- Added: Animation for settings categories transitions between screens.
- Updated [PREMIUM]: Layout of Speed notification screen with "example of usage".
- Updated [PREMIUM]: Added more contrast color for Navigation Drawer and other navigation elements in OLED theme.
- Updated [PREMIUM]: Status bar color updated with darker variant for both Night and OLED theme.
- Updated: Most of vector icons updated to Material Design 2.0 specification.
- Updated: Icons for system settings links in Battery, Memory, Internet and Wi-Fi updated to Material Design 2.0 specification.
- Improved: Margins and paddings on Sensor details screen.
- Improved: Optimized size of many raster icons and images.

### Features
- Added: Double click to exit application to prevent false application closures.
- Added: Possibility to reset all measurement settings to default state.
- Added: Link to SIM system settings in SIM category.

### Fixes
- Fixed [Wi-Fi]: In properties section SSID field will be hidden if Hidden SSID enabled in router.
- Fixed [Codecs]: All codecs types were marked as "Unavailable".
- Fixed [System]: Bootloader version was marked as "Unknown".
- Fixed [System]: Wrong detection of SELinux state.
- Fixed: Useless restart dialogs in measurement settings removed.

## Castro [2.7.2] - 07.05.2018
### Features:
- Updated: Italian localization;
- Updated: Firebase libraries.

## Castro [2.7.1] - 30.04.2018
### Features:
- Updated: Spanish localization;
- Updated: System libraries and ProGuard configuration.

## Fixes
- Fixed: Crash on startup. 
- Fixed: Crash in Codecs detailed dialogs.

## Castro [2.7] - 12.04.2018
## Information
- Added [System]: LineageOS version.
- Added [Battery]: Active performance profile for LineageOS.
- Added [Processor]: Support for Kirin 659 processor.
- Added [Processor]: Lenovo YB1-X90F, Huawei P20, P20 PRO, P20 Lite and Xiaomi Mi MIX 2S added to devices database.
- Updated [Battery]: Current charge speed method updated to work on more devices.

### Design
- Updated [PREMIUM]: Widget titles font.
- Updated [PREMIUM]: Titles colors changes dynamically now in Configure Widget screen.
- Updated [PREMIUM]: Titles font in Configure Widget screen.
- Updated [PREMIUM]: Widget's preview image.
- Updated: Design of Codec detailed information dialog.
- Updated: Design of Color Choser dialog.

### Features
- Added [PREMIUM]: 10 seconds refresh interval for widget.
- Added [PREMIUM]: AMOLED Night mode.
- Updated [PREMIUM]: Widget background worker.
- Updated [PREMIUM]: Widget information update in background.
- Removed [PREMIUM]: Support for DashClock widgets.
- Added: More accent colors combinations in Settings.
- Added: Permissions handling in SIM section.
- Updated: Codecs information handler.

### Fixes
- Fixed [PREMIUM]: Configure widget screen’s missing background in rare cases.
- Fixed [PREMIUM]: Configure widget screen now properly works with Night modes.
- Fixed [PREMIUM]: Configure widget screen now properly works with accent colors.
- Fixed [PREMIUM]: Crashes when trying to open system settings from information sections.
- Fixed [PREMIUM]: Memory leak during widget’s background work.
- Fixed: Mistakes in localization for Device section.
- Fixed: Missing title in Measurements settings.
- Fixed: Crash when trying to open Google Play from application.
- Fixed: Missing launcher icon on Android Nougat and earlier.

## Castro [2.6.2] - 14.03.2018
### Fixes
- Fixed: Crash when using Network Speed notification.
- Fixed: Crash when viewing specific codecs.

### Localization
- Updated: Spanish translation.
- Updated: Italian translation.

## Castro [2.6.1] - 12.03.2018
### Features
- Updated: Firebase services to improve overhaul performance.

### Fixes
- Fixed: Cutting edges on Translators window.

### Localization
- Added: Portuguese (Portugal) translation.
- Added: Spanish translation.

## Castro [2.6] - 09.03.2018
### Information
- Added [SIM]: New section - SIM.
- Added [SIM]: New categories - General, Primary SIM, Secondary SIM and Default.
- Added [SIM]: General: Phone type, SIM slots count and Unlocked phone.
- Added [SIM]: Default: Internet, Voice and SMS.
- Added [SIM]: Operator name, number, slot index, country ISO, country name, ICC ID, MCC, MNC.
- Added [Memory]: Used RAM memory.
- Added [Memory]: Used Internal memory.
- Added [Memory]: Used External memory.
- Added [Memory]: Used SWAP memory.
- Added [Sensors]: Maximum FIFO events count.
- Added [Sensors]: Reserved FIFO events count.
- Added [Device]: Type of screen.

### Design
- Added: Flags of countries in Translators window.

### Features
- Added: Ability to change more units of measurement in Settings.
- Added: Double SIM support devices support.
- Added: Build number in Feedback window.
- Changed: Minimum android version to 22 (Android Lollipop 5.1).

### Fixes
- Fixed [SIM]: Check for unlocked phone.
- Fixed: PDF report creating features.

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
