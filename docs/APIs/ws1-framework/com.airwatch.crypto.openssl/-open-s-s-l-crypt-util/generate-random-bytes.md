[ws1-framework](../../index.md)/[com.airwatch.crypto.openssl](../index.md)/[OpenSSLCryptUtil](index.md)/[generateRandomBytes](generate-random-bytes.md)

# generateRandomBytes

```kotlin
open fun generateRandomBytes(size: Int, seed: Array<Byte>): Array<Byte>
```

<div class="api-sig-types" markdown="span">[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html), [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-byte/index.html)</div>

Generates random bytes of the specified size using the provided seed.

## Parameters

| Name | Description |
|------|-------------|
| size | The number of random bytes to generate |
| seed | The seed value as a byte array |

## Return

A byte array of random bytes
