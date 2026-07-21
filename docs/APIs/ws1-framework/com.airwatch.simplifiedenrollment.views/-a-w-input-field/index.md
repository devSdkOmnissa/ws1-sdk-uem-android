[ws1-framework](../../index.md)/[com.airwatch.simplifiedenrollment.views](../index.md)/[AWInputField](index.md)

# AWInputField

```kotlin
open class AWInputField
```

A custom view that extends LinearLayout and provides a user input field with enhanced functionality. 

This view combines a TextInputLayout with EditText to provide Material Design compliant input fields with support for password visibility toggle, biometric authentication, and clipboard control.

## Types

| Name | Summary |
|---|---|
| [INPUT_MODE](-i-n-p-u-t_-m-o-d-e/index.md) | enum [INPUT_MODE](-i-n-p-u-t_-m-o-d-e/index.md)<br>Defines the input mode types for the AWInputField, determining keyboard type and input behavior. |
| [OnEditorActionListener](-on-editor-action-listener/index.md) | open class [OnEditorActionListener](-on-editor-action-listener/index.md)<br>Custom editor action listener that handles IME actions in conjunction with AWNextActionView. |

## Functions

| Name | Summary |
|---|---|
| [addTextChangedListener](add-text-changed-listener.md) | open fun [addTextChangedListener](add-text-changed-listener.md)(watcher: TextWatcher)<br>Adds a text watcher to monitor text changes in the input field. |
| [getText](get-text.md) | open fun [getText](get-text.md)(): Editable<br>Returns the current text content of the input field. |
| [getTextInputLayout](get-text-input-layout.md) | open fun [getTextInputLayout](get-text-input-layout.md)(): TextInputLayout<br>Returns the underlying TextInputLayout component. |
| [isEmpty](is-empty.md) | open fun [isEmpty](is-empty.md)(): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-boolean/index.html)<br>Checks if the input field is empty. |
| [setContentDescription](set-content-description.md) | open fun [setContentDescription](set-content-description.md)(contentDescription: [CharSequence](https://developer.android.com/reference/kotlin/java/lang/CharSequence.html))<br>Overrides the default content description behavior to set it on the EditText component as well. |
| [setHint](set-hint.md) | open fun [setHint](set-hint.md)(hint: [String](https://developer.android.com/reference/kotlin/java/lang/String.html))<br>Sets the hint text to be displayed when the input field is empty. |
| [setInputMode](set-input-mode.md) | open fun [setInputMode](set-input-mode.md)(mode: [AWInputField.INPUT_MODE](-i-n-p-u-t_-m-o-d-e/index.md))<br>Sets the input mode for the field, determining the keyboard type and input behavior. |
| [setMaxLength](set-max-length.md) | open fun [setMaxLength](set-max-length.md)(maxLength: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html))<br>Sets the maximum length of text that can be entered in the input field. |
| [setOnEditorActionListener](set-on-editor-action-listener.md) | open fun [setOnEditorActionListener](set-on-editor-action-listener.md)(listener: OnEditorActionListener)<br>Sets a listener to be invoked when an editor action is performed on the input field.<br>open fun [setOnEditorActionListener](set-on-editor-action-listener.md)(imeOptions: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html))<br>Sets the IME action options for the input field. |
| [setText](set-text.md) | open fun [setText](set-text.md)(text: [CharSequence](https://developer.android.com/reference/kotlin/java/lang/CharSequence.html))<br>Sets the text content of the input field. |
