[ws1-network](../../index.md)/[com.airwatch.gateway](../index.md)/[GatewayManager](index.md)/[start](start.md)

# start

```kotlin
open fun start(): Boolean
```

<div class="api-sig-types" markdown="span">[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)</div>

Starts the local proxy based on the configuration provided.

## Return

true if the start request was accepted, false otherwise.

## Throws

| Exception | Condition |
|-----------|-----------|
| GatewayException | If the gateway configuration is invalid. |
