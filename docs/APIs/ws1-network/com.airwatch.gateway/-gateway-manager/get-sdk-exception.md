[ws1-network](../../index.md)/[com.airwatch.gateway](../index.md)/[GatewayManager](index.md)/[getSdkException](get-sdk-exception.md)

# getSdkException

```kotlin
open fun getSdkException(): AirWatchSDKException
```

Returns the SDK exception that occurred and was saved during tunnel setup.

## Return

AirWatchSDKException captured during tunnel setup. Before any tunnel setup failure is saved, this returns the default initialized exception.
