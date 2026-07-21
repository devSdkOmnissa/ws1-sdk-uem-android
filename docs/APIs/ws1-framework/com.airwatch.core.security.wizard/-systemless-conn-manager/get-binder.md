[ws1-framework](../../index.md)/[com.airwatch.core.security.wizard](../index.md)/[SystemlessConnManager](index.md)/[getBinder](get-binder.md)

# getBinder

```kotlin
fun getBinder(): SyslessCompDetector?
```

Returns the binder instance of the service. Clients can call APIs in {@link com.airwatch.core.security.wizard.SyslessCompDetector} using this binder instance.

## Return

binder instance of the service, or null if not connected.
