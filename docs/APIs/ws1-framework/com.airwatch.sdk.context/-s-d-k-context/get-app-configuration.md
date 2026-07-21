[ws1-framework](../../index.md)/[com.airwatch.sdk.context](../index.md)/[SDKContext](index.md)/[getAppConfiguration](get-app-configuration.md)

# getAppConfiguration

```kotlin
abstract fun getAppConfiguration(): AppConfiguration
```

Return AppConfiguration object with latest SDK configuration. NOTE:This method will access the database if no configuration present in  cache

## Return

- AppConfiguration

## Throws

| Exception | Condition |
|-----------|-----------|
| com.airwatch.sdk.context.SDKContextException | if [is not configured ](index.md). |
