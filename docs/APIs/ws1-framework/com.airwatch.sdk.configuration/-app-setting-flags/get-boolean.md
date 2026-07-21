[ws1-framework](../../index.md)/[com.airwatch.sdk.configuration](../index.md)/[AppSettingFlags](index.md)/[getBoolean](get-boolean.md)

# getBoolean

```kotlin
open fun getBoolean(key: String): Boolean
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)</div>

Gets the boolean flag value from the in-memory map. Returns false if the key doesn't exist or value not an instance of Boolean.

## Parameters

| Name | Description |
|------|-------------|
| key | Non-null setting flag key. |

open fun [getBoolean](get-boolean.md)(key: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), defaultValue: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)

Gets the boolean flag value from the in-memory map. Returns default value if the key doesn't exist or value not an instance of Boolean.

## Parameters

| Name | Description |
|------|-------------|
| key | Non-null setting flag key. |
| defaultValue | Default value to return if key not found. |

## Return

true if flag is true, false otherwise.

## Return

boolean flag value or defaultValue if not found.
