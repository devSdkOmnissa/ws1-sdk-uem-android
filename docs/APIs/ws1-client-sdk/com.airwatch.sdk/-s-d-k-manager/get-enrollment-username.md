[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[getEnrollmentUsername](get-enrollment-username.md)

# getEnrollmentUsername

```kotlin
open fun getEnrollmentUsername(): String
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html)</div>

Retrieves Enrollment Username assigned to the App which the device is currently enrolled. Access level AW_MANAGED for Agent V6.0 and above, for previous versions it is AW_ONLY. 

Access Level = AW_MANAGED (for details on access permission please check [SDKManager](index.md)) 

## Return

The Enrollment Username.

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails or app is not enrolled |
