[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[getConsoleVersion](get-console-version.md)

# getConsoleVersion

```kotlin
open fun getConsoleVersion(): Float
```

<div class="api-sig-types" markdown="span">[Float](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-float/index.html)</div>

Provides console version to which device is connected. 

Access Level = NONE (for details on access permission please check [SDKManager](index.md)) 

## Return

console version in decimal format, 0.0 if console version is unavailable

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
