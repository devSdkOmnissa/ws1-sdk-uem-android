[ws1-client-sdk](../../index.md)/[com.airwatch.event](../index.md)/[WS1AnchorEvents](index.md)

# WS1AnchorEvents

```kotlin
interface WS1AnchorEvents
```

This need to be implemented by the App's and pass its reference via [SDKClientConfig](../-s-d-k-client-config/index.md). This is first step of migration to Workmanager from JobIntentService.

## Functions

| Name | Summary |
|---|---|
| [handleAutoEnrollmentStatus](handle-auto-enrollment-status.md) | open fun [handleAutoEnrollmentStatus](handle-auto-enrollment-status.md)(status: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html))<br>Abstract method for the third party application to handle auto enrollment completion broadcast. |
| [onAnchorAppCheckIn](on-anchor-app-check-in.md) | open fun [onAnchorAppCheckIn](on-anchor-app-check-in.md)(context: Context)<br>Method to handle device checked in (signed out) broadcast from AnchorApp. |
| [onAnchorAppCheckOut](on-anchor-app-check-out.md) | open fun [onAnchorAppCheckOut](on-anchor-app-check-out.md)(context: Context)<br>Method to handle device checked out (signed in) broadcast from AnchorApp. |
| [onAnchorAppUpgrade](on-anchor-app-upgrade.md) | abstract fun [onAnchorAppUpgrade](on-anchor-app-upgrade.md)(context: Context, isUpgrade: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html))<br>Method to handle broadcast for Anchor App Upgrade. |
| [onApplicationConfigurationChange](on-application-configuration-change.md) | abstract fun [onApplicationConfigurationChange](on-application-configuration-change.md)(applicationConfiguration: Bundle, context: Context)<br>App should override and implement this method to receive application configuration changes from console. |
| [onClearAppDataCommandReceived](on-clear-app-data-command-received.md) | abstract fun [onClearAppDataCommandReceived](on-clear-app-data-command-received.md)(context: Context, reasonCode: [ClearReasonCode](../../com.airwatch.sdk.shareddevice/-clear-reason-code/index.md))<br>Clear app data requested from Workspace ONE SDK. |
| [onEnrollmentComplete](on-enrollment-complete.md) | open fun [onEnrollmentComplete](on-enrollment-complete.md)(context: Context, enrollmentFrom: [String](https://developer.android.com/reference/kotlin/java/lang/String.html))<br>Callback to perform actions on enrollment completion. |
| [onLauncherEvent](on-launcher-event.md) | open fun [onLauncherEvent](on-launcher-event.md)(eventType: [String](https://developer.android.com/reference/kotlin/java/lang/String.html), bundle: Bundle)<br>Method to handle broadcast from launcher. |
| [onOGChangeStatusReceived](on-o-g-change-status-received.md) | open fun [onOGChangeStatusReceived](on-o-g-change-status-received.md)(context: Context)<br>App should override and implement this method to receive OG change command status. |
