[ws1-framework](../../index.md)/[com.airwatch.certpinning.repository](../index.md)/[CertPinRepository](index.md)/[getCertsByHostID](get-certs-by-host-i-d.md)

# getCertsByHostID

```kotlin
abstract fun getCertsByHostID(vararg hostIds: Long): List<CertificateRecord>
```

<div class="api-sig-types" markdown="span">[Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-long/index.html), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)</div>

Gets certificate records for particular hosts.

## Parameters

| Name | Description |
|------|-------------|
| hostIds | Non-null vararg of host IDs. |

## Return

Non-null list of CertificateRecord objects.
