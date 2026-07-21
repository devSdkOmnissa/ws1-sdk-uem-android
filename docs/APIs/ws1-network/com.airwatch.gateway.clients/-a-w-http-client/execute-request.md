[ws1-network](../../index.md)/[com.airwatch.gateway.clients](../index.md)/[AWHttpClient](index.md)/[executeRequest](execute-request.md)

# executeRequest

```kotlin
open fun <T> executeRequest(target: HttpHost, request: HttpRequest, responseHandler: ResponseHandler<? extends T>, context: HttpContext): T
```

<div class="api-sig-types" markdown="span">[T](execute-request.md), [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)</div>

Executes the request against the given target, handling integrated auth and tunnelling.

## Parameters

| Name | Description |
|------|-------------|
| target | The HttpHost to execute against. Non-null. |
| request | The HttpRequest to execute. Non-null. |
| responseHandler | The ResponseHandler that processes the response. Non-null. |
| context | The HttpContext for the request. Nullable. |
| &lt;T&gt; | The type produced by the response handler. |

## Parameters

| Name | Description |
|------|-------------|
| target | The HttpHost to execute against. Non-null. |
| request | The HttpRequest to execute. Non-null. |
| responseHandler | The ResponseHandler that processes the response. Non-null. |
| &lt;T&gt; | The type produced by the response handler. |

## Parameters

| Name | Description |
|------|-------------|
| request | The HttpUriRequest to execute. Non-null. |
| responseHandler | The ResponseHandler that processes the response. Non-null. |
| context | The HttpContext for the request. Nullable. |
| &lt;T&gt; | The type produced by the response handler. |

## Parameters

| Name | Description |
|------|-------------|
| request | The HttpUriRequest to execute. Non-null. |
| responseHandler | The ResponseHandler that processes the response. Non-null. |
| &lt;T&gt; | The type produced by the response handler. |

## Parameters

| Name | Description |
|------|-------------|
| request | The HttpUriRequest to execute. Non-null. |

## Parameters

| Name | Description |
|------|-------------|
| request | The HttpUriRequest to execute. Non-null. |
| context | The HttpContext for the request. Nullable. |

## Parameters

| Name | Description |
|------|-------------|
| target | The HttpHost to execute against. Non-null. |
| request | The HttpRequest to execute. Non-null. |

## Parameters

| Name | Description |
|------|-------------|
| target | The HttpHost to execute against. Non-null. |
| request | The HttpRequest to execute. Non-null. |
| context | The HttpContext for the request. Nullable. |

## Return

The non-null result produced by the response handler.

## Return

The non-null result produced by the response handler.

## Return

The non-null result produced by the response handler.

## Return

The non-null result produced by the response handler.

## Return

The non-null HttpResponse.

## Return

The non-null HttpResponse.

## Return

The non-null HttpResponse.

## Return

The non-null HttpResponse.

## Throws

| Exception | Condition |
|-----------|-----------|
| [java.io.IOException](https://developer.android.com/reference/kotlin/java/io/IOException.html) | If the request could not be executed. |

open fun &lt;[T](execute-request.md)&gt; [executeRequest](execute-request.md)(target: HttpHost, request: HttpRequest, responseHandler: ResponseHandler&lt;? extends T&gt;): [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)

Executes the request against the given target, handling integrated auth and tunnelling.

## Throws

| Exception | Condition |
|-----------|-----------|
| [java.io.IOException](https://developer.android.com/reference/kotlin/java/io/IOException.html) | If the request could not be executed. |

open fun &lt;[T](execute-request.md)&gt; [executeRequest](execute-request.md)(request: HttpUriRequest, responseHandler: ResponseHandler&lt;? extends T&gt;, context: HttpContext): [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)

Executes the request, handling integrated auth and tunnelling.

## Throws

| Exception | Condition |
|-----------|-----------|
| [java.io.IOException](https://developer.android.com/reference/kotlin/java/io/IOException.html) | If the request could not be executed. |

open fun &lt;[T](execute-request.md)&gt; [executeRequest](execute-request.md)(request: HttpUriRequest, responseHandler: ResponseHandler&lt;? extends T&gt;): [T](https://developer.android.com/reference/kotlin/java/lang/Enum.html#valueof)

Executes the request, handling integrated auth and tunnelling.

## Throws

| Exception | Condition |
|-----------|-----------|
| [java.io.IOException](https://developer.android.com/reference/kotlin/java/io/IOException.html) | If the request could not be executed. |

open fun [executeRequest](execute-request.md)(request: HttpUriRequest): HttpResponse

Executes the request, handling integrated auth and tunnelling.

## Throws

| Exception | Condition |
|-----------|-----------|
| [java.io.IOException](https://developer.android.com/reference/kotlin/java/io/IOException.html) | If the request could not be executed. |

open fun [executeRequest](execute-request.md)(request: HttpUriRequest, context: HttpContext): HttpResponse

Executes the request, handling integrated auth and tunnelling.

## Throws

| Exception | Condition |
|-----------|-----------|
| [java.io.IOException](https://developer.android.com/reference/kotlin/java/io/IOException.html) | If the request could not be executed. |

open fun [executeRequest](execute-request.md)(target: HttpHost, request: HttpRequest): HttpResponse

Executes the request against the given target, handling integrated auth and tunnelling.

## Throws

| Exception | Condition |
|-----------|-----------|
| [java.io.IOException](https://developer.android.com/reference/kotlin/java/io/IOException.html) | If the request could not be executed. |

open fun [executeRequest](execute-request.md)(target: HttpHost, request: HttpRequest, context: HttpContext): HttpResponse

Executes the request against the given target, handling integrated auth and tunnelling.

## Throws

| Exception | Condition |
|-----------|-----------|
| [java.io.IOException](https://developer.android.com/reference/kotlin/java/io/IOException.html) | If the request could not be executed. |
