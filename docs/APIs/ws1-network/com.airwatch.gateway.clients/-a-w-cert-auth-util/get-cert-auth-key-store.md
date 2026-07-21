[ws1-network](../../index.md)/[com.airwatch.gateway.clients](../index.md)/[AWCertAuthUtil](index.md)/[getCertAuthKeyStore](get-cert-auth-key-store.md)

# getCertAuthKeyStore

```kotlin
open fun getCertAuthKeyStore(): KeyStore
```

<div class="api-sig-types" markdown="span">[KeyStore](https://developer.android.com/reference/kotlin/java/security/KeyStore.html)</div>

If Client Cert auth is enabled, this method returns a KeyStore instance containing client certificates fetched from the AW console for use in various HTTP clients.

## Return

a KeyStore instance containing client certificates. If the client certificate retrieval fails or if client cert auth is not enabled, this method returns null.
