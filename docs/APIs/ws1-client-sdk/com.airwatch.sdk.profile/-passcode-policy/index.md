[ws1-client-sdk](../../index.md)/[com.airwatch.sdk.profile](../index.md)/[PasscodePolicy](index.md)

# PasscodePolicy

```kotlin
open class PasscodePolicy
```

Provides information about Passcode policy set in console. This includes details around passcode age complexity and other related requirements 

 Information can be fetched from anchor application using [getPasscodePolicy](../../com.airwatch.sdk/-s-d-k-manager/get-passcode-policy.md) . 

 Example Usage 

```java
//Initializes Workspace ONE SDK and connects with anchor application if it is available.
SDKManager sdkManager = SDKManager.init(context);
//Checks enrollment status
if(sdkManager.isEnrolled()){
  //Fetch policy from enrolled anchor application.
  PasscodePolicy profile = sdkManager.getPasscodePolicy();
}
```

## Functions

| Name | Summary |
|---|---|
| [getMaxPasscodeAge](get-max-passcode-age.md) | open fun [getMaxPasscodeAge](get-max-passcode-age.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Provides the maximum passcode age configured in the WS1 UEM Console, after which the user is prompted to change their passcode. |
| [getMinComplexChars](get-min-complex-chars.md) | open fun [getMinComplexChars](get-min-complex-chars.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Provides the minimum number of complex (non-alphanumeric) characters required in the passcode, as configured in the WS1 Console. |
| [getMinPasscodeLength](get-min-passcode-length.md) | open fun [getMinPasscodeLength](get-min-passcode-length.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Provides the minimum passcode length configured in the WS1 Console. |
| [getPasscodeHistory](get-passcode-history.md) | open fun [getPasscodeHistory](get-passcode-history.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Provides the passcode history depth configured in the WS1 UEM Console. |
| [getPassscodeComplexity](get-passscode-complexity.md) | open fun [getPassscodeComplexity](get-passscode-complexity.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Returns flag value indicating if Passcode Complexity is specified in the Console |
| [isPasscodeRequired](is-passcode-required.md) | open fun [isPasscodeRequired](is-passcode-required.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Returns flag value indicating if Passcode requirement is specified in the WS1 Console. |
