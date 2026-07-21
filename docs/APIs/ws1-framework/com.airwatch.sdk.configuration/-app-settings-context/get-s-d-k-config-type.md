[ws1-framework](../../index.md)/[com.airwatch.sdk.configuration](../index.md)/[AppSettingsContext](index.md)/[getSDKConfigType](get-s-d-k-config-type.md)

# getSDKConfigType

```kotlin
abstract fun getSDKConfigType(): String
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html)</div>

If your application needs to fetch SDK settings, the default value is 21 unless it is a wrapped app, in which case it is 22.

## Return

Non-null string - your SDK configuration type.
