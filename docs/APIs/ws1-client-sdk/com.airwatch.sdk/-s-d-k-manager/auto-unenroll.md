[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[autoUnenroll](auto-unenroll.md)

# autoUnenroll

```kotlin
open fun autoUnenroll(): Boolean
```

<div class="api-sig-types" markdown="span">[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)</div>

UnEnrolls the application silently if agent is enrolled. 

Access Level = AW_WHITELISTED (for details on access permission please check [SDKManager](index.md)) 

## Return

- true if the UnEnrollment is success.
- false if UnEnrollment failed

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
