[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[isSSOSessionValid](is-s-s-o-session-valid.md)

# isSSOSessionValid

```kotlin
open fun isSSOSessionValid(): Boolean
```

<div class="api-sig-types" markdown="span">[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)</div>

Provides if SSO session valid. 

Access Level = NONE (for details on access permission please check [SDKManager](index.md)) 

## Return

true if the session is available and valid. false if session is not available or expired.

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
