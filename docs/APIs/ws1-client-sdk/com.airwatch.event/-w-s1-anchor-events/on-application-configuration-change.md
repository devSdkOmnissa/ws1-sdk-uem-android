[ws1-client-sdk](../../index.md)/[com.airwatch.event](../index.md)/[WS1AnchorEvents](index.md)/[onApplicationConfigurationChange](on-application-configuration-change.md)

# onApplicationConfigurationChange

```kotlin
abstract fun onApplicationConfigurationChange(applicationConfiguration: Bundle, context: Context)
```

App should override and implement this method to receive application configuration changes from console.

## Parameters

| Name | Description |
|------|-------------|
| applicationConfiguration | New application configuration defined in console |
| context | Application context |

## See also

- [com.airwatch.sdk.SDKManager](../../com.airwatch.sdk/-s-d-k-manager/get-application-configuration.md)
