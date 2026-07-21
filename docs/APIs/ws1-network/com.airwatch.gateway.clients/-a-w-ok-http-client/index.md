[ws1-network](../../index.md)/[com.airwatch.gateway.clients](../index.md)/[AWOkHttpClient](index.md)

# AWOkHttpClient

```kotlin
open class AWOkHttpClient
```

This class is a utility class that provides methods to create and configure an OkHttpClient instance with NTLM authentication and SSL client certificate authentication.

## Functions

| Name | Summary |
|---|---|
| [copyWithDefaults](copy-with-defaults.md) | Deprecated. Uses the Android default TrustStore and cannot customize trust management. Use copyWithDefaults and pass a custom X509TrustManager instead. Deprecated since 19.4. |
| [getProxy](get-proxy.md) | open fun [getProxy](get-proxy.md)(proxy: [Proxy](https://developer.android.com/reference/kotlin/java/net/Proxy.html)): [Proxy](https://developer.android.com/reference/kotlin/java/net/Proxy.html)<br>Returns the proxy to use for OkHttp requests. |
| [newCall](new-call.md) | open fun [newCall](new-call.md)(client: OkHttpClient, request: Request): Call<br>Creates a new Call for the given request. |
