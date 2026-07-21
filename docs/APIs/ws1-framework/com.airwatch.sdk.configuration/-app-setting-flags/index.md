[ws1-framework](../../index.md)/[com.airwatch.sdk.configuration](../index.md)/[AppSettingFlags](index.md)

# AppSettingFlags

```kotlin
open class AppSettingFlags
```

Add pre-defined keys and set flags on application for SDK to read and process. Note: The keys set are stored in-memory and is the responsibility of the application to repopulate on kill and relaunch.

## Functions

| Name | Summary |
|---|---|
| [get](get.md) | open fun [get](get.md)(key: [String](https://developer.android.com/reference/kotlin/java/lang/String.html)): [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-any/index.html)<br>Gets the flag value from the in-memory map. |
| [getAll](get-all.md) | open fun [getAll](get-all.md)(): [Map](https://developer.android.com/reference/kotlin/java/util/Map.html)&lt;[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-any/index.html)&gt;<br>Return all setting flags that have been set and their values. |
| [getBoolean](get-boolean.md) | open fun [getBoolean](get-boolean.md)(key: [String](https://developer.android.com/reference/kotlin/java/lang/String.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>open fun [getBoolean](get-boolean.md)(key: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), defaultValue: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Gets the boolean flag value from the in-memory map. |
