[ws1-framework](../../index.md)/[com.airwatch.sdk.context](../index.md)/[SDKContext](index.md)/[fetchSDKSettings](fetch-s-d-k-settings.md)

# fetchSDKSettings

```kotlin
abstract fun fetchSDKSettings(listener: ISdkFetchSettingsListener)
```

<div class="api-sig-types" markdown="span">[ISdkFetchSettingsListener](../-i-sdk-fetch-settings-listener/index.md)</div>

Initiates SDK settings fetch. The settings will be stored in the database and cached in the SDKContextManager.

## Parameters

| Name | Description |
|------|-------------|
| listener | a callback to be notified when the fetch is completed. |

## Throws

| Exception | Condition |
|-----------|-----------|
| com.airwatch.sdk.context.SDKContextException | if [is not initialized ](index.md). |
