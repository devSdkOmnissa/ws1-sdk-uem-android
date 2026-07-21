[ws1-framework](../../index.md)/[com.airwatch.login](../index.md)/[SDKLoginSessionWrapper](index.md)/[authenticationType](authentication-type.md)

# authenticationType

```kotlin
val authenticationType: Int
```

<div class="api-sig-types" markdown="span">[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)</div>

Returns the current authentication type.

## Return

Non-null integer - the authentication type among one of the following:

- AuthenticationType.USER_NAME_PASSWORD
- AuthenticationType.PASSCODE
- AuthenticationType.DISABLED
