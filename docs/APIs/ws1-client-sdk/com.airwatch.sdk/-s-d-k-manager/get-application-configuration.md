[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[getApplicationConfiguration](get-application-configuration.md)

# getApplicationConfiguration

```kotlin
open fun getApplicationConfiguration(): Bundle
```

 Fetches key-value pair configuration set for the application in the console. 

 Note: Not to be confused with SDK Profile

## Return

configuration Settings for the caller application.

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
