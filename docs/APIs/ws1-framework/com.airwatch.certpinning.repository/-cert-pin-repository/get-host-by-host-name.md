[ws1-framework](../../index.md)/[com.airwatch.certpinning.repository](../index.md)/[CertPinRepository](index.md)/[getHostByHostName](get-host-by-host-name.md)

# getHostByHostName

```kotlin
abstract fun getHostByHostName(hostname: String): HostRecord?
```

<div class="api-sig-types" markdown="span">[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)</div>

Searches for a HostRecord based on hostname.

## Parameters

| Name | Description |
|------|-------------|
| hostname | Non-null hostname string to search for. |

## Return

Nullable HostRecord - the matching host record or null if not found.
