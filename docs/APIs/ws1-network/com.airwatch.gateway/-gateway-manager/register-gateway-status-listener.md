[ws1-network](../../index.md)/[com.airwatch.gateway](../index.md)/[GatewayManager](index.md)/[registerGatewayStatusListener](register-gateway-status-listener.md)

# registerGatewayStatusListener

```kotlin
open fun registerGatewayStatusListener(gatewayStatusListener: IGatewayStatusListener): Boolean
```

<div class="api-sig-types" markdown="span">[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)</div>

Add a status listener for the proxy, if not already registered.

## Parameters

| Name | Description |
|------|-------------|
| gatewayStatusListener | The IGatewayStatusListener to register. Non-null. |

## Return

true if the listener was newly registered, false if it was already registered.

## Throws

| Exception | Condition |
|-----------|-----------|
| GatewayException | If gatewayStatusListener is null. |
