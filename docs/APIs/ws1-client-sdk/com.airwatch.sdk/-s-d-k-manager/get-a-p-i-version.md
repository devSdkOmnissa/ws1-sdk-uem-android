[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[getAPIVersion](get-a-p-i-version.md)

# getAPIVersion

```kotlin
open fun getAPIVersion(): Int
```

<div class="api-sig-types" markdown="span">[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)</div>

Retrieves the revision level of the WS1 SDK. 

Access Level = NONE (for details on access permission please check [SDKManager](index.md)) 

 This method is provided for debugging version mismatch issues.

## Return

The WS1 SDK revision level

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if errors occurs while connecting with Anchor app |
