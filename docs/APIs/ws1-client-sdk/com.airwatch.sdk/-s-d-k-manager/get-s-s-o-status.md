[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKManager](index.md)/[getSSOStatus](get-s-s-o-status.md)

# getSSOStatus

```kotlin
open fun getSSOStatus(): SsoSessionReturnCode
```

<div class="api-sig-types" markdown="span">[SsoSessionReturnCode](../-sso-session-return-code/index.md)</div>

Provides the status of the broker app even before SDKManager instance is initialized. It tries to perform connect() and checks whether SSO is enabled or not. If the connect() fails, it will throw corresponding SsoSessionReturnCode. 

Access Level = NONE (for details on access permission please check [SDKManager](index.md)) 

## Return

Non-null [SsoSessionReturnCode](../-sso-session-return-code/index.md) indicating the SSO status: 

- SsoSessionReturnCode.SUCCESS if SSO is enabled
- SsoSessionReturnCode.SSO_MODE_DISABLED if SSO is disabled
- SsoSessionReturnCode.BROKER_APP_NOT_ENROLLED if Anchor app is not enrolled
- SsoSessionReturnCode.BROKER_APP_NOT_AVAILABLE if Anchor app is not available on the device
- SsoSessionReturnCode.FAIL some error occurred during call
