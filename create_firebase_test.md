# Persona
- World-class iOS Developer specializing in Firebase communication.
- Avid user of GoF design patterns.

# Our Goal
- Build a Firebase test app for iOS using a WebView with a TextField and a "Send" Button.
- Do not use CocoaPods or Carthage.
- Do not worry about the Firebase Database, we are only interested in sending a text message.  If we need the Firebase Database to only send a text message, then it will be ok to use it otherwise we do not need it to clutter up our code.

Here is the GoogleService-Info.plist
# GoogleService-Info.plist
```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>API_KEY</key>
	<string>AIzaSyA57VdiDrmAffcwX2ny0NGYE45iPVZU-8w</string>
	<key>GCM_SENDER_ID</key>
	<string>840912674907</string>
	<key>PLIST_VERSION</key>
	<string>1</string>
	<key>BUNDLE_ID</key>
	<string>awm.ios.mcba.visionteamrealestate</string>
	<key>PROJECT_ID</key>
	<string>visionteam-78cf8</string>
	<key>STORAGE_BUCKET</key>
	<string>visionteam-78cf8.appspot.com</string>
	<key>IS_ADS_ENABLED</key>
	<false></false>
	<key>IS_ANALYTICS_ENABLED</key>
	<false></false>
	<key>IS_APPINVITE_ENABLED</key>
	<true></true>
	<key>IS_GCM_ENABLED</key>
	<true></true>
	<key>IS_SIGNIN_ENABLED</key>
	<true></true>
	<key>GOOGLE_APP_ID</key>
	<string>1:840912674907:ios:4ee928e40c1806a4951f7e</string>
</dict>
</plist>
```

# Your Task
Walk me through the steps to create a Firebase test app for iOS using a WebView with a TextField and a "Send" Button.  Use the GoogleService-Info.plist file above for our Firebase project.  Do not use CocoaPods or Carthage.  Do not worry about the Firebase Database, we are only interested in sending a text message.  If we need the Firebase Database to only send a text message, then it will be ok to use it otherwise we do not need it to clutter up our code.