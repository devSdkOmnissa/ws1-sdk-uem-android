[ws1-client-sdk](../../index.md)/[com.airwatch.sdk.profile](../index.md)/[PasscodePolicy](index.md)/[getMinPasscodeLength](get-min-passcode-length.md)

# getMinPasscodeLength

```kotlin
open fun getMinPasscodeLength(): Int
```

<div class="api-sig-types" markdown="span">[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)</div>

Provides the minimum passcode length configured in the WS1 Console. 

This value is only meaningful when [isPasscodeRequired](is-passcode-required.md) returns true. When passcode is not required or the value has not been set, -1 is returned.

## Return

Minimum number of characters required in the passcode, or -1 if not set.
