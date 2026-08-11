[ws1-framework](../../index.md)/[com.airwatch.certpinning.repository](../index.md)/[CertPinRepository](index.md)/[getCertsByPin](get-certs-by-pin.md)

# getCertsByPin

```kotlin
abstract fun getCertsByPin(vararg pins: String): List<CertificateRecord>
```

<div class="api-sig-types" markdown="span">[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)</div>

Gets certificate records based on certificate pins.

## Parameters

| Name | Description |
|------|-------------|
| pins | Non-null vararg of certificate pin strings. |

## Return

Non-null list of CertificateRecord objects.
