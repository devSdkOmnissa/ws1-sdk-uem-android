[ws1-client-sdk](../../index.md)/[com.airwatch.sdk.shareddevice](../index.md)/[CheckoutResponse](index.md)

# CheckoutResponse

```kotlin
open class CheckoutResponse
```

Shared device check out response GSON Class. 

 Provides response details from console after a shared device checkout operation occurs. Response from console is fetched via anchor application using SDKManager APIs.

## See also

- [com.airwatch.sdk.SDKManager](../../com.airwatch.sdk/-s-d-k-manager/accept-checkout-e-u-l-a.md)

## Functions

| Name | Summary |
|---|---|
| [getClearAppDataOnLogout](get-clear-app-data-on-logout.md) | open fun [getClearAppDataOnLogout](get-clear-app-data-on-logout.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Flag representing app wipe on checkin or checkout operation |
| [getEulaContent](get-eula-content.md) | open fun [getEulaContent](get-eula-content.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Provides content text for End User License Agreement. |
| [getEulaContentId](get-eula-content-id.md) | open fun [getEulaContentId](get-eula-content-id.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Provides content id for End User License Agreement. |
| [getMessage](get-message.md) | open fun [getMessage](get-message.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Provides status description for current Checkout operation |
| [getStatus](get-status.md) | open fun [getStatus](get-status.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Provides status of checkout operation |
