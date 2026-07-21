[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[authenticateUser](authenticate-user.md)

# authenticateUser

```kotlin
open fun authenticateUser(userName: String, userPassword: String): Boolean
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)</div>

Verifies authentication credentials with the console. The device must have access to the console. This type of authentication is analogous to enrollment user credentials. 

Access Level = AW_MANAGED (for details on access permission please check [SDKManager](index.md)) 

## Parameters

| Name | Description |
|------|-------------|
| userName | It may be a basic user or it may be an AD user. |
| userPassword | The password for the user account. |

## Return

true on successful authentication. false if authentication failed

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
