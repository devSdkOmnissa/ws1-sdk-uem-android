[ws1-framework](../../index.md)/[com.airwatch.login](../index.md)/[SDKLoginSessionWrapper](index.md)/[authenticationMode](authentication-mode.md)

# authenticationMode

```kotlin
val authenticationMode: String
```

<div class="api-sig-types" markdown="span">[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)</div>

Returns the current authentication mode.

## Return

Non-null string - the authentication mode among the following:

- SDKAppAuthenticator.AUTHENTICATION_MODE_SSO
- SDKAppAuthenticator.AUTHENTICATION_MODE_SSO_DISABLED
- SDKAppAuthenticator.AUTHENTICATION_MODE_STANDALONE
