[ws1-network](../../index.md)/[com.airwatch.gateway.ui](../index.md)/[GatewayBaseActivity](index.md)

# GatewayBaseActivity

```kotlin
open class GatewayBaseActivity
```

Base Activity to be subclassed by activities where tunnelling feature is required. This class manages the proxy's lifecycle from the activities lifecycle methods. This class also notifies the gateway component's lifecycle and errors. For example, if apps would like to trigger their network requests after the SDK's tunnelling is configured, then apps can subclass this class, override the [proxyStatusUpdated](proxy-status-updated.md) method and wait for STATE_STARTED If applications cannot subclass this class, they can use SDKGatewayActivityDelegate as a delegate for all the Activity lifecycle methods.

## Functions

| Name | Summary |
|---|---|
| [isTunnelingEnabled](is-tunneling-enabled.md) | open fun [isTunnelingEnabled](is-tunneling-enabled.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Indicates whether the tunnelling feature is enabled for this activity. |
| [proxyStatusUpdated](proxy-status-updated.md) | open fun [proxyStatusUpdated](proxy-status-updated.md)(proxyStatus: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html))<br>Receives gateway status update status |
