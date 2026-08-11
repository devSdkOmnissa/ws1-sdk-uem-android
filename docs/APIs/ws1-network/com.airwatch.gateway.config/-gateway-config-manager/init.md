[ws1-network](../../index.md)/[com.airwatch.gateway.config](../index.md)/[GatewayConfigManager](index.md)/[init](init.md)

# init

```kotlin
open fun init(context: Context): GatewayConfigManager
```

<div class="api-sig-types" markdown="span">[GatewayConfigManager](index.md)</div>

Initializes and returns the singleton [GatewayConfigManager](index.md).

## Parameters

| Name | Description |
|------|-------------|
| context | The application Context used for initialization. Non-null. |

## Return

Non-null singleton [GatewayConfigManager](index.md) instance.

## Throws

| Exception | Condition |
|-----------|-----------|
| GatewayException | If context is null and no instance exists yet. |
