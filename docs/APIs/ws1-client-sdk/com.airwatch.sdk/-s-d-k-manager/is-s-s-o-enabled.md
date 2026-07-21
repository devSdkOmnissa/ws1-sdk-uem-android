[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[isSSOEnabled](is-s-s-o-enabled.md)

# isSSOEnabled

```kotlin
open fun isSSOEnabled(): Boolean
```

<div class="api-sig-types" markdown="span">[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)</div>

Determines if the Single Sign On feature is enabled for the 3rd party application. 

Access Level = NONE (for details on access permission please check [SDKManager](index.md)) 

## Return

true if the feature is enabled or if the requester is a non-AirWatch app; false otherwise.

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
