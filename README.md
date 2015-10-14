# cordova-plugin-android-screens
This Cordova plugin lets you configure the supported screen sizes on Android devices.

## Install (from GitHub)

```
cordova plugin add https://github.com/maxcarl/cordova-plugin-android-screens.git
```

## How to use?

After installing you can customize the plugin.xml to fit your needs:

```xml
<supports-screens        
android:smallScreens="false"
android:largeScreens="true"
android:normalScreens="true" 
android:xlargeScreens="true"/>
```

This example prevents the app to be used on small devices.

## Platforms

Applies to Android only.