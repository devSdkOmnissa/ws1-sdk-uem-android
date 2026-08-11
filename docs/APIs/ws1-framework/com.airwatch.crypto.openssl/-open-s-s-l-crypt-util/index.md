[ws1-framework](../../index.md)/[com.airwatch.crypto.openssl](../index.md)/[OpenSSLCryptUtil](index.md)

# OpenSSLCryptUtil

```kotlin
open class OpenSSLCryptUtil : IOpenSSLCryptUtil
```

Utility class containing methods for a range of cryptographic task including generation of message digest, encryption/decryption, signature validation, etc. 

 API in this class uses equivalent API in OpenSSL library through JNI call.

## Functions

| Name | Summary |
|---|---|
| [checkX509CertificateVersion](check-x509-certificate-version.md) | open fun [checkX509CertificateVersion](check-x509-certificate-version.md)(certPath: [String](https://developer.android.com/reference/kotlin/java/lang/String.html)): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Checks the version attribute of an X.509 certificate. |
| [generateRandomBytes](generate-random-bytes.md) | open fun [generateRandomBytes](generate-random-bytes.md)(size: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html), seed: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-byte/index.html)&gt;): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-byte/index.html)&gt;<br>Generates random bytes of the specified size using the provided seed. |
| [getInstance](get-instance.md) | open fun [getInstance](get-instance.md)(): [OpenSSLCryptUtil](index.md)<br>Retrieves the singleton instance of OpenSSLCryptUtil. |
| [sha256Hash](sha256-hash.md) | open fun [sha256Hash](sha256-hash.md)(toHash: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-byte/index.html)&gt;): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-byte/index.html)&gt;<br>Generates a SHA256 hash of the input byte array.<br>open fun [sha256Hash](sha256-hash.md)(file: [File](https://developer.android.com/reference/kotlin/java/io/File.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-byte/index.html)&gt;<br>Generates a SHA256 hash of a file.<br>open fun [sha256Hash](sha256-hash.md)(toHash: [String](https://developer.android.com/reference/kotlin/java/lang/String.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-byte/index.html)&gt;<br>Generates a SHA256 hash of the input string. |
