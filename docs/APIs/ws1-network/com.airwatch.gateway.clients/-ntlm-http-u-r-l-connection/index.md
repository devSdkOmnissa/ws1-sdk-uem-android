[ws1-network](../../index.md)/[com.airwatch.gateway.clients](../index.md)/[NtlmHttpURLConnection](index.md)

# NtlmHttpURLConnection

```kotlin
open class NtlmHttpURLConnection
```

Decorator class for NTLM authentication using WS1 Enrollment credentials Using the constructor that takes in the Activity Context will make this implementation handle re-authentication prompts - i.e., if the user's AD credentials changes (due to a periodic change) then this implementation will prompt the user to enter the new password.
