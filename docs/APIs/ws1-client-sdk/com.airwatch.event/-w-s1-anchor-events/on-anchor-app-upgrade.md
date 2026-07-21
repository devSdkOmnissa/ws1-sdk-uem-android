[ws1-client-sdk](../../index.md)/[com.airwatch.event](../index.md)/[WS1AnchorEvents](index.md)/[onAnchorAppUpgrade](on-anchor-app-upgrade.md)

# onAnchorAppUpgrade

```kotlin
abstract fun onAnchorAppUpgrade(context: Context, isUpgrade: Boolean)
```

<div class="api-sig-types" markdown="span">[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)</div>

Method to handle broadcast for Anchor App Upgrade. This broadcast is delayed till subsequent app launch.

## Parameters

| Name | Description |
|------|-------------|
| context | Context object |
| isUpgrade | boolean flag indicating if it is an upgrade or removal of anchor app. |
