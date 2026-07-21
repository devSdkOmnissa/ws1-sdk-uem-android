[ws1-network](../../index.md)/[com.airwatch.gateway.clients](../index.md)/[AWUrlConnection](index.md)

# AWUrlConnection

```kotlin
open class AWUrlConnection
```

Utility that provides an instance of [URLConnection](https://developer.android.com/reference/kotlin/java/net/URLConnection.html) that supports Integrated Authentication and tunnelling.

## Functions

| Name | Summary |
|---|---|
| [openConnection](open-connection.md) | open fun [openConnection](open-connection.md)(url: [URL](https://developer.android.com/reference/kotlin/java/net/URL.html)): [URLConnection](https://developer.android.com/reference/kotlin/java/net/URLConnection.html)<br>Provides an instance of [HttpsURLConnection](https://developer.android.com/reference/kotlin/javax/net/ssl/HttpsURLConnection.html) to use for Integrated Authentication and tunnelling. |
| [openStream](open-stream.md) | open fun [openStream](open-stream.md)(url: [URL](https://developer.android.com/reference/kotlin/java/net/URL.html)): [InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html)<br>Opens the connection for the given [URL](https://developer.android.com/reference/kotlin/java/net/URL.html) and returns its [InputStream](https://developer.android.com/reference/kotlin/java/io/InputStream.html). |
