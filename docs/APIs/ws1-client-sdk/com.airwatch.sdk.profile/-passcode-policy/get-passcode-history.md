[ws1-client-sdk](../../index.md)/[com.airwatch.sdk.profile](../index.md)/[PasscodePolicy](index.md)/[getPasscodeHistory](get-passcode-history.md)

# getPasscodeHistory

```kotlin
open fun getPasscodeHistory(): Int
```

<div class="api-sig-types" markdown="span">[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)</div>

Provides the passcode history depth configured in the WS1 UEM Console. The device will prevent the user from reusing the most recent N passcodes, where N is this value. 

This value is only meaningful when [isPasscodeRequired](is-passcode-required.md) returns true. When passcode is not required or the value has not been set, -1 is returned.

## Return

Number of previous passcodes that cannot be reused, or -1 if not set.
