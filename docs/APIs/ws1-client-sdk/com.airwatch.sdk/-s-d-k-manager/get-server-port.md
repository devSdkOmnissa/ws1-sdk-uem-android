[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[getServerPort](get-server-port.md)

# getServerPort

```kotlin
open fun getServerPort(): Int
```

<div class="api-sig-types" markdown="span">[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)</div>

Retrieves the port number in which the device is currently enrolled. 

Access Level = AW_MANAGED (for details on access permission please check [SDKManager](index.md)) 

## Return

The port number. Or -1 if no specific port number is attached or if it is default http or https port. Also returns -1 if app is not enrolled.

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
