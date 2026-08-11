[ws1-framework](../../index.md)/[com.airwatch.sdk.context](../index.md)/[SDKContext](index.md)

# SDKContext

```kotlin
abstract class SDKContext
```

SDKContext is the entry point for the SDK. It provides the methods to initialize the SDK, fetch the SDK configuration, fetch the app configuration, and more.

## See also

- com.airwatch.sdk.context.SDKContextImpl

## Functions

| Name | Summary |
|---|---|
| [fetchAndExecuteComplianceSettings](fetch-and-execute-compliance-settings.md) | abstract fun [fetchAndExecuteComplianceSettings](fetch-and-execute-compliance-settings.md)(listener: IFutureSuccessCallback&lt;[Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)&gt;)<br>Initiates compliance settings fetch and executes restrictions and compliance tasks with the new/saved settings payload or clears any compliance related actions if none exists. |
| [fetchAppSettingsWithConfigTypeAndVersion](fetch-app-settings-with-config-type-and-version.md) | abstract fun [fetchAppSettingsWithConfigTypeAndVersion](fetch-app-settings-with-config-type-and-version.md)(listener: [ISdkFetchSettingsListener](../-i-sdk-fetch-settings-listener/index.md), configType: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), configVersion: [String](https://developer.android.com/reference/kotlin/java/lang/String.html))<br>Fetch App settings with given configType and configVersion. |
| [fetchSDKSettings](fetch-s-d-k-settings.md) | abstract fun [fetchSDKSettings](fetch-s-d-k-settings.md)(listener: [ISdkFetchSettingsListener](../-i-sdk-fetch-settings-listener/index.md))<br>Initiates SDK settings fetch. |
| [getAppConfiguration](get-app-configuration.md) | abstract fun [getAppConfiguration](get-app-configuration.md)(): AppConfiguration<br>Return AppConfiguration object with latest SDK configuration. |
| [getCurrentState](get-current-state.md) | abstract fun [getCurrentState](get-current-state.md)(): SDKContext.State<br>Returns the current state of the SDKContextManager. |
| [getKeyManager](get-key-manager.md) | abstract fun [getKeyManager](get-key-manager.md)(): MasterKeyManager<br>Return initialized MasterKeyManager. |
| [getSDKConfiguration](get-s-d-k-configuration.md) | abstract fun [getSDKConfiguration](get-s-d-k-configuration.md)(): SDKConfiguration<br>Return SDKConfiguration object with latest SDK configuration. |
| [init](init.md) | abstract fun [init](init.md)(context: Context)<br>abstract fun [init](init.md)(context: Context, passcode: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-byte/index.html)&gt;)<br>abstract fun [init](init.md)(context: Context, keyManager: MasterKeyManager)<br>Initialize an instance of SDKContextManager. |
