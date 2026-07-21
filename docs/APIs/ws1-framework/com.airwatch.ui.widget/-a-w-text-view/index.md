[ws1-framework](../../index.md)/[com.airwatch.ui.widget](../index.md)/[AWTextView](index.md)

# AWTextView

```kotlin
open class AWTextView : ICLipBoard
```

Custom TextView to be used to set the font either dynamically (from the java files using setTypeface) or can be set in the xml file. In the xml, font can set using airwatch:awsdkFontStyle="value" where airwatch is the namespace and fontStyle is the attribute to be set. The allowed value set for fontStyle is as follows:"bold"-Roboto-Bold"medium"-Roboto-Medium"light"-Roboto-Light"regular"-Roboto-Regular Note: Please include the .ttf files for the above mentioned fonts in the assets folder of the project.

## Functions

| Name | Summary |
|---|---|
| [setTypeface](set-typeface.md) | open fun [setTypeface](set-typeface.md)(ctx: Context, fontId: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Sets the font style of the TextView based on the passed fontId. |
