[ws1-network](../../index.md)/[com.airwatch.gateway](../index.md)/[GatewayStatusCodes](index.md)

# GatewayStatusCodes

```kotlin
open class GatewayStatusCodes
```

Status code for gateway initialization and shutdown.

## Properties

| Name | Summary |
|---|---|
| [LOCAL_PORT_UNAVAILABLE](-l-o-c-a-l_-p-o-r-t_-u-n-a-v-a-i-l-a-b-l-e.md) | val [LOCAL_PORT_UNAVAILABLE](-l-o-c-a-l_-p-o-r-t_-u-n-a-v-a-i-l-a-b-l-e.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Error indicating the configured local proxy port is unavailable. |
| [START_PROXY_ERROR_END](-s-t-a-r-t_-p-r-o-x-y_-e-r-r-o-r_-e-n-d.md) | val [START_PROXY_ERROR_END](-s-t-a-r-t_-p-r-o-x-y_-e-r-r-o-r_-e-n-d.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Upper bound of the proxy-start error code range. |
| [START_PROXY_ERROR_START](-s-t-a-r-t_-p-r-o-x-y_-e-r-r-o-r_-s-t-a-r-t.md) | val [START_PROXY_ERROR_START](-s-t-a-r-t_-p-r-o-x-y_-e-r-r-o-r_-s-t-a-r-t.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>A mask value added to all the error codes occurred while starting proxy when they are passed from the proxy to the application. |
| [START_TUNNEL_SERVER_ERROR](-s-t-a-r-t_-t-u-n-n-e-l_-s-e-r-v-e-r_-e-r-r-o-r.md) | val [START_TUNNEL_SERVER_ERROR](-s-t-a-r-t_-t-u-n-n-e-l_-s-e-r-v-e-r_-e-r-r-o-r.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Error indicating the tunnel server failed to start. |
| [STATE_CONFIGURING](-s-t-a-t-e_-c-o-n-f-i-g-u-r-i-n-g.md) | val [STATE_CONFIGURING](-s-t-a-t-e_-c-o-n-f-i-g-u-r-i-n-g.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Status indicating the gateway is being configured. |
| [STATE_ESTABLISHING_CONNECTION](-s-t-a-t-e_-e-s-t-a-b-l-i-s-h-i-n-g_-c-o-n-n-e-c-t-i-o-n.md) | val [STATE_ESTABLISHING_CONNECTION](-s-t-a-t-e_-e-s-t-a-b-l-i-s-h-i-n-g_-c-o-n-n-e-c-t-i-o-n.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Status indicating the gateway is establishing a connection. |
| [STATE_STARTED](-s-t-a-t-e_-s-t-a-r-t-e-d.md) | val [STATE_STARTED](-s-t-a-t-e_-s-t-a-r-t-e-d.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Status indicating the gateway (local proxy) has started. |
| [STATE_STOPPED](-s-t-a-t-e_-s-t-o-p-p-e-d.md) | val [STATE_STOPPED](-s-t-a-t-e_-s-t-o-p-p-e-d.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Status indicating the gateway (local proxy) has stopped. |
| [TUNNEL_DISCONNECTED](-t-u-n-n-e-l_-d-i-s-c-o-n-n-e-c-t-e-d.md) | val [TUNNEL_DISCONNECTED](-t-u-n-n-e-l_-d-i-s-c-o-n-n-e-c-t-e-d.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Status set when tunnel got disconnected. |
| [UNABLE_TO_START_LOCAL_PROXY_SERVICE](-u-n-a-b-l-e_-t-o_-s-t-a-r-t_-l-o-c-a-l_-p-r-o-x-y_-s-e-r-v-i-c-e.md) | val [UNABLE_TO_START_LOCAL_PROXY_SERVICE](-u-n-a-b-l-e_-t-o_-s-t-a-r-t_-l-o-c-a-l_-p-r-o-x-y_-s-e-r-v-i-c-e.md): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Error indicating the local proxy service could not be started. |
