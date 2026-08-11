[ws1-network](../../index.md)/[com.airwatch.gateway.clients](../index.md)/[AWCertAuthUtil](index.md)

# AWCertAuthUtil

```kotlin
class AWCertAuthUtil
```

Utility class for AW TLS/SSL Client Cert Authentication for various HTTP Clients. It provides APIs that return a [KeyManager](https://developer.android.com/reference/kotlin/javax/net/ssl/KeyManager.html) instance built using the certificate and private key configured in the SDK profile fetched from the Workspace ONE UEM.

## Functions

| Name | Summary |
|---|---|
| [getCertAuthKeyManagers](get-cert-auth-key-managers.md) | open fun [getCertAuthKeyManagers](get-cert-auth-key-managers.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html)&lt;[KeyManager](https://developer.android.com/reference/kotlin/javax/net/ssl/KeyManager.html)&gt;<br>If Client Cert auth is enabled, this method returns a KeyManager array with a KeyManager containing client certificates fetched from the AW console for use in various HTTP clients. |
| [getCertAuthKeyStore](get-cert-auth-key-store.md) | open fun [getCertAuthKeyStore](get-cert-auth-key-store.md)(): [KeyStore](https://developer.android.com/reference/kotlin/java/security/KeyStore.html)<br>If Client Cert auth is enabled, this method returns a KeyStore instance containing client certificates fetched from the AW console for use in various HTTP clients. |
