[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[isEnrolled](is-enrolled.md)

# isEnrolled

```kotlin
open fun isEnrolled(): Boolean
```

<div class="api-sig-types" markdown="span">[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)</div>

Determines if the device is currently enrolled in AirWatch. 

Access Level = AW_MANAGED (for details on access permission please check [SDKManager](index.md)) 

## Return

true if the device is currently enrolled, false otherwise

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
