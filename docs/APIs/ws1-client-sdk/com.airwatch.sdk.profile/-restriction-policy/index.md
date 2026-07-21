[ws1-client-sdk](../../index.md)/[com.airwatch.sdk.profile](../index.md)/[RestrictionPolicy](index.md)

# RestrictionPolicy

```kotlin
open class RestrictionPolicy
```

Provides details regarding Restriction policy set in console. This includes restriction on usage of bluetooth, camera, copy paste, and offline access features 

Policy can be fetched from anchor application using [getRestrictionPolicy](../../com.airwatch.sdk/-s-d-k-manager/get-restriction-policy.md). Example usage 

```java
    //Initializes Workspace ONE SDK and connects with anchor application if it is available.
    SDKManager sdkManager = SDKManager.init(context);
    //Checks enrollment status
	   if(sdkManager.isEnrolled()){
	      //Fetch policy from enrolled anchor application.
	      RestrictionPolicy profile = sdkManager.getRestrictionPolicy();
	   }
```

## Functions

| Name | Summary |
|---|---|
| [allowBluetooth](allow-bluetooth.md) | open fun [allowBluetooth](allow-bluetooth.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Retrieve application restriction information for use of Bluetooth. |
| [allowCamera](allow-camera.md) | open fun [allowCamera](allow-camera.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Retrieve application restriction information for use of the camera. |
| [allowOfflineMode](allow-offline-mode.md) | open fun [allowOfflineMode](allow-offline-mode.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Determine if the application can be used when access to network is not available. |
| [preventCopyAndCutActions](prevent-copy-and-cut-actions.md) | open fun [preventCopyAndCutActions](prevent-copy-and-cut-actions.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Determine if the application is allowed to use clipboard copy and cut actions. |
