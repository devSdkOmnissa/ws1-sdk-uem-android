[ws1-framework](../../index.md)/[com.airwatch.certpinning.repository](../index.md)/[CertPinRepository](index.md)/[getHosts](get-hosts.md)

# getHosts

```kotlin
abstract fun getHosts(vararg hostList: String): List<HostRecord>
```

<div class="api-sig-types" markdown="span">[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)</div>

Gets all host records based on host URLs.

## Parameters

| Name | Description |
|------|-------------|
| hostList | Non-null vararg of host URL strings. |

## Return

Non-null list of HostRecord objects.
