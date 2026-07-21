[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[getCustomSettings](get-custom-settings.md)

# getCustomSettings

```kotlin
open fun getCustomSettings(): String
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html)</div>

Fetches the Custom Settings that are defined for the anchor app i.e., Agent or Workspace. 

Access Level = AW_MANAGED (for details on access permission please check [SDKManager](index.md)) 

## Return

The custom settings as a String

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
