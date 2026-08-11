[ws1-framework](../../index.md)/[com.airwatch.sdk.configuration](../index.md)/[AppSettingsContext](index.md)/[getFlags](get-flags.md)

# getFlags

```kotlin
abstract fun getFlags(): AppSettingFlags
```

<div class="api-sig-types" markdown="span">[AppSettingFlags](../-app-setting-flags/index.md)</div>

Returns an instance of [AppSettingFlags](../-app-setting-flags/index.md) that contains all the flags the application needs to communicate with the SDK framework. These flags are in-memory and the app needs to take care of the storage and making it available when the SDK needs it.

## Return

Nullable AppSettingFlags instance or null if not applicable.
