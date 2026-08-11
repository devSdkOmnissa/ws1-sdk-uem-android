[ws1-framework](../../index.md)/[com.airwatch.crypto.openssl](../index.md)/[OpenSSLCryptUtil](index.md)/[getInstance](get-instance.md)

# getInstance

```kotlin
open fun getInstance(): OpenSSLCryptUtil
```

<div class="api-sig-types" markdown="span">[OpenSSLCryptUtil](index.md)</div>

Retrieves the singleton instance of OpenSSLCryptUtil. 

 If the instance has not been created yet, this method will attempt to create it. The instance is created lazily upon first call and is thread-safe. 

## Return

The singleton instance of OpenSSLCryptUtil, or null if creation fails
