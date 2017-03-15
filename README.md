### Gradle APK Verification

#### Instructions

Include this in your app-level gradle file:
```
apply from: "http://demo.hanekedesign.com/Android/apkverification.gradle"
```

Create an app-level ```gradle.properties``` file with the following contents:
```
KEYTOOL_LOCATION = "Applications/Android Studio.app/Contents/jre/jdk/Contents/Home/bin"
KEYSTORE_LOCATION = "/Users/nthunem/AndroidStudioApplications/Northland-Church/northland_keystore.jks"
APK_LOCATION = "/Users/nthunem/AndroidStudioApplications/Northland-Church/app/app-release.apk"
ALIAS = "<your-alias>"
PASSWORD = "<your-password>"
```
#### NOTE: variable names must not change.
