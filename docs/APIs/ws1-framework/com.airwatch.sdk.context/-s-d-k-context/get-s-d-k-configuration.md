[ws1-framework](../../index.md)/[com.airwatch.sdk.context](../index.md)/[SDKContext](index.md)/[getSDKConfiguration](get-s-d-k-configuration.md)

# getSDKConfiguration

```kotlin
abstract fun getSDKConfiguration(): SDKConfiguration
```

Return SDKConfiguration object with latest SDK configuration. NOTE:This method will access the database if no configuration present in  cache

## Return

- SDKConfiguration

## Throws

| Exception | Condition |
|-----------|-----------|
| com.airwatch.sdk.context.SDKContextException | if [is not configured ](index.md). |
