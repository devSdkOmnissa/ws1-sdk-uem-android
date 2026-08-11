[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[getSDKProfileJSONString](get-s-d-k-profile-j-s-o-n-string.md)

# getSDKProfileJSONString

```kotlin
open fun getSDKProfileJSONString(): String
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html)</div>

Returns the SDK profile as a JSON string from the Anchor app. 

Access Level = AW_MANAGED (for details on access permission please check [SDKManager](index.md)) 

## Return

SDK profile JSON; empty string if unavailable or on remote error.

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if binding with the Anchor app fails |
