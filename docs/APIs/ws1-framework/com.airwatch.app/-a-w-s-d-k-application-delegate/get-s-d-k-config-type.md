[ws1-framework](../../index.md)/[com.airwatch.app](../index.md)/[AWSDKApplicationDelegate](index.md)/[getSDKConfigType](get-s-d-k-config-type.md)

# getSDKConfigType

```kotlin
open override fun getSDKConfigType(): String
```

<div class="api-sig-types" markdown="span">[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)</div>

If your application needs to fetch SDK settings, the default value is 21 unless it is a wrapped app, in which case it is 22.

## Return

Non-null string - your SDK configuration type.
