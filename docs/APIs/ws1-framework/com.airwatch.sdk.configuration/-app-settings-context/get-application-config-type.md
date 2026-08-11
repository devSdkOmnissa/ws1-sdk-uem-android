[ws1-framework](../../index.md)/[com.airwatch.sdk.configuration](../index.md)/[AppSettingsContext](index.md)/[getApplicationConfigType](get-application-config-type.md)

# getApplicationConfigType

```kotlin
abstract fun getApplicationConfigType(): String
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html)</div>

If your application needs to fetch application-specific settings, override this method. Otherwise it can be ignored.

## Return

Nullable string - your application configuration type or null if not applicable.
