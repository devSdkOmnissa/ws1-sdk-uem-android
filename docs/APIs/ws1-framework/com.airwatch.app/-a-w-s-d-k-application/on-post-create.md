[ws1-framework](../../index.md)/[com.airwatch.app](../index.md)/[AWSDKApplication](index.md)/[onPostCreate](on-post-create.md)

# onPostCreate

```kotlin
abstract fun onPostCreate()
```

android.app.Application.onCreate may get called by another SDK process very frequently and cause unintended effects. To avoid this, place application-specific initialization in [onPostCreate](on-post-create.md). [onPostCreate](on-post-create.md) will not be called during Direct boot mode.
