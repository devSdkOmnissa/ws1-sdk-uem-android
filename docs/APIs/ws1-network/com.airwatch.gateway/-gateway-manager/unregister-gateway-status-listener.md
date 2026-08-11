[ws1-network](../../index.md)/[com.airwatch.gateway](../index.md)/[GatewayManager](index.md)/[unregisterGatewayStatusListener](unregister-gateway-status-listener.md)

# unregisterGatewayStatusListener

```kotlin
open fun unregisterGatewayStatusListener(gatewayStatusListener: IGatewayStatusListener): Boolean
```

<div class="api-sig-types" markdown="span">[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)</div>

Remove a status listener for the proxy, if registered.

## Parameters

| Name | Description |
|------|-------------|
| gatewayStatusListener | The IGatewayStatusListener to unregister. Non-null. |

## Return

true if the listener was removed, false if it was not registered.

## Throws

| Exception | Condition |
|-----------|-----------|
| GatewayException | If gatewayStatusListener is null. |
