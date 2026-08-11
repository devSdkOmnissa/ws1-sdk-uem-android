[ws1-framework](../../index.md)/[com.airwatch.crypto.openssl](../index.md)/[OpenSSLCryptUtil](index.md)/[sha256Hash](sha256-hash.md)

# sha256Hash

```kotlin
open fun sha256Hash(toHash: String): Array<Byte>
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html), [Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-byte/index.html)</div>

Generates a SHA256 hash of the input string.

## Parameters

| Name | Description |
|------|-------------|
| toHash | The string to be hashed |

open fun [sha256Hash](sha256-hash.md)(toHash: [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-byte/index.html)&gt;): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-byte/index.html)&gt;

Generates a SHA256 hash of the input byte array.

## Parameters

| Name | Description |
|------|-------------|
| toHash | The byte array to be hashed |

open fun [sha256Hash](sha256-hash.md)(file: [File](https://developer.android.com/reference/kotlin/java/io/File.html)): [Array](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-array/index.html)&lt;[Byte](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-byte/index.html)&gt;

Generates a SHA256 hash of a file.

## Parameters

| Name | Description |
|------|-------------|
| file | The file to be hashed |

## Return

The SHA256 hash as a byte array

## Return

The SHA256 hash as a byte array

## Return

The SHA256 hash as a byte array, or null if an error occurs
