[ws1-network](../../index.md)/[com.airwatch.gateway.clients](../index.md)/[AWAuthInterceptor](index.md)/[AWAuthInterceptor](-a-w-auth-interceptor.md)

# AWAuthInterceptor

```kotlin
open fun AWAuthInterceptor(useDomainWithUserCredentials: Boolean)
```

<div class="api-sig-types" markdown="span">[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)</div>

Creates an interceptor that handles NTLM and Basic authentication. By default the credentials are sent without a domain; pass true to send domain-qualified credentials.

## Parameters

| Name | Description |
|------|-------------|
| useDomainWithUserCredentials | true to use domain-qualified credentials (Domain/UserName:Password), false to use plain credentials (UserName:Password). |
