[ws1-network](../../index.md)/[com.airwatch.gateway](../index.md)/[GatewayManager](index.md)/[autoConfigureProxy](auto-configure-proxy.md)

# autoConfigureProxy

```kotlin
open fun autoConfigureProxy()
```

Automatically fetches and applies the gateway proxy configuration, then starts the local proxy. No action is taken if the proxy is already running. Any errors are reported to registered status listeners.
