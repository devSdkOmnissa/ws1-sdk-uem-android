[ws1-client-sdk](../../index.md)/[com.airwatch.sdk.shareddevice](../index.md)/[ClearReasonCode](index.md)

# ClearReasonCode

```kotlin
enum ClearReasonCode
```

Provides reason for wipe action initiation.

## See also

- [com.airwatch.event.WS1AnchorEvents](../../com.airwatch.event/-w-s1-anchor-events/on-clear-app-data-command-received.md)

## Entries

| Name | Description |
|------|-------------|
| [APP_INITIALIZATION_FAILED](-a-p-p_-i-n-i-t-i-a-l-i-z-a-t-i-o-n_-f-a-i-l-e-d/index.md) | App initialization failed |
| [APP_INACTIVITY](-a-p-p_-i-n-a-c-t-i-v-i-t-y/index.md) | App was inactive beyond what's configured on the console |
| [APP_NOT_SUPPORTED](-a-p-p_-n-o-t_-s-u-p-p-o-r-t-e-d/index.md) | App is not supported |
| [NON_COMPLIANT](-n-o-n_-c-o-m-p-l-i-a-n-t/index.md) | Device failed one or more compliance policies |
| [UNKNOWN](-u-n-k-n-o-w-n/index.md) | Unknown Code triggered data wipe |
| [CTS_INCOMPATIBLE](-c-t-s_-i-n-c-o-m-p-a-t-i-b-l-e/index.md) | safetynet detected the device failed to pass Android compatibility testing, device might be tampered or modified |
| [REQUESTED_BY_APP](-r-e-q-u-e-s-t-e-d_-b-y_-a-p-p/index.md) | app trigger the wipe without user interaction example: anchor removed and remove package not received |
| [COMPROMISE_DETECTED_GUARD_IT](-c-o-m-p-r-o-m-i-s-e_-d-e-t-e-c-t-e-d_-g-u-a-r-d_-i-t/index.md) | Guard IT detect device compromised |
| [COMPROMISE_DETECTED_ENSURE_IT](-c-o-m-p-r-o-m-i-s-e_-d-e-t-e-c-t-e-d_-e-n-s-u-r-e_-i-t/index.md) | Ensure IT detected device compromised |
| [COMPROMISE_DETECTED_AW](-c-o-m-p-r-o-m-i-s-e_-d-e-t-e-c-t-e-d_-a-w/index.md) | compromise protection enabled and airwatch detect device compromised |
| [BREAK_MDM_COMMAND](-b-r-e-a-k_-m-d-m_-c-o-m-m-a-n-d/index.md) | Entripse wipe command from command processor |
| [APP_STATUS_ENDPOINT](-a-p-p_-s-t-a-t-u-s_-e-n-d-p-o-i-n-t/index.md) | App status end point triggered data wipe |
| [USER_DELETE_ACCOUNT_AND_SERVICE](-u-s-e-r_-d-e-l-e-t-e_-a-c-c-o-u-n-t_-a-n-d_-s-e-r-v-i-c-e/index.md) | user triggered account and service deletion from app setting |
| [MAX_ATTEMPT_VIOLATION](-m-a-x_-a-t-t-e-m-p-t_-v-i-o-l-a-t-i-o-n/index.md) | maximum attempt of authentication triggered data wipe |
| [ANCHOR_APP_UN_INSTALLED](-a-n-c-h-o-r_-a-p-p_-u-n_-i-n-s-t-a-l-l-e-d/index.md) | if anchor app uninstalled and broadcast message sent to app in case of WS1 and Container. |
| [ANCHOR_APP](-a-n-c-h-o-r_-a-p-p/index.md) | anchor app triggered data wipe |
