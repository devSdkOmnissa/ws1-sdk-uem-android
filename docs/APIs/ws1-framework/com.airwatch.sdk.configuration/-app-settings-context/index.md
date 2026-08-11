[ws1-framework](../../index.md)/[com.airwatch.sdk.configuration](../index.md)/[AppSettingsContext](index.md)

# AppSettingsContext

```kotlin
interface AppSettingsContext
```

Implement this interface to provide the context for the SDK to fetch settings.

## Functions

| Name | Summary |
|---|---|
| [getApplicationConfigType](get-application-config-type.md) | abstract fun [getApplicationConfigType](get-application-config-type.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>If your application needs to fetch application-specific settings, override this method. |
| [getApplicationConfigVersion](get-application-config-version.md) | abstract fun [getApplicationConfigVersion](get-application-config-version.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Returns the application configuration version. |
| [getFlags](get-flags.md) | abstract fun [getFlags](get-flags.md)(): [AppSettingFlags](../-app-setting-flags/index.md)<br>Returns an instance of [AppSettingFlags](../-app-setting-flags/index.md) that contains all the flags the application needs to communicate with the SDK framework. |
| [getSDKConfigType](get-s-d-k-config-type.md) | abstract fun [getSDKConfigType](get-s-d-k-config-type.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>If your application needs to fetch SDK settings, the default value is 21 unless it is a wrapped app, in which case it is 22. |
| [isGeofencingSupported](is-geofencing-supported.md) | abstract fun [isGeofencingSupported](is-geofencing-supported.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Indicates whether geofencing is supported by the application. |
| [shouldRetainContentBetweenSessions](should-retain-content-between-sessions.md) | open fun [shouldRetainContentBetweenSessions](should-retain-content-between-sessions.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Returns whether the application should retain content between sessions. |

!!! abstract "Inheritors"

    | Name |
    |---|
    | [AWSDKApplication](../../com.airwatch.app/-a-w-s-d-k-application/index.md) |
