[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[getSharedDeviceStatus](get-shared-device-status.md)

# getSharedDeviceStatus

```kotlin
open fun getSharedDeviceStatus(): SharedDeviceStatus
```

<div class="api-sig-types" markdown="span">[SharedDeviceStatus](../../com.airwatch.sdk.shareddevice/-shared-device-status/index.md)</div>

Fetches the SharedDevice status of the current device 

Access Level = AW_MANAGED (for details on access permission please check [SDKManager](index.md)) 

## Return

the SharedDeviceStaus object containing the status

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
