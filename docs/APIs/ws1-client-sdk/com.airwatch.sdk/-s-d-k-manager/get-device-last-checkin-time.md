[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[getDeviceLastCheckinTime](get-device-last-checkin-time.md)

# getDeviceLastCheckinTime

```kotlin
open fun getDeviceLastCheckinTime(): Long
```

<div class="api-sig-types" markdown="span">[Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-long/index.html)</div>

Get the timestamp (in milliseconds) when the last Beacon was successfully sent. 

Access Level = NONE (for details on access permission please check [SDKManager](index.md)) 

## Return

Positive long timestamp of the last successfully sent Beacon; else 0 if not available.

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
