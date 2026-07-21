[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[getBindingPackageName](get-binding-package-name.md)

# getBindingPackageName

```kotlin
open fun getBindingPackageName(context: Context): String
```

<div class="api-sig-types" markdown="span">[String](https://developer.android.com/reference/kotlin/java/lang/String.html)</div>

Utility method to determine the Anchor App to which SDK will be bound. Currently, Agent is given priority over the Workspace.

## Parameters

| Name | Description |
|------|-------------|
| context | The context from where this method is called. |

## Return

the package name to which the SDK will be bound
