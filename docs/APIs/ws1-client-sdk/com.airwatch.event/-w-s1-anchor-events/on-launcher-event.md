[ws1-client-sdk](../../index.md)/[com.airwatch.event](../index.md)/[WS1AnchorEvents](index.md)/[onLauncherEvent](on-launcher-event.md)

# onLauncherEvent

```kotlin
open fun onLauncherEvent(eventType: String, bundle: Bundle)
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html)</div>

Method to handle broadcast from launcher. 

 The eventType parameter can receive the following values: 

- ANCHOR_APP_CHECK_IN_ERROR
- ANCHOR_APP_CHECK_OUT_ERROR
- LAUNCHER_STATE

 The bundle parameter may contain the following keys: 

- LAUNCHER_STATE (String)
- STATUS_CODE (Integer)
- FAILURE_MESSAGE (String)

## Parameters

| Name | Description |
|------|-------------|
| eventType | Type of event from launcher |
| bundle | Optional bundle with event data. STATUS_CODE is of type Integer. |
