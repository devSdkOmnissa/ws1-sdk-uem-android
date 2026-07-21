[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[getGroupId](get-group-id.md)

# getGroupId

```kotlin
open fun getGroupId(): String
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html)</div>

Retrieves the location group in which the device is currently enrolled. 

Access Level = AW_MANAGED (for details on access permission please check [SDKManager](index.md)) 

## Return

The enrolled location group id. If device is not enrolled returns "AirWatchSDKException Device not enrolled"

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
