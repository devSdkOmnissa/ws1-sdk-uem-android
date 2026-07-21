[ws1-network](../../index.md)/[com.airwatch.gateway.clients](../index.md)/[AWOkHttpClient](index.md)/[newCall](new-call.md)

# newCall

```kotlin
open fun newCall(client: OkHttpClient, request: Request): Call
```

Creates a new Call for the given request. When the proxy authenticator is required, the supplied client is copied with an AWOkHttpProxyAuthenticator attached.

## Parameters

| Name | Description |
|------|-------------|
| client | The OkHttpClient used to create the call. Non-null. |
| request | The Request to execute. Non-null. |

## Return

A non-null Call ready to be executed.
