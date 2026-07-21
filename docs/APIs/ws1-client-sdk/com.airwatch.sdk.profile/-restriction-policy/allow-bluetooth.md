[ws1-client-sdk](../../index.md)/[com.airwatch.sdk.profile](../index.md)/[RestrictionPolicy](index.md)/[allowBluetooth](allow-bluetooth.md)

# allowBluetooth

```kotlin
open fun allowBluetooth(): Boolean
```

<div class="api-sig-types" markdown="span">[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)</div>

Retrieve application restriction information for use of Bluetooth. If the device restriction prohibits the use of Bluetooth, it takes precedence over the application setting.

## Return

true if bluetooth is prohibited. false if bluetooth is allowed.
