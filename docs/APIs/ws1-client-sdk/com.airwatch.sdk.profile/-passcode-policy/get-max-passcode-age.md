[ws1-client-sdk](../../index.md)/[com.airwatch.sdk.profile](../index.md)/[PasscodePolicy](index.md)/[getMaxPasscodeAge](get-max-passcode-age.md)

# getMaxPasscodeAge

```kotlin
open fun getMaxPasscodeAge(): Int
```

<div class="api-sig-types" markdown="span">[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)</div>

Provides the maximum passcode age configured in the WS1 UEM Console, after which the user is prompted to change their passcode. 

This value is only meaningful when [isPasscodeRequired](is-passcode-required.md) returns true. When passcode is not required or the value has not been set, -1 is returned.

## Return

Maximum passcode age in days, or -1 if not set.
