[ws1-network](../../index.md)/[com.airwatch.gateway.clients](../index.md)/[AWUrlConnection](index.md)/[openStream](open-stream.md)

# openStream

```kotlin
open fun openStream(url: URL): InputStream
```

<div class="api-sig-types" markdown="span">[URL](https://developer.android.com/reference/kotlin/java/net/URL.html), [InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)</div>

Opens the connection for the given [URL](https://developer.android.com/reference/kotlin/java/net/URL.html) and returns its [InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html). If the proxy-aware connection cannot be established, this falls back to [openStream](https://developer.android.com/reference/kotlin/java/net/URL.html#openstream).

## Parameters

| Name | Description |
|------|-------------|
| url | The [URL](https://developer.android.com/reference/kotlin/java/net/URL.html) to read from. Non-null. |

## Return

A non-null [InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html) for reading the URL contents.

## Throws

| Exception | Condition |
|-----------|-----------|
| [java.io.IOException](https://developer.android.com/reference/kotlin/java/io/IOException.html) | If an I/O error occurs while opening the stream. |
