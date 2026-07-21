[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[isCompliant](is-compliant.md)

# isCompliant

```kotlin
open fun isCompliant(): Boolean
```

<div class="api-sig-types" markdown="span">[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)</div>

Determines if the device is currently in good standings with the compliance rules. 

Access Level = AW_MANAGED (for details on access permission please check [SDKManager](index.md)) 

## Return

true if the device is compliant. false if the device is not compliant

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
