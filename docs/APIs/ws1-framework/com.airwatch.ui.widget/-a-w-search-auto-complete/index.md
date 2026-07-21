[ws1-framework](../../index.md)/[com.airwatch.ui.widget](../index.md)/[AWSearchAutoComplete](index.md)

# AWSearchAutoComplete

```kotlin
open class AWSearchAutoComplete : ICLipBoard
```

A helper class to honour com.airwatch.clipboard.CopyPasteManager in SearchView.

 Instead of creating an entire custom SearchView widget that can handle clip data, this class offers a shortcut solution to do so. The SearchView allows us to inflate our own layout via the styleable attribute SearchView_layout. In the theme associated with your searchview override the style attribute "searchViewStyle" to define a custom style and in the custom style, override attribute "layout" to use aw_searchview_abc_search_view. See style ActionBarTheme in Boxer for an example.

## Functions

| Name | Summary |
|---|---|
| [setTypeface](set-typeface.md) | open fun [setTypeface](set-typeface.md)(ctx: Context, fontId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Sets the font style of the TextView based on the passed fontId. |
