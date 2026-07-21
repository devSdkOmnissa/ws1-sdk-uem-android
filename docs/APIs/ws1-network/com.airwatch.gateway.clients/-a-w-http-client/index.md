[ws1-network](../../index.md)/[com.airwatch.gateway.clients](../index.md)/[AWHttpClient](index.md)

# AWHttpClient

@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)

~~open~~ ~~class~~ [~~AWHttpClient~~](index.md)

Wrapper over org.apache.http.impl.client.DefaultHttpClient that provides IA and tunnelling features. Use AWUrlConnection.

## Constructors

| Name | Description |
|---|---|
| [AWHttpClient](-a-w-http-client.md) | open fun [AWHttpClient](-a-w-http-client.md)(context: Context)<br>Creates a client that tunnels traffic and responds to integrated auth challenges using a user with no domain and password. |
| [AWHttpClient](-a-w-http-client.md) | open fun [AWHttpClient](-a-w-http-client.md)(context: Context, useDomainWithUserCredentials: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html))<br>Creates a client that tunnels traffic and responds to integrated auth challenges using a user and password. |

## Functions

| Name | Summary |
|---|---|
| [executeRequest](execute-request.md) | open fun [executeRequest](execute-request.md)(request: HttpUriRequest): HttpResponse<br>open fun [executeRequest](execute-request.md)(request: HttpUriRequest, context: HttpContext): HttpResponse<br>open fun &lt;[T](execute-request.md)&gt; [executeRequest](execute-request.md)(request: HttpUriRequest, responseHandler: ResponseHandler&lt;? extends T&gt;): [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)<br>open fun &lt;[T](execute-request.md)&gt; [executeRequest](execute-request.md)(request: HttpUriRequest, responseHandler: ResponseHandler&lt;? extends T&gt;, context: HttpContext): [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)<br>Executes the request, handling integrated auth and tunnelling.<br>open fun [executeRequest](execute-request.md)(target: HttpHost, request: HttpRequest): HttpResponse<br>open fun [executeRequest](execute-request.md)(target: HttpHost, request: HttpRequest, context: HttpContext): HttpResponse<br>open fun &lt;[T](execute-request.md)&gt; [executeRequest](execute-request.md)(target: HttpHost, request: HttpRequest, responseHandler: ResponseHandler&lt;? extends T&gt;): [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)<br>open fun &lt;[T](execute-request.md)&gt; [executeRequest](execute-request.md)(target: HttpHost, request: HttpRequest, responseHandler: ResponseHandler&lt;? extends T&gt;, context: HttpContext): [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)<br>Executes the request against the given target, handling integrated auth and tunnelling. |
