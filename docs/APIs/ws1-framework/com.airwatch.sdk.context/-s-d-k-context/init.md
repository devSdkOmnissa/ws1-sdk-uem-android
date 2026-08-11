[ws1-framework](../../index.md)/[com.airwatch.sdk.context](../index.md)/[SDKContext](index.md)/[init](init.md)

# init

```kotlin
abstract fun init(context: Context)
```

Initialize an instance of SDKContextManager. Key manager required for cipher operation is loaded. A random pass code is used to initialize the key manager.

## Parameters

| Name | Description |
|------|-------------|
| context | - [SDKContext](index.md). |

## Parameters

| Name | Description |
|------|-------------|
| context | - Context. |
| passcode | Initialize key man ager with the given pass code. |

## Parameters

| Name | Description |
|------|-------------|
| context | - Context. |
| keyManager | - MasterKeyManager instance to initialize the SDKContextManager with. |

## Throws

| Exception | Condition |
|-----------|-----------|
| [java.lang.IllegalArgumentException](https://developer.android.com/reference/kotlin/java/lang/IllegalArgumentException.html) | throw this exception if context is null. |

abstract fun [init](init.md)(context: Context, passcode: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-byte/index.html)&gt;)

Initialize an instance of SDKContextManager. Key manager. required for cipher operation is loaded.

## Throws

| Exception | Condition |
|-----------|-----------|
| com.airwatch.sdk.context.SDKContextException | - If unable to initiate SDKKeyManager. |
| [java.lang.IllegalArgumentException](https://developer.android.com/reference/kotlin/java/lang/IllegalArgumentException.html) | throw this exception if context is null. |

abstract fun [init](init.md)(context: Context, keyManager: MasterKeyManager)

Initialize an instance of SDKContextManager. Key manager required for cipher operation is loaded. This method is used when the app wants to have more control over the key manager initialization by providing an instance of MasterKeyManager. This is useful in scenarios where the app wants to use a custom implementation of the key manager or wants to use a specific configuration for the key manager.

## Throws

| Exception | Condition |
|-----------|-----------|
| [java.lang.IllegalArgumentException](https://developer.android.com/reference/kotlin/java/lang/IllegalArgumentException.html) | throw this exception if context or keyManager is null. |
