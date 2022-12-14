# Beacon

Help scout mobile SDK implementation for Flutter

## Overview

This plugin implements Help Scout official native SDK [Learn more](https://developer.helpscout.com/beacon-2/)


### Requirements
#### For Android
- `minSDKVersion`: 21(Android 5.0) or later
- `compiledSDK`: 29(Android 10)
- Java 8 feature support
- Beacon needs [Internet support](https://developer.android.com/training/basics/network-ops/connecting)
[Learn more ](https://developer.helpscout.com/beacon-2/android/)

#### iOS

*Note:* For this plugin to work, set your `minimum deployment target` to `iOS 11.0`
Add the following permission to your `info.plist ` file (Optional)
- `NSPhotoLibraryUsageDescription`
- `NSCameraUsageDescription`
- `NSMicrophoneUsageDescription`
- `NSPhotoLibraryAddUsageDescription`



![Image](https://github.com/helpscout/HSAttachmentPicker/raw/master/picker_photos_permissions.png)

### Getting started
Setup beacon with your `Beacon ID` and user's email address and name (optional)
```
    final Beacon _beacon = Beacon(
                             beaconId: "XXX-XXX-XXX-XXXX-XXX",
                             email: "example@gmail.com",
                             name: "John Doe");

```
 
Launch beacon by calling `_beacon.open()` method
```
`_beacon.open();`
```
# help_scout_nullsafety
