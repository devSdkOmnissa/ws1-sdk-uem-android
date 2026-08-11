[ws1-client-sdk](../../index.md)/[com.airwatch.sdk.profile](../index.md)/[PasscodePolicy](index.md)/[getMinComplexChars](get-min-complex-chars.md)

# getMinComplexChars

```kotlin
open fun getMinComplexChars(): Int
```

<div class="api-sig-types" markdown="span">[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)</div>

Provides the minimum number of complex (non-alphanumeric) characters required in the passcode, as configured in the WS1 Console. 

This value is only meaningful when [isPasscodeRequired](is-passcode-required.md) returns true. When passcode is not required or the value has not been set, -1 is returned.

## Return

Minimum number of complex characters required, or -1 if not set.
