[ws1-network](../../index.md)/[com.airwatch.gateway.clients](../index.md)/[AWOkHttpClient](index.md)/[getProxy](get-proxy.md)

# getProxy

```kotlin
open fun getProxy(proxy: Proxy): Proxy
```

<div class="api-sig-types" markdown="span">[Proxy](https://developer.android.com/reference/kotlin/java/net/Proxy.html)</div>

Returns the proxy to use for OkHttp requests. Currently a no-op that returns the supplied proxy, as proxy configuration is applied at the application level. Retained for API compatibility.

## Parameters

| Name | Description |
|------|-------------|
| proxy | The [Proxy](https://developer.android.com/reference/kotlin/java/net/Proxy.html) passed in by the caller. Nullable. |

## Return

The same [Proxy](https://developer.android.com/reference/kotlin/java/net/Proxy.html) instance that was passed in. Nullable.
