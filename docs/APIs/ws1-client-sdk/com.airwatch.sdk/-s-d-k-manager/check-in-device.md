[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[checkInDevice](check-in-device.md)

# checkInDevice

```kotlin
open fun checkInDevice(): Int
```

<div class="api-sig-types" markdown="span">[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)</div>

Used to checkin the device. This rolls back the device to the parent organization group. 

Access Level = AW_MANAGED (for details on access permission please check [SDKManager](index.md)) 

## Return

The status of the operation

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
