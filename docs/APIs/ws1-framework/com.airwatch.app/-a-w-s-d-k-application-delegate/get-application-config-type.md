[ws1-framework](../../index.md)/[com.airwatch.app](../index.md)/[AWSDKApplicationDelegate](index.md)/[getApplicationConfigType](get-application-config-type.md)

# getApplicationConfigType

```kotlin
open override fun getApplicationConfigType(): String?
```

<div class="api-sig-types" markdown="span">[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-string/index.html)</div>

If your application needs to fetch application-specific settings, override this method. Otherwise it can be ignored.

## Return

Nullable string - your application configuration type or null if not applicable.
