[ws1-network](../../index.md)/[com.airwatch.gateway.clients](../index.md)/[AWWebView](index.md)

# AWWebView

```kotlin
open class AWWebView
```

A Wrapper over the Android's android.webkit.WebView instance that provides Integrated Authentication, Copy-paste restriction and tunnelling features.

## Functions

| Name | Summary |
|---|---|
| [cleanUp](clean-up.md) | open fun [cleanUp](clean-up.md)()<br>Cleans up the proxy configuration and headers. |
| [loadUrl](load-url.md) | open fun [loadUrl](load-url.md)(url: [String](https://developer.android.com/reference/kotlin/java/lang/String.html))<br>Loads the given URL after ensuring proxy/tunnelling client setup is initialized when tunnelling is enabled. |
| [reload](reload.md) | open fun [reload](reload.md)()<br>Reloads the current URL after ensuring proxy/tunnelling client setup is initialized when tunnelling is enabled. |
