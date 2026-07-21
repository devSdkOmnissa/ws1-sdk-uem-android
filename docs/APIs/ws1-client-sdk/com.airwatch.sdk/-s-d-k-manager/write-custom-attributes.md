[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[writeCustomAttributes](write-custom-attributes.md)

# writeCustomAttributes

```kotlin
open fun writeCustomAttributes(attributes: List<CustomAttributeData>): Int
```

<div class="api-sig-types" markdown="span">[List](https://developer.android.com/reference/kotlin/java/util/List.html), [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)</div>

Writes custom attributes for the given list of attributes. 

 Each CustomAttributeData must have group, key, and value fields populated. 

## Parameters

| Name | Description |
|------|-------------|
| attributes | list of attributes to write. |

## Return

Positive integer indicating the number of attributes successfully written, or SDK_RES_FAIL status code if attributes array is empty/null.

## Throws

| Exception | Condition |
|-----------|-----------|
| [com.airwatch.sdk.AirWatchSDKException](../-air-watch-s-d-k-exception/index.md) | if any attribute is null or has null/empty group or key, if the service returns an error message, if API is not available in Anchor Application, or if binding with Anchor app fails. |
