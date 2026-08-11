[ws1-network](../../index.md)/[com.airwatch.gateway.clients](../index.md)/[AWCertAuthUtil](index.md)/[getCertAuthKeyManagers](get-cert-auth-key-managers.md)

# getCertAuthKeyManagers

```kotlin
open fun getCertAuthKeyManagers(): Array<KeyManager>
```

<div class="api-sig-types" markdown="span">[Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html), [KeyManager](https://developer.android.com/reference/kotlin/javax/net/ssl/KeyManager.html)</div>

If Client Cert auth is enabled, this method returns a KeyManager array with a KeyManager containing client certificates fetched from the AW console for use in various HTTP clients. The returned KeyManager object is typically used to construct an SSLContext instance.

## Return

a KeyManager array with a KeyManager containing client certificates. If the client certificate retrieval fails or in case of any other errors, this method returns null. If cert auth is not enabled, this method returns null.
