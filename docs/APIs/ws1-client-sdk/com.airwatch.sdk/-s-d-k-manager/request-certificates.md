[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[requestCertificates](request-certificates.md)

# requestCertificates

```kotlin
open fun requestCertificates(issuerId: String, token: String, iCrc: ICertificateReceiverCallback): Boolean
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [ICertificateReceiverCallback](../-i-certificate-receiver-callback/index.md), [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)</div>

Requests the Anchor application to send the Certificates corresponding to the requested issuerId. If the token passed is not null and valid, then the anchor application will try to retrieve the certificates from console, if they are not found in the database. 

Access Level = AW_MANAGED (for details on access permission please check [SDKManager](index.md)) 

## Parameters

| Name | Description |
|------|-------------|
| issuerId | the IssuerId of the Certificate. |
| token | the token corresponding to the issuer |
| iCrc | [ICertificateReceiverCallback](../-i-certificate-receiver-callback/index.md) callback object to retrieve the certificates. |

## Return

true if certificates found for giver issuer; false if not found and/or needs a network call

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
