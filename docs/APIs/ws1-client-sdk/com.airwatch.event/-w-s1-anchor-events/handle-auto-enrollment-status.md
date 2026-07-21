[ws1-client-sdk](../../index.md)/[com.airwatch.event](../index.md)/[WS1AnchorEvents](index.md)/[handleAutoEnrollmentStatus](handle-auto-enrollment-status.md)

# handleAutoEnrollmentStatus

```kotlin
open fun handleAutoEnrollmentStatus(status: Int)
```

<div class="api-sig-types" markdown="span">[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)</div>

Abstract method for the third party application to handle auto enrollment completion broadcast. This will be triggered after [autoEnroll](../../com.airwatch.sdk/-s-d-k-manager/auto-enroll.md)

## Parameters

| Name | Description |
|------|-------------|
| status | integer to indicate the status of aunto enrollment. When complete, AirWatchSDKConstants.AUTO_ENROLLMENT_STATUS_COMPLETE will be used as an input |
