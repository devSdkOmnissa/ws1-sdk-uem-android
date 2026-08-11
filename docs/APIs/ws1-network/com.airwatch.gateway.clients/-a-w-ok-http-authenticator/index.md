[ws1-network](../../index.md)/[com.airwatch.gateway.clients](../index.md)/[AWOkHttpAuthenticator](index.md)

# AWOkHttpAuthenticator

```kotlin
open class AWOkHttpAuthenticator
```

An Authenticator implementation that provides NTLM auth support with WS1 enrollment credentials. Using the constructor that takes in the Activity Context will make this implementation handle re-authentication prompts - i.e., if the user's AD credentials changes (due to a periodic change) then this implementation will prompt the user to enter the new password.

## Functions

| Name | Summary |
|---|---|
| [authenticate](authenticate.md) | open fun [authenticate](authenticate.md)(route: Route, response: Response): Request<br>Responds to an authentication challenge from the server by building a new request that carries the appropriate NTLM or Basic Authorization header using WS1 enrollment credentials. |
