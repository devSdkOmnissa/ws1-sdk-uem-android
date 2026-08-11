[ws1-framework](../index.md)/[com.airwatch.app](index.md)

# Package com.airwatch.app

## Types

| Name | Summary |
|---|---|
| [AWApplication](-a-w-application/index.md) | abstract class [AWApplication](-a-w-application/index.md) : [AWSDKApplication](-a-w-s-d-k-application/index.md)<br>To support SDK Login and Authentication, applications (which extends android.app.Application) have to extend this class. In case, your application doesn't extend Application, your android.app.Application subclass should implement [AWSDKApplication](-a-w-s-d-k-application/index.md) and use [AWSDKApplicationDelegate](-a-w-s-d-k-application-delegate/index.md) for delegation |
| [AWSDKApplication](-a-w-s-d-k-application/index.md) | interface [AWSDKApplication](-a-w-s-d-k-application/index.md) : [AppSettingsContext](../com.airwatch.sdk.configuration/-app-settings-context/index.md), SDKLoginDataCollector, P2PContext, CommandProcessorContext, UnifiedPinContext, PushNotificationContext, BrandingProvider, IOnConfigurationChangeListener, SSLPinningContext, BeaconContext, CopyPasteContext, ClientTLSCertificateRotationListener<br>To support SDK Login and Authentication, application class (which extends android.app.Application) have to implement this. [AWSDKApplicationDelegate](-a-w-s-d-k-application-delegate/index.md) should be used for delegation. |
| [AWSDKApplicationDelegate](-a-w-s-d-k-application-delegate/index.md) | class [AWSDKApplicationDelegate](-a-w-s-d-k-application-delegate/index.md) : [AWSDKApplication](-a-w-s-d-k-application/index.md)<br>Delegation class for [AWSDKApplication](-a-w-s-d-k-application/index.md) interface to support the functioning of WS1 SDK Framework. |
