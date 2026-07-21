[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[AirWatchSDKBroadcastReceiver](index.md)

# AirWatchSDKBroadcastReceiver

```kotlin
open class AirWatchSDKBroadcastReceiver : AbstractSDKBroadcastReceiver
```

Broadcast receiver to get callback on events like OG change , Auto Enrollment complete and wipe. 

 Register this receiver in AndroidManifest.xml file to receive broadcast intents sent from Anchor app. Replace applicationId with package ID of the application. 

```xml
<uses-permission android:name="com.airwatch.sdk.BROADCAST"/>
 <receiver android:name="com.airwatch.sdk.AirWatchSDKBroadcastReceiver"
            android:permission="com.airwatch.sdk.BROADCAST">
            <intent-filter>
                <action android:name="${applicationId}.airwatchsdk.BROADCAST"/>
            </intent-filter>
  </receiver>
```

The broadcast intents are received by AbstractSDKBroadcastReceiver and then processed by [com.airwatch.event.WS1AnchorEvents](../../com.airwatch.event/-w-s1-anchor-events/index.md). [com.airwatch.event.WS1AnchorEvents](../../com.airwatch.event/-w-s1-anchor-events/index.md) provides callbacks which can be overriden to provide custom functionalities for these broadcast intents.
