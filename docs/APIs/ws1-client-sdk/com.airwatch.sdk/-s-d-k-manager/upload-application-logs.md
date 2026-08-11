[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[uploadApplicationLogs](upload-application-logs.md)

# uploadApplicationLogs

```kotlin
open fun uploadApplicationLogs(): Boolean
```

<div class="api-sig-types" markdown="span">[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)</div>

This method is used to upload the application logs to the anchor app. 

Access Level = NONE (for details on access permission please check [SDKManager](index.md)) 

## Return

boolean; true if the logging fetch process was successfully initiated to the anchor app, false otherwise.

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if binding with the Anchor app fails |
