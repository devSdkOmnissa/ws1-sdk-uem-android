[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[getRestrictionPolicy](get-restriction-policy.md)

# getRestrictionPolicy

```kotlin
open fun getRestrictionPolicy(): RestrictionPolicy
```

<div class="api-sig-types" markdown="span">[RestrictionPolicy](../../com.airwatch.sdk.profile/-restriction-policy/index.md)</div>

Fetches the Restriction Policy as defined at the WS1 UEM Console. 

Access Level = AW_MANAGED (for details on access permission please check [SDKManager](index.md)) 

## Return

RestrictionPolicy object on success. null in case of failure.

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
