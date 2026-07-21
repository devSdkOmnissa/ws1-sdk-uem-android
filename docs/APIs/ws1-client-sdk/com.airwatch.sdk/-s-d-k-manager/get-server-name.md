[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[getServerName](get-server-name.md)

# getServerName

```kotlin
open fun getServerName(): String
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html)</div>

Retrieves the server name in which the device is currently enrolled. 

Access Level = AW_MANAGED (for details on access permission please check [SDKManager](index.md)) 

## Return

The server name, usually a DNS name but can be an IP address; a non-empty string when enrolled

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or if binding with Anchor app fails or if empty host name is returned |
