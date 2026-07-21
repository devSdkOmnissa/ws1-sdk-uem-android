[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[performSharedDeviceOperation](perform-shared-device-operation.md)

# performSharedDeviceOperation

```kotlin
open fun performSharedDeviceOperation(bundle: Bundle, resultReceiver: ResultReceiver)
```

Performs shared device operations such as checkout,checkin etc.

## Parameters

| Name | Description |
|------|-------------|
| bundle | Specifies the shared device operation type. Must be one of the operation type specified in [SharedDeviceOperations](../../com.airwatch.sdk.shareddevice/-shared-device-operations/index.md) |
| resultReceiver | A callback for providing the result for the operation |

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
