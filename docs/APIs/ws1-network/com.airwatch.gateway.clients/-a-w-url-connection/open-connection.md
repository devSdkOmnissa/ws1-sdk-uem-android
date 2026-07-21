[ws1-network](../../index.md)/[com.airwatch.gateway.clients](../index.md)/[AWUrlConnection](index.md)/[openConnection](open-connection.md)

# openConnection

```kotlin
open fun openConnection(url: URL): URLConnection
```

<div class="api-sig-types" markdown="span">[URL](https://developer.android.com/reference/kotlin/java/net/URL.html), [URLConnection](https://developer.android.com/reference/kotlin/java/net/URLConnection.html)</div>

Provides an instance of [HttpsURLConnection](https://developer.android.com/reference/kotlin/javax/net/ssl/HttpsURLConnection.html) to use for Integrated Authentication and tunnelling.

## Parameters

| Name | Description |
|------|-------------|
| url | The [URL](https://developer.android.com/reference/kotlin/java/net/URL.html) to open the connection for. Non-null. |

## Return

A [URLConnection](https://developer.android.com/reference/kotlin/java/net/URLConnection.html) instance for the given URL, or null if url is null or empty.

## Throws

| Exception | Condition |
|-----------|-----------|
| [java.io.IOException](https://developer.android.com/reference/kotlin/java/io/IOException.html) | If an I/O error occurs while opening the connection. |
