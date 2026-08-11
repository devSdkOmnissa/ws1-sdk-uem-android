[ws1-framework](../../index.md)/[com.airwatch.sdk.context](../index.md)/[SDKContext](index.md)/[fetchAppSettingsWithConfigTypeAndVersion](fetch-app-settings-with-config-type-and-version.md)

# fetchAppSettingsWithConfigTypeAndVersion

```kotlin
abstract fun fetchAppSettingsWithConfigTypeAndVersion(listener: ISdkFetchSettingsListener, configType: String, configVersion: String)
```

<div class="api-sig-types" markdown="span">[ISdkFetchSettingsListener](../-i-sdk-fetch-settings-listener/index.md), [String](https://developer.android.com/reference/kotlin/java/lang/String.html)</div>

Fetch App settings with given configType and configVersion. Pass null for default config version

## Throws

| Exception | Condition |
|-----------|-----------|
| com.airwatch.sdk.context.SDKContextException | if [is not initialized ](index.md). |
