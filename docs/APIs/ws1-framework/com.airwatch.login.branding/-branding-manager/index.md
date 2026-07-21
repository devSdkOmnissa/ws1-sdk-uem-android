[ws1-framework](../../index.md)/[com.airwatch.login.branding](../index.md)/[BrandingManager](index.md)

# BrandingManager

```kotlin
interface BrandingManager
```

This interface is used to provide branding for the login screen.

## Functions

| Name | Summary |
|---|---|
| [applyBranding](apply-branding.md) | abstract fun [applyBranding](apply-branding.md)(activity: Activity)<br>Applies branding to the activity.<br>abstract fun [applyBranding](apply-branding.md)(inputField: [AWInputField](../../com.airwatch.simplifiedenrollment.views/-a-w-input-field/index.md))<br>Applies branding to the input field.<br>abstract fun [applyBranding](apply-branding.md)(nextActionView: AWNextActionView)<br>Applies branding to the next action view. |
| [brandInputScreenLogo](brand-input-screen-logo.md) | abstract fun [brandInputScreenLogo](brand-input-screen-logo.md)(callBack: BrandingCallBack)<br>Brands the input screen logo.<br>open fun [brandInputScreenLogo](brand-input-screen-logo.md)(callBack: BrandingCallBack, width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html))<br>Brands the input screen logo with specific dimensions. |
| [brandLoadingScreenLogo](brand-loading-screen-logo.md) | abstract fun [brandLoadingScreenLogo](brand-loading-screen-logo.md)(callBack: BrandingCallBack)<br>Brands the loading screen logo.<br>open fun [brandLoadingScreenLogo](brand-loading-screen-logo.md)(callBack: BrandingCallBack, width: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html), height: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html))<br>Brands the loading screen logo with specific dimensions. |
| [getPrimaryColor](get-primary-color.md) | abstract fun [getPrimaryColor](get-primary-color.md)(): [Integer](https://developer.android.com/reference/kotlin/java/lang/Integer.html)<br>Returns the primary branding color. |

!!! abstract "Inheritors"

    | Name |
    |---|
    | [DefaultBrandingManager](../-default-branding-manager/index.md) |
