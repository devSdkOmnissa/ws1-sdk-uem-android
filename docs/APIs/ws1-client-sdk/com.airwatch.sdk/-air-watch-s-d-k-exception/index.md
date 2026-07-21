[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[AirWatchSDKException](index.md)

# AirWatchSDKException

```kotlin
open class AirWatchSDKException : Exception
```

<div class="api-sig-types" markdown="span">[Exception](https://developer.android.com/reference/kotlin/java/lang/Exception.html)</div>

AirWatchSDKException is a custom Exception defined by WS1. When the AirWatchSDKManger APIs result in any issues like Connectivity, binding etc this Exception is thrown with appropriate reason from [SDKStatusCode](../-s-d-k-status-code/index.md).

## Constructors

| Name | Description |
|---|---|
| [AirWatchSDKException](-air-watch-s-d-k-exception.md) | open fun [AirWatchSDKException](-air-watch-s-d-k-exception.md)(error: [SDKStatusCode](../-s-d-k-status-code/index.md))<br>WS1 SDK Exception Constructor |
