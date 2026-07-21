[ws1-framework](../../index.md)/[com.airwatch.core.security.wizard](../index.md)/[SystemlessConnManager](index.md)

# SystemlessConnManager

```kotlin
object SystemlessConnManager
```

Provides APIs to connect and find if magisk is present or not. To use, client need to call {@link #init(Context)} to initialize and call required APIs in {@link com.airwatch.core.security.wizard.SyslessCompDetector} using {@link #getBinder()} Call @{link #deInit(context) after the api usage is done.

## Functions

| Name | Summary |
|---|---|
| [getBinder](get-binder.md) | fun [getBinder](get-binder.md)(): SyslessCompDetector<br>Returns the binder instance of the service. Clients can call APIs in {@link com.airwatch.core.security.wizard.SyslessCompDetector} using this binder instance. |
