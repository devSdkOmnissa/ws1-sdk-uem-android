[ws1-framework](../../index.md)/[com.airwatch.sdk.context](../index.md)/[SDKContext](index.md)/[getCurrentState](get-current-state.md)

# getCurrentState

```kotlin
abstract fun getCurrentState(): SDKContext.State
```

Returns the current state of the SDKContextManager. The state is determined based on the initialization and configuration status of the SDKContextManager. The state can be used to restrict access to certain methods based on the current state of the SDKContextManager.

## Return

SDKContextManager.State

## See also

- com.airwatch.sdk.context.SDKContext.State
