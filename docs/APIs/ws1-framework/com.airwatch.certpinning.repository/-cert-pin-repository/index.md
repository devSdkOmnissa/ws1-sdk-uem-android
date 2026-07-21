[ws1-framework](../../index.md)/[com.airwatch.certpinning.repository](../index.md)/[CertPinRepository](index.md)

# CertPinRepository

```kotlin
interface CertPinRepository
```

Repository interface for Certificate Pinning.

## Functions

| Name | Summary |
|---|---|
| [getAllHosts](get-all-hosts.md) | abstract fun [getAllHosts](get-all-hosts.md)(): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)&lt;HostRecord&gt;<br>Gets all available host records. |
| [getCertsByHostID](get-certs-by-host-i-d.md) | abstract fun [getCertsByHostID](get-certs-by-host-i-d.md)(vararg hostIds: [Long](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-long/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)&lt;CertificateRecord&gt;<br>Gets certificate records for particular hosts. |
| [getCertsByPin](get-certs-by-pin.md) | abstract fun [getCertsByPin](get-certs-by-pin.md)(vararg pins: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)&lt;CertificateRecord&gt;<br>Gets certificate records based on certificate pins. |
| [getHostByHostName](get-host-by-host-name.md) | abstract fun [getHostByHostName](get-host-by-host-name.md)(hostname: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)): HostRecord?<br>Searches for a HostRecord based on hostname. |
| [getHosts](get-hosts.md) | abstract fun [getHosts](get-hosts.md)(vararg hostList: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)&lt;HostRecord&gt;<br>Gets all host records based on host URLs. |
| [getPinsByHost](get-pins-by-host.md) | abstract fun [getPinsByHost](get-pins-by-host.md)(vararg hosts: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)): [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)&gt;<br>Gets certificate pins for particular hosts. |
