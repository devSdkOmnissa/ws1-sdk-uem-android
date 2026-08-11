[ws1-framework](../../index.md)/[com.airwatch.login](../index.md)/[SDKBaseActivity](index.md)

# SDKBaseActivity

```kotlin
open class SDKBaseActivity : SDKBaseActivityDelegate.Callback
```

Base implementation that extends AppCompactActivity if other super class type required please extend or use the SDKBaseActivityDelegate to add the functionality to your base class.

## Functions

| Name | Summary |
|---|---|
| [isInForeground](is-in-foreground.md) | open fun [isInForeground](is-in-foreground.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Checks whether the activity is currently in the foreground. |
| [showWatermark](show-watermark.md) | open fun [showWatermark](show-watermark.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Controls whether to show watermark in the Activity as per the profile configured. |
