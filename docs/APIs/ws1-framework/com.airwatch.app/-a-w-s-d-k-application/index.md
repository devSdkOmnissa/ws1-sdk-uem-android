[ws1-framework](../../index.md)/[com.airwatch.app](../index.md)/[AWSDKApplication](index.md)

# AWSDKApplication

```kotlin
interface AWSDKApplication : AppSettingsContext, SDKLoginDataCollector, P2PContext, CommandProcessorContext, UnifiedPinContext, PushNotificationContext, BrandingProvider, IOnConfigurationChangeListener, SSLPinningContext, BeaconContext, CopyPasteContext, ClientTLSCertificateRotationListener
```

<div class="api-sig-types" markdown="span">[AppSettingsContext](../../com.airwatch.sdk.configuration/-app-settings-context/index.md)</div>

To support SDK Login and Authentication, application class (which extends android.app.Application) have to implement this. [AWSDKApplicationDelegate](../-a-w-s-d-k-application-delegate/index.md) should be used for delegation.

## Functions

| Name | Summary |
|---|---|
| [getDelegate](get-delegate.md) | abstract fun [getDelegate](get-delegate.md)(): [AWSDKApplication](index.md)<br>Gets the delegate instance. This is very helpful if using Kotlin's class delegation model and want to intercept a delegation call. |
| [onPostCreate](on-post-create.md) | abstract fun [onPostCreate](on-post-create.md)()<br>android.app.Application.onCreate may get called by another SDK process very frequently and cause unintended effects. To avoid this, place application-specific initialization in [onPostCreate](on-post-create.md). [onPostCreate](on-post-create.md) will not be called during Direct boot mode. |

!!! abstract "Inheritors"

    | Name |
    |---|
    | [AWApplication](../-a-w-application/index.md) |
    | [AWSDKApplicationDelegate](../-a-w-s-d-k-application-delegate/index.md) |
