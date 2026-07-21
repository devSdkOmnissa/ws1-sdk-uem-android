[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[autoEnroll](auto-enroll.md)

# autoEnroll

```kotlin
open fun autoEnroll(server: String, groupId: String, user: String, password: String): Boolean
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html), [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)</div>

Enrolls the application silently if agent is not yet enrolled. 

Access Level = AW_WHITELISTED (for details on access permission please check [SDKManager](index.md)) 

 To check the progress need to check [isEnrolled](is-enrolled.md) Receive the callback for auto enrollment finish in [handleAutoEnrollmentStatus](../../com.airwatch.event/-w-s1-anchor-events/handle-auto-enrollment-status.md)

## Parameters

| Name | Description |
|------|-------------|
| server | Device Services server URL to enroll against. |
| groupId | Organization group identifier used for enrollment. |
| user | Enrollment username. |
| password | Enrollment password for the given user. |

## Return

true if enrollment started successfully; false on permission issue.

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if API is not available in Anchor Application or binding with Anchor app fails |
