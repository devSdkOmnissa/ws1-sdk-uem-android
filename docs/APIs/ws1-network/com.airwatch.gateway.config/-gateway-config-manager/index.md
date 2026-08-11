[ws1-network](../../index.md)/[com.airwatch.gateway.config](../index.md)/[GatewayConfigManager](index.md)

# GatewayConfigManager

```kotlin
open class GatewayConfigManager
```

Provides configuration information about gateway settings - standard proxy etc.

## Functions

| Name | Summary |
|---|---|
| [getAppTunnelType](get-app-tunnel-type.md) | open fun [getAppTunnelType](get-app-tunnel-type.md)(): ProxySetupType<br>Returns the configured app tunnel setup type. |
| [getContext](get-context.md) | open fun [getContext](get-context.md)(): Context<br>Returns the Context associated with this manager. |
| [getDeviceServicesUrl](get-device-services-url.md) | open fun [getDeviceServicesUrl](get-device-services-url.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Returns the configured Device Services URL. |
| [getDeviceUid](get-device-uid.md) | open fun [getDeviceUid](get-device-uid.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Returns the device unique identifier, fetching it once and caching it. |
| [getInstance](get-instance.md) | open fun [getInstance](get-instance.md)(): [GatewayConfigManager](index.md)<br>Returns the already-initialized singleton [GatewayConfigManager](index.md). |
| [getLocalProxyPort](get-local-proxy-port.md) | open fun [getLocalProxyPort](get-local-proxy-port.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Returns the local proxy port from the current configuration. |
| [getPackageName](get-package-name.md) | open fun [getPackageName](get-package-name.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Returns the host application's package name. |
| [getPacV2RoutingMode](get-pac-v2-routing-mode.md) | open fun [getPacV2RoutingMode](get-pac-v2-routing-mode.md)(): PacV2RoutingMode<br>This API is used to get the PAC Mode set in the KVP for PAC V2 |
| [getProxyConfig](get-proxy-config.md) | open fun [getProxyConfig](get-proxy-config.md)(): BaseGatewayConfig<br>Returns the currently stored proxy configuration. |
| [getString](get-string.md) | open fun [getString](get-string.md)(resId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Returns the localized string for the given resource id. |
| [getUseLegacySettings](get-use-legacy-settings.md) | open fun [getUseLegacySettings](get-use-legacy-settings.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Indicates whether legacy proxy settings should be used. |
| [getWebView](get-web-view.md) | open fun [getWebView](get-web-view.md)(): WebView<br>Returns the WebView currently associated with this manager, if any. |
| [hasValidConfig](has-valid-config.md) | open fun [hasValidConfig](has-valid-config.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Indicates whether a valid proxy configuration is currently loaded. |
| [init](init.md) | open fun [init](init.md)(context: Context): [GatewayConfigManager](index.md)<br>Initializes and returns the singleton [GatewayConfigManager](index.md). |
| [isAppTunnelEnabled](is-app-tunnel-enabled.md) | open fun [isAppTunnelEnabled](is-app-tunnel-enabled.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Indicates whether app tunnelling is enabled in the current configuration. |
| [isConfigChanged](is-config-changed.md) | open fun [isConfigChanged](is-config-changed.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Indicates whether the configuration has changed since it was last applied. |
| [isPacV2Enabled](is-pac-v2-enabled.md) | open fun [isPacV2Enabled](is-pac-v2-enabled.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>This API is used to check whether PacV2 is enabled via the KVP PAC URL |
| [isStdEnabled](is-std-enabled.md) | open fun [isStdEnabled](is-std-enabled.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Indicates whether the standard (basic username/password) proxy setup is enabled. |
| [isTunnelSdkEnabled](is-tunnel-sdk-enabled.md) | open fun [isTunnelSdkEnabled](is-tunnel-sdk-enabled.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Indicates whether the Tunnel SDK proxy setup is enabled. |
