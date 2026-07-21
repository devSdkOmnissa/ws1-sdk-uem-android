[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[getDeviceSerialId](get-device-serial-id.md)

# getDeviceSerialId

```kotlin
open fun getDeviceSerialId(): String
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html)</div>

Returns the device SERIAL ID. From Android Q only Hub has the permission to read it.

## Return

Non-null string containing the device serial ID. Returns an empty string if the serial ID is unavailable.

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if the API is not available in the Anchor Application, if binding with the Anchor app fails, or if the Anchor app API version is below the required minimum (v10). |
