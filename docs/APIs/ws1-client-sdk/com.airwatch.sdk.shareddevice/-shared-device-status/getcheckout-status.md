[ws1-client-sdk](../../index.md)/[com.airwatch.sdk.shareddevice](../index.md)/[SharedDeviceStatus](index.md)/[getcheckoutStatus](getcheckout-status.md)

# getcheckoutStatus

```kotlin
open fun getcheckoutStatus(): String
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html)</div>

Provides checkout status in Json format

## Return

The non-null [String](https://developer.android.com/reference/kotlin/java/lang/String.html) Details for SharedDevice such as 

- Username
- Group
- Status 
   
   - 0: Successful Operation
   - 1: Error in Last Operation
- CheckedOut 
   
   - 0: Device currently Checked Out
   - 1: Device currently Checked In
   - -1:Error in receiving data.

It is represented in a Json Format. An empty json indicates error receiving status from console endpoint
