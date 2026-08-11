[ws1-framework](../../index.md)/[com.airwatch.crypto.openssl](../index.md)/[OpenSSLCryptUtil](index.md)/[checkX509CertificateVersion](check-x509-certificate-version.md)

# checkX509CertificateVersion

```kotlin
open fun checkX509CertificateVersion(certPath: String): Int
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)</div>

Checks the version attribute of an X.509 certificate. 

 This method is used to verify that the certificate version is valid (between 0 and 2). If the version is outside this range, the certificate may need to be rewritten. 

## Parameters

| Name | Description |
|------|-------------|
| certPath | The path to the X.509 certificate file |

## Return

The version number of the certificate, or an error code if version is invalid
