[ws1-network](../../index.md)/[com.airwatch.gateway](../index.md)/[IGatewayStatusListener](index.md)/[onError](on-error.md)

# onError

```kotlin
abstract fun onError(errorCode: Int)
```

<div class="api-sig-types" markdown="span">[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)</div>

Callback invoked when a gateway error occurs.

## Parameters

| Name | Description |
|------|-------------|
| errorCode | The error code describing the failure, as defined in GatewayStatusCodes. |
