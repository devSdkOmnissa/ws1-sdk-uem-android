[ws1-framework](../../index.md)/[com.airwatch.simplifiedenrollment.views](../index.md)/[AWInputField](index.md)/[setOnEditorActionListener](set-on-editor-action-listener.md)

# setOnEditorActionListener

```kotlin
open fun setOnEditorActionListener(listener: OnEditorActionListener)
```

Sets a listener to be invoked when an editor action is performed on the input field.

## Parameters

| Name | Description |
|------|-------------|
| listener | Nullable listener to be notified of editor actions (e.g., IME_ACTION_GO, IME_ACTION_NEXT) |

open fun [setOnEditorActionListener](set-on-editor-action-listener.md)(imeOptions: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html))

Sets the IME action options for the input field.

## Parameters

| Name | Description |
|------|-------------|
| imeOptions | IME action option flags (e.g., EditorInfo.IME_ACTION_NEXT, EditorInfo.IME_ACTION_GO) |
