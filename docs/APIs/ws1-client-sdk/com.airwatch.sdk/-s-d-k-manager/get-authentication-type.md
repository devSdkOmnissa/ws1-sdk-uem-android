[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[getAuthenticationType](get-authentication-type.md)

# getAuthenticationType

```kotlin
open fun getAuthenticationType(): Int
```

<div class="api-sig-types" markdown="span">[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)</div>

Get the Authentication Type set in WS1 UEM Console. 

Access Level = AW_MANAGED (for details on access permission please check [SDKManager](index.md)) 

## Return

- 0 if No Authentication required.
- 1 if Username and password based Authentication required.
- 2 if Passcode based Authentication is required.
- -2 If there is an unexpected exception.

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
