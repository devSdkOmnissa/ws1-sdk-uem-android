[ws1-client-sdk](../../index.md)/[com.airwatch.event](../index.md)/[WS1AnchorEvents](index.md)/[onClearAppDataCommandReceived](on-clear-app-data-command-received.md)

# onClearAppDataCommandReceived

```kotlin
abstract fun onClearAppDataCommandReceived(context: Context, reasonCode: ClearReasonCode)
```

<div class="api-sig-types" markdown="span">[ClearReasonCode](../../com.airwatch.sdk.shareddevice/-clear-reason-code/index.md)</div>

Clear app data requested from Workspace ONE SDK. App should perform wipe actions on receiving this callback.

## Parameters

| Name | Description |
|------|-------------|
| context | Application context |
| reasonCode | Reason for which app wipe is requested |

## See also

- [com.airwatch.sdk.shareddevice.ClearReasonCode](../../com.airwatch.sdk.shareddevice/-clear-reason-code/index.md)
