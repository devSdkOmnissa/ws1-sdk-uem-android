[ws1-framework](../../index.md)/[com.airwatch.sdk.context](../index.md)/[SDKContext](index.md)/[fetchAndExecuteComplianceSettings](fetch-and-execute-compliance-settings.md)

# fetchAndExecuteComplianceSettings

```kotlin
abstract fun fetchAndExecuteComplianceSettings(listener: IFutureSuccessCallback<Boolean>)
```

<div class="api-sig-types" markdown="span">[Boolean](https://developer.android.com/reference/kotlin/java/lang/Boolean.html)</div>

Initiates compliance settings fetch and executes restrictions and compliance tasks with the new/saved settings payload or clears any compliance related actions if none exists. This call will also reset the scheduler timer for the next settings fetch.

## Parameters

| Name | Description |
|------|-------------|
| listener | a callback determining if fetching and execution of compliance was successful |

## Throws

| Exception | Condition |
|-----------|-----------|
| com.airwatch.sdk.context.SDKContextException | if [is not initialized ](index.md). |
