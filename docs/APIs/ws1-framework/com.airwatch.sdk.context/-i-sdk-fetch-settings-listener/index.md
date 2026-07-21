[ws1-framework](../../index.md)/[com.airwatch.sdk.context](../index.md)/[ISdkFetchSettingsListener](index.md)

# ISdkFetchSettingsListener

```kotlin
interface ISdkFetchSettingsListener
```

Interface for listening the result of the method fetch sdk settings in SDKContextManager.

## Functions

| Name | Summary |
|---|---|
| [onFailure](on-failure.md) | abstract fun [onFailure](on-failure.md)(taskResult: TaskResult)<br>Called when settings fetch fails. |
| [onSuccess](on-success.md) | abstract fun [onSuccess](on-success.md)(configuration: BaseConfiguration)<br>Called when settings fetch succeeds. |
