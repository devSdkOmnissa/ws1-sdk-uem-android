[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[acceptCheckoutEULA](accept-checkout-e-u-l-a.md)

# acceptCheckoutEULA

```kotlin
open fun acceptCheckoutEULA(eulaContentId: String, accepted: Boolean): CheckoutResponse
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html), [CheckoutResponse](../../com.airwatch.sdk.shareddevice/-checkout-response/index.md)</div>

Request console to check out the device for corresponding user with Accept EULA acknowledgment. 

Access Level = AW_MANAGED (for details on access permission please check [SDKManager](index.md)) 

## Parameters

| Name | Description |
|------|-------------|
| eulaContentId | The id of the EULA content |
| accepted | boolean flag to indicate whether the EULA is accepted or not. |

## Return

The CheckoutResponse object containing the details of the checkout operation

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
