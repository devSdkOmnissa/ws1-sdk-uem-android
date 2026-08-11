[ws1-framework](../../index.md)/[com.airwatch.certpinning.repository](../index.md)/[CertPinRepository](index.md)/[getPinsByHost](get-pins-by-host.md)

# getPinsByHost

```kotlin
abstract fun getPinsByHost(vararg hosts: String): List<String>
```

<div class="api-sig-types" markdown="span">[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html), [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)</div>

Gets certificate pins for particular hosts.

## Parameters

| Name | Description |
|------|-------------|
| hosts | Non-null vararg of host URL strings. |

## Return

Non-null list of certificate pin strings.
