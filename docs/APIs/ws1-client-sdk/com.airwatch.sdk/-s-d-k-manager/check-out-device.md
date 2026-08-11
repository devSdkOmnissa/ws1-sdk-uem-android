[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[checkOutDevice](check-out-device.md)

# checkOutDevice

```kotlin
open fun checkOutDevice(user: String, password: String, groupCode: String): CheckoutResponse
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [CheckoutResponse](../../com.airwatch.sdk.shareddevice/-checkout-response/index.md)</div>

Checkouts the device from (login to) a different child organization group than the one it is enrolled to. 

Access Level = AW_MANAGED (for details on access permission please check [SDKManager](index.md)) 

## Parameters

| Name | Description |
|------|-------------|
| user | The username with which the device is enrolled |
| password | The password with which the device is enrolled |
| groupCode | The id of child organization group to which the device is enrolling now |

## Return

CheckoutResponse object containing the details of the operation

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
