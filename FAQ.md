## Basics
### What are the system requirements of the program?
Android 4.0.3 (API 15) and above.

### Why are there two Castro apps?
There are two versions of Castro - Basic and Premium. Premium version has extra features, that doesn't available in basic version. The Premium version of Castro is a standalone application.

### What is the difference beetwen Basic and Premium version?
The Premium version enables such features:

* Customisable widget
* Night Mode

We are developing new Premium features for every update. Buy once, get it all!

### What will happen if I will change my device?
When you purchase Castro Premium, in Google Play, it will be assigned to your Google account. If you use the same Google account on a new or factory reset device, you will have access to all previous purchases.


## Permissions
### Network connections (ACCESS_WIFI_STATE, ACCESS_NETWORK_STATE, INTERNET)
Used to connect to Castro analytics servers and to get information Wi-Fi.

### Phone state (READ_PHONE_STATE)
Used to get information about identifiers, like IMEI, IMSI and serial number. Also used to get information about cellular.

### Camera (CAMERA)
Used to get camera properties and camera mods information.

### Storage (WRITE_EXTERNAL_STORAGE, READ_EXTERNAL_STORAGE)
Used to save Castro reports on SD card and read information about internal and external memory.


## Not correct information
### Screen density
Screen density calculation can be wrong. Android can not define your real DPI, because it scales it to the nearest constant (120, 240, 360, 480, or 640).

### Battery capacity
Battery capacity can only be reported for factory default batteries. If the battery was replaced with an extended capacity battery, neither Android or Castro will be able to detect the new capacity.

### External memory
Castro can show similar values for External and Internal memory. It is caused by Android's SD card emulating. On the newer devices Android defines Internal memory as emulated External memory.

### Camera parameters
Camera capabilities may show incorrect information if the manufacturer encoded the wrong values into the Android profile of the device.