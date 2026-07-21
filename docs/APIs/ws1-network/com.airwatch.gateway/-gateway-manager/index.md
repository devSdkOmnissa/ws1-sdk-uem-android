[ws1-network](../../index.md)/[com.airwatch.gateway](../index.md)/[GatewayManager](index.md)

# GatewayManager

```kotlin
open class GatewayManager
```

Provides APIs to configure the application for tunnelling (by starting/stopping the internal proxy tunnel). It can also be used to register listeners to be notified of the gateway configuration status.

## Functions

| Name | Summary |
|---|---|
| [autoConfigureProxy](auto-configure-proxy.md) | open fun [autoConfigureProxy](auto-configure-proxy.md)()<br>Automatically fetches and applies the gateway proxy configuration, then starts the local proxy. |
| [getContext](get-context.md) | open fun [getContext](get-context.md)(): Context<br>Returns the application context used to initialize the [GatewayManager](index.md). |
| [getInstance](get-instance.md) | open fun [getInstance](get-instance.md)(context: Context): [GatewayManager](index.md)<br>Retrieve the singleton instance of [GatewayManager](index.md). |
| [getSdkException](get-sdk-exception.md) | open fun [getSdkException](get-sdk-exception.md)(): AirWatchSDKException<br>Returns the SDK exception that occurred and was saved during tunnel setup. |
| [isRunning](is-running.md) | open fun [isRunning](is-running.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Indicates whether the local proxy is currently running. |
| [loadConfiguration](load-configuration.md) | open fun [loadConfiguration](load-configuration.md)(configuration: BaseGatewayConfig): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Validate and load the proxy configuration. |
| [registerGatewayStatusListener](register-gateway-status-listener.md) | open fun [registerGatewayStatusListener](register-gateway-status-listener.md)(gatewayStatusListener: IGatewayStatusListener): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Add a status listener for the proxy, if not already registered. |
| [start](start.md) | open fun [start](start.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Starts the local proxy based on the configuration provided. |
| [startTunnel](start-tunnel.md) | open fun [startTunnel](start-tunnel.md)()<br>Starts the Tunnel SDK and, once it is running, starts the local proxy. |
| [stop](stop.md) | open fun [stop](stop.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Stops the local proxy. |
| [stopTunnel](stop-tunnel.md) | open fun [stopTunnel](stop-tunnel.md)()<br>Stops the Tunnel SDK and resets the tunnel configuration. |
| [unregisterGatewayStatusListener](unregister-gateway-status-listener.md) | open fun [unregisterGatewayStatusListener](unregister-gateway-status-listener.md)(gatewayStatusListener: IGatewayStatusListener): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Remove a status listener for the proxy, if registered. |
