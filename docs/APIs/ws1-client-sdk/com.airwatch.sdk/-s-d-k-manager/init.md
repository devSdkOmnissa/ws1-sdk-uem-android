[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[init](init.md)

# init

```kotlin
open fun init(context: Context): SDKManager
```

<div class="api-sig-types" markdown="span">[SDKManager](index.md)</div>

Initializes the WS1 SDK. This should be the first API to be called to do the binding with WS1 MDM Agent. This is a Blocking call, so should not be made on a UI thread.

## Parameters

| Name | Description |
|------|-------------|
| context | Requires Application Context |

## Return

SDKManager singleton instance on successful initialization. null in case of failure.

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if connection with anchor application fails |
