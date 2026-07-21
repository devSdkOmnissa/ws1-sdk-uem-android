[ws1-framework](../../index.md)/[com.airwatch.ui.widget](../index.md)/[AWEditText](index.md)/[setTypeface](set-typeface.md)

# setTypeface

```kotlin
open fun setTypeface(ctx: Context, fontId: Int): Boolean
```

<div class="api-sig-types" markdown="span">[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html), [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)</div>

Sets the font style of the TextView based on the passed fontId.

## Parameters

| Name | Description |
|------|-------------|
| ctx | Non-null Application/activity context. |
| fontId | Integer value to set font:1 - Roboto-Bold 2 - Roboto-Light 3 - Roboto-Medium 4 - Roboto-Regular for pre API 16 default to Roboto Regular if font file included |

## Return

true if font style is set else false.
