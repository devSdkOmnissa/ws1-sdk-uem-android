[ws1-network](../../index.md)/[com.airwatch.gateway.clients](../index.md)/[AWOkHttpClient](index.md)/[copyWithDefaults](copy-with-defaults.md)

# copyWithDefaults

@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)

~~open~~ ~~fun~~ [~~copyWithDefaults~~](copy-with-defaults.md)~~(~~~~client~~~~:~~ ~~OkHttpClient~~~~)~~~~:~~ ~~OkHttpClient~~

Builds a new instance of OkHttpClient from the one passed in and sets the authenticator and SSLSocketFactory instances. The authenticator is to support NTLM auth and the SSLSocketFactory takes care of SSL Client cert auth. This method uses the Android default TrustStore for SSL trust management.

## Deprecated

Uses the Android default TrustStore and cannot customize trust management. Use [copyWithDefaults](copy-with-defaults.md) and pass a custom [X509TrustManager](https://developer.android.com/reference/kotlin/javax/net/ssl/X509TrustManager.html) instead. Deprecated since 19.4.

## Deprecated

Uses the Android default TrustStore and cannot customize trust management. Use copyWithDefaults and pass a custom [X509TrustManager](https://developer.android.com/reference/kotlin/javax/net/ssl/X509TrustManager.html) instead. Deprecated since 19.4.

## Parameters

| Name | Description |
|------|-------------|
| client | The OkHttpClient to copy and configure. Non-null. |

@[Deprecated](https://developer.android.com/reference/kotlin/java/lang/Deprecated.html)

~~open~~ ~~fun~~ [~~copyWithDefaults~~](copy-with-defaults.md)~~(~~~~context~~~~:~~ ~~Context~~~~,~~ ~~client~~~~:~~ ~~OkHttpClient~~~~)~~~~:~~ ~~OkHttpClient~~

Builds a new instance of OkHttpClient from the one passed in and sets the authenticator and SSLSocketFactory instances. The authenticator is to support NTLM auth and the SSLSocketFactory takes care of SSL Client cert auth. This method uses the Android default TrustStore for SSL trust management.

## Parameters

| Name | Description |
|------|-------------|
| context | The Context used to access SDK configuration. Non-null. |
| client | The OkHttpClient to copy and configure. Non-null. |

open fun [copyWithDefaults](copy-with-defaults.md)(client: OkHttpClient, trustManager: [X509TrustManager](https://developer.android.com/reference/kotlin/javax/net/ssl/X509TrustManager.html)): OkHttpClient

Builds a new instance of OkHttpClient from the one passed in and sets the authenticator and SSLSocketFactory instances. The authenticator is to support NTLM auth and the SSLSocketFactory takes care of SSL Client cert auth. The TrustManager is used to customize the SSL trust management.

## Parameters

| Name | Description |
|------|-------------|
| client | The OkHttpClient to copy and configure. Non-null. |
| trustManager | The [X509TrustManager](https://developer.android.com/reference/kotlin/javax/net/ssl/X509TrustManager.html) used to customize SSL trust management. Non-null. |

## Return

A non-null configured OkHttpClient instance.

## Return

A non-null configured OkHttpClient instance.

## Return

A non-null configured OkHttpClient instance.
