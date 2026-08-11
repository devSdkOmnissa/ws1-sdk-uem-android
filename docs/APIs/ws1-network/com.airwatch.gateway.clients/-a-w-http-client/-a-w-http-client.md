[ws1-network](../../index.md)/[com.airwatch.gateway.clients](../index.md)/[AWHttpClient](index.md)/[AWHttpClient](-a-w-http-client.md)

# AWHttpClient

```kotlin
open fun AWHttpClient(context: Context)
```

Creates a client that tunnels traffic and responds to integrated auth challenges using a user with no domain and password.

## Parameters

| Name | Description |
|------|-------------|
| context | The Context used to access SDK configuration. Non-null. (Note* this class will not support self signed certificate webSites) |

open fun [AWHttpClient](-a-w-http-client.md)(context: Context, useDomainWithUserCredentials: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html))

Creates a client that tunnels traffic and responds to integrated auth challenges using a user and password.

## Parameters

| Name | Description |
|------|-------------|
| context | The Context used to access SDK configuration. Non-null. |
| useDomainWithUserCredentials | true for Domain/USerName:Password false for UserName:Password (default) (Note* this class will not support self signed certificate webSites) |
