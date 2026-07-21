[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[getSDKProfile](get-s-d-k-profile.md)

# getSDKProfile

```kotlin
open fun getSDKProfile(): IBaseConfiguration
```

Returns the SDK profile manager for the current application. 

Access Level = AW_MANAGED (for details on access permission please check [SDKManager](index.md)) 

## Return

IBaseConfiguration instance backed by SDKProfileManager.

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if binding with the Anchor app fails |
