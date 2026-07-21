[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[refreshBinding](refresh-binding.md)

# refreshBinding

```kotlin
open fun refreshBinding(context: Context): SDKManager
```

<div class="api-sig-types" markdown="span">[SDKManager](index.md)</div>

Refreshes the binding of WS1 SDK, when Workspace is installed/removed. This is a Blocking call, so should not be made on a UI thread.

## Parameters

| Name | Description |
|------|-------------|
| context | Requires Application Context |

## Return

SDKManager singleton instance on successful initialization, and null in case of failure.

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if error occurs while initialization of SDK |

## See also

- [com.airwatch.sdk.SDKManager](deinit.md)
