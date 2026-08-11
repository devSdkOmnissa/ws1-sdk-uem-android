[ws1-network](../../index.md)/[com.airwatch.gateway.clients](../index.md)/[AWOkHttpAuthenticator](index.md)/[authenticate](authenticate.md)

# authenticate

```kotlin
open fun authenticate(route: Route, response: Response): Request
```

Responds to an authentication challenge from the server by building a new request that carries the appropriate NTLM or Basic Authorization header using WS1 enrollment credentials. When configured with an activity context, this may prompt the user to update credentials if the existing ones fail.

## Parameters

| Name | Description |
|------|-------------|
| route | The Route for the request, or null. |
| response | The Response containing the authentication challenge. Non-null. |

## Return

A new Request with authentication headers, or null if the challenge cannot be satisfied. Nullable.
