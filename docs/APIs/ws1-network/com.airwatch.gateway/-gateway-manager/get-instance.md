[ws1-network](../../index.md)/[com.airwatch.gateway](../index.md)/[GatewayManager](index.md)/[getInstance](get-instance.md)

# getInstance

```kotlin
open fun getInstance(context: Context): GatewayManager
```

<div class="api-sig-types" markdown="span">[GatewayManager](index.md)</div>

Retrieve the singleton instance of [GatewayManager](index.md).

## Parameters

| Name | Description |
|------|-------------|
| context | The application Context used to initialize the manager. Non-null. |

## Return

Non-null singleton com.airwatch.gateway.GatewayManager instance.

## Throws

| Exception | Condition |
|-----------|-----------|
| GatewayException | If context is null and mGatewayManager is null. |
