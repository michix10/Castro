# Changelog

- Latest production version: 2.0
- Latest beta version: 2.0 Beta 05

This changelog is for release version of Castro. Changelog for beta version can be found [here](CHANGELOG_BETA.md).

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