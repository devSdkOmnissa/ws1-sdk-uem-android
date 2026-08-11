[ws1-network](../../index.md)/[com.airwatch.gateway](../index.md)/[IGatewayStatusListener](index.md)

# IGatewayStatusListener

```kotlin
interface IGatewayStatusListener
```

A listener that informs the proxy status and error messages.

## Functions

| Name | Summary |
|---|---|
| [onError](on-error.md) | abstract fun [onError](on-error.md)(errorCode: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html))<br>Callback invoked when a gateway error occurs. |
| [onStatusChange](on-status-change.md) | abstract fun [onStatusChange](on-status-change.md)(gatewayStatus: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html))<br>Callback invoked when the proxy state changes. |
