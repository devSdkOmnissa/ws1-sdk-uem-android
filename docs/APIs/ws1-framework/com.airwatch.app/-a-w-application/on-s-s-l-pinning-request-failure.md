[ws1-framework](../../index.md)/[com.airwatch.app](../index.md)/[AWApplication](index.md)/[onSSLPinningRequestFailure](on-s-s-l-pinning-request-failure.md)

# onSSLPinningRequestFailure

```kotlin
abstract override fun onSSLPinningRequestFailure(host: String, serverCACert: X509Certificate?)
```

<div class="api-sig-types" markdown="span">[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), [X509Certificate](https://developer.android.com/reference/kotlin/java/security/cert/X509Certificate.html)</div>

Callback for SSL pinning request failure.

## Parameters

| Name | Description |
|------|-------------|
| host | Non-null host name that failed. |
| serverCACert | Nullable server CA certificate. |
