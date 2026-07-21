[ws1-client-sdk](../../index.md)/[com.airwatch.sdk.profile](../index.md)/[PasscodePolicy](index.md)/[isPasscodeRequired](is-passcode-required.md)

# isPasscodeRequired

```kotlin
open fun isPasscodeRequired(): Boolean
```

<div class="api-sig-types" markdown="span">[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)</div>

Returns flag value indicating if Passcode requirement is specified in the WS1 Console.

## Return

true if the passcode is required. false if passcode is not required and all the other methods return values will be -1.
