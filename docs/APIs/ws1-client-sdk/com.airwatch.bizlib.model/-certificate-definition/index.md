[ws1-client-sdk](../../index.md)/[com.airwatch.bizlib.model](../index.md)/[CertificateDefinition](index.md)

# CertificateDefinition

```kotlin
open class CertificateDefinition
```

Parcelable model representing certificate data along with the credentials needed to access it.

## Functions

| Name | Summary |
|---|---|
| [getAppPackage](get-app-package.md) | open fun [getAppPackage](get-app-package.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Returns the package name of the application this certificate belongs to. |
| [getCertificateData](get-certificate-data.md) | open fun [getCertificateData](get-certificate-data.md)(): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-byte/index.html)&gt;<br>Returns the binary data of the certificate, decoded from its Base64 representation. |
| [getCertificateString](get-certificate-string.md) | open fun [getCertificateString](get-certificate-string.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Returns the certificate payload as a Base64-encoded string. |
| [getCredentialPwd](get-credential-pwd.md) | open fun [getCredentialPwd](get-credential-pwd.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Returns the credential storage password used to access the certificate. |
| [getEnableTima](get-enable-tima.md) | open fun [getEnableTima](get-enable-tima.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Indicates whether TIMA (TrustZone-based Integrity Measurement Architecture) key storage is enabled for this certificate. |
| [getId](get-id.md) | open fun [getId](get-id.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Returns the integer identifier assigned to this certificate. |
| [getName](get-name.md) | open fun [getName](get-name.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Returns the name assigned to the Certificate by the WS1 Console (typically the subject name). |
| [getPassword](get-password.md) | open fun [getPassword](get-password.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Returns the password associated with the certificate, when applicable (for example, for PKCS#12 certificates). |
| [getThumbprint](get-thumbprint.md) | open fun [getThumbprint](get-thumbprint.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Returns the thumbprint (fingerprint) of the certificate. |
| [getType](get-type.md) | open fun [getType](get-type.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Returns the type of the certificate (for example, X.509 or PKCS12). |
| [getUuid](get-uuid.md) | open fun [getUuid](get-uuid.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Returns the unique UUID assigned to the Certificate by the WS1 Console. |
| [isCertificateInstallable](is-certificate-installable.md) | open fun [isCertificateInstallable](is-certificate-installable.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Indicates whether the certificate should be installed into the device trust store. |
