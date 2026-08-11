[ws1-network](../../index.md)/[com.airwatch.gateway](../index.md)/[IGatewayStatusListener](index.md)/[onStatusChange](on-status-change.md)

# onStatusChange

```kotlin
abstract fun onStatusChange(gatewayStatus: Int)
```

<div class="api-sig-types" markdown="span">[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)</div>

Callback invoked when the proxy state changes.

## Parameters

| Name | Description |
|------|-------------|
| gatewayStatus | The new gateway status code, as defined in GatewayStatusCodes. |
