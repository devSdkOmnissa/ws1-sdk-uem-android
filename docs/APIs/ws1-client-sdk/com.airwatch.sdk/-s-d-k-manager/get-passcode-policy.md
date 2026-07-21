[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[getPasscodePolicy](get-passcode-policy.md)

# getPasscodePolicy

```kotlin
open fun getPasscodePolicy(): PasscodePolicy
```

<div class="api-sig-types" markdown="span">[PasscodePolicy](../../com.airwatch.sdk.profile/-passcode-policy/index.md)</div>

Get the Passcode Policy that is defined on the WS1 UEM Console. 

Access Level = AW_MANAGED (for details on access permission please check [SDKManager](index.md)) 

## Return

PasscodePolicy object if successful. null value in case of any Error.

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
