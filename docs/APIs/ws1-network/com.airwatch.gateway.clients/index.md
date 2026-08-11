[ws1-network](../index.md)/[com.airwatch.gateway.clients](index.md)

# Package com.airwatch.gateway.clients

## Types

| Name | Summary |
|---|---|
| [AWAuthInterceptor](-a-w-auth-interceptor/index.md) | open class [AWAuthInterceptor](-a-w-auth-interceptor/index.md)<br>An HttpRequestInterceptor instance for the Default Apache HTTPClient that handles NTLM and Basic authentication. |
| [AWCertAuthUtil](-a-w-cert-auth-util/index.md) | class [AWCertAuthUtil](-a-w-cert-auth-util/index.md)<br>Utility class for AW TLS/SSL Client Cert Authentication for various HTTP Clients. |
| [AWHttpClient](-a-w-http-client/index.md) | @[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)<br>~~open~~ ~~class~~ [~~AWHttpClient~~](-a-w-http-client/index.md)<br>Wrapper over org.apache.http.impl.client. |
| [AWOkHttpAuthenticator](-a-w-ok-http-authenticator/index.md) | open class [AWOkHttpAuthenticator](-a-w-ok-http-authenticator/index.md)<br>An Authenticator implementation that provides NTLM auth support with WS1 enrollment credentials. |
| [AWOkHttpClient](-a-w-ok-http-client/index.md) | open class [AWOkHttpClient](-a-w-ok-http-client/index.md)<br>This class is a utility class that provides methods to create and configure an OkHttpClient instance with NTLM authentication and SSL client certificate authentication. |
| [AWUrlConnection](-a-w-url-connection/index.md) | open class [AWUrlConnection](-a-w-url-connection/index.md)<br>Utility that provides an instance of [URLConnection](https://developer.android.com/reference/kotlin/java/net/URLConnection.html) that supports Integrated Authentication and tunnelling. |
| [AWWebView](-a-w-web-view/index.md) | open class [AWWebView](-a-w-web-view/index.md)<br>A Wrapper over the Android's android.webkit. |
| [AWWebViewClient](-a-w-web-view-client/index.md) | open class [AWWebViewClient](-a-w-web-view-client/index.md)<br>An implementation of android.webkit. |
| [NtlmHttpURLConnection](-ntlm-http-u-r-l-connection/index.md) | open class [NtlmHttpURLConnection](-ntlm-http-u-r-l-connection/index.md)<br>Decorator class for NTLM authentication using WS1 Enrollment credentials Using the constructor that takes in the Activity Context will make this implementation handle re-authentication prompts - i.e., if the user's AD credentials changes (due to a periodic change) then this implementation will prompt the user to enter the new password. |
