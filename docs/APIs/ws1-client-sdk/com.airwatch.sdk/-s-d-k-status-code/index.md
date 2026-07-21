[ws1-client-sdk](../../index.md)/[com.airwatch.sdk](../index.md)/[SDKStatusCode](index.md)

# SDKStatusCode

```kotlin
enum SDKStatusCode
```

Class provides mapping between SDK state codes and corresponding state's description. 

It is used to describe exceptions thrown for category [AirWatchSDKException](../-air-watch-s-d-k-exception/index.md).

## Entries

| Name | Description |
|------|-------------|
| [SDK_RES_NOT_AVAILABLE](-s-d-k_-r-e-s_-n-o-t_-a-v-a-i-l-a-b-l-e/index.md) | Default SDK resource not available error code. |
| [SDK_CUSTOM_ATTRIBUTE_OPERATION_FAILED](-s-d-k_-c-u-s-t-o-m_-a-t-t-r-i-b-u-t-e_-o-p-e-r-a-t-i-o-n_-f-a-i-l-e-d/index.md) | Custom attribute operation failed. |
| [SDK_AUTH_CREDENTIAL_TOKEN_FETCH_FAILED](-s-d-k_-a-u-t-h_-c-r-e-d-e-n-t-i-a-l_-t-o-k-e-n_-f-e-t-c-h_-f-a-i-l-e-d/index.md) | Failed to fetch Credential Token. |
| [SDK_APP_STATUS_ENDPOINT_FETCH_FAILED](-s-d-k_-a-p-p_-s-t-a-t-u-s_-e-n-d-p-o-i-n-t_-f-e-t-c-h_-f-a-i-l-e-d/index.md) | Fetching data from App Status endpoint failed. |
| [EMM_ACCESS_REQUIRED](-e-m-m_-a-c-c-e-s-s_-r-e-q-u-i-r-e-d/index.md) | Application requires MDM enrollment. |
| [APP_UNAUTHORIZED_ACCESS](-a-p-p_-u-n-a-u-t-h-o-r-i-z-e-d_-a-c-c-e-s-s/index.md) | Unauthorized app access. |
| [SDK_INITIALIZE_FAILED_UNKNOWN_FORMAT](-s-d-k_-i-n-i-t-i-a-l-i-z-e_-f-a-i-l-e-d_-u-n-k-n-o-w-n_-f-o-r-m-a-t/index.md) | SDK Initialization failed due to bad format. |
| [SDK_APP_NOT_ALLOWED_ON_COPE](-s-d-k_-a-p-p_-n-o-t_-a-l-l-o-w-e-d_-o-n_-c-o-p-e/index.md) | Deprecated. Use EMM_ACCESS_REQUIRED instead |
| [SDK_APP_NOT_SUPPORTED](-s-d-k_-a-p-p_-n-o-t_-s-u-p-p-o-r-t-e-d/index.md) | Authentication failed because the application is not supported. |
| [SDK_UDID_UPGRADE_ERROR](-s-d-k_-u-d-i-d_-u-p-g-r-a-d-e_-e-r-r-o-r/index.md) | Authentication failed due to a device ID mismatch. |
| [TUNNEL_OR_LP_FAILED_TO_START](-t-u-n-n-e-l_-o-r_-l-p_-f-a-i-l-e-d_-t-o_-s-t-a-r-t/index.md) | Tunnel SDK or local proxy failed to start. |
| [TUNNEL_SDK_CONFIG_NOT_FOUND](-t-u-n-n-e-l_-s-d-k_-c-o-n-f-i-g_-n-o-t_-f-o-u-n-d/index.md) | Tunnel SDK configuration not found in preferences. |
| [TUNNEL_SDK_CERT_FETCH_ERROR](-t-u-n-n-e-l_-s-d-k_-c-e-r-t_-f-e-t-c-h_-e-r-r-o-r/index.md) | Tunnel SDK client certificate fetch failed. |
| [TUNNEL_SDK_SCEP_TOKEN_FETCH_ERROR](-t-u-n-n-e-l_-s-d-k_-s-c-e-p_-t-o-k-e-n_-f-e-t-c-h_-e-r-r-o-r/index.md) | Tunnel SDK SCEP token fetch failed. |
| [TUNNEL_SDK_CONFIG_FETCH_ERROR](-t-u-n-n-e-l_-s-d-k_-c-o-n-f-i-g_-f-e-t-c-h_-e-r-r-o-r/index.md) | Tunnel SDK configuration fetch failed. |
| [SDK_ERROR_SCEP_PENDING](-s-d-k_-e-r-r-o-r_-s-c-e-p_-p-e-n-d-i-n-g/index.md) | SCEP enrollment status is pending. |
| [SDK_FORGOT_PASSCODE_FAILED](-s-d-k_-f-o-r-g-o-t_-p-a-s-s-c-o-d-e_-f-a-i-l-e-d/index.md) | Operation to reset passcode failed. |
| [SDK_SERVICE_EMPTY_RESPONSE](-s-d-k_-s-e-r-v-i-c-e_-e-m-p-t-y_-r-e-s-p-o-n-s-e/index.md) | Received empty response from WS1 MDM service. |
| [SDK_FETCH_APP_CONFIG_FAILED](-s-d-k_-f-e-t-c-h_-a-p-p_-c-o-n-f-i-g_-f-a-i-l-e-d/index.md) | Fetching custom app configuration failed. |
| [SDK_VERSION_NOT_SUPPORT](-s-d-k_-v-e-r-s-i-o-n_-n-o-t_-s-u-p-p-o-r-t/index.md) | Action not supported by installed SDK version. |
| [SDK_VERSION_ERROR](-s-d-k_-v-e-r-s-i-o-n_-e-r-r-o-r/index.md) | Invalid SDK version boundary. |
| [SDK_BINDING_SERVICE_ERROR](-s-d-k_-b-i-n-d-i-n-g_-s-e-r-v-i-c-e_-e-r-r-o-r/index.md) | Binding service connection to WS1 MDM failed. |
| [SDK_ROOT_DETECTION_FAILED](-s-d-k_-r-o-o-t_-d-e-t-e-c-t-i-o-n_-f-a-i-l-e-d/index.md) | Routine compromise detection scanning failed. |
| [SDK_AUTH_ENDPOINT_UNKNOWN_ERROR](-s-d-k_-a-u-t-h_-e-n-d-p-o-i-n-t_-u-n-k-n-o-w-n_-e-r-r-o-r/index.md) | Unknown error occurred at the authentication endpoint. |
| [SDK_AUTH_ENDPOINT_CONFIGURATION_ERROR](-s-d-k_-a-u-t-h_-e-n-d-p-o-i-n-t_-c-o-n-f-i-g-u-r-a-t-i-o-n_-e-r-r-o-r/index.md) | Authentication endpoint configuration error. |
| [SDK_AUTH_ENDPOINT_DEVICE_NOT_FOUND](-s-d-k_-a-u-t-h_-e-n-d-p-o-i-n-t_-d-e-v-i-c-e_-n-o-t_-f-o-u-n-d/index.md) | Device not found during lookup. |
| [SDK_AUTH_ENDPOINT_INVALID_TOKEN](-s-d-k_-a-u-t-h_-e-n-d-p-o-i-n-t_-i-n-v-a-l-i-d_-t-o-k-e-n/index.md) | The submitted authentication token is invalid. |
| [SDK_AUTH_ENDPOINT_DEVICE_NOT_MDM_ENROLLED](-s-d-k_-a-u-t-h_-e-n-d-p-o-i-n-t_-d-e-v-i-c-e_-n-o-t_-m-d-m_-e-n-r-o-l-l-e-d/index.md) | Device is not properly MDM enrolled. |
| [SDK_AUTH_ENDPOINT_INACTIVE_ACCOUNT](-s-d-k_-a-u-t-h_-e-n-d-p-o-i-n-t_-i-n-a-c-t-i-v-e_-a-c-c-o-u-n-t/index.md) | Associated profile authorization linked user Account is generally recognized but rendered inactive. |
| [SDK_AUTH_ENDPOINT_ACCOUNT_LOCKED](-s-d-k_-a-u-t-h_-e-n-d-p-o-i-n-t_-a-c-c-o-u-n-t_-l-o-c-k-e-d/index.md) | User account is locked. |
| [SDK_AUTH_ENDPOINT_INVALID_CREDS](-s-d-k_-a-u-t-h_-e-n-d-p-o-i-n-t_-i-n-v-a-l-i-d_-c-r-e-d-s/index.md) | Invalid user credentials provided. |
| [SDK_DERIVED_CREDENTIALS_ACTIVATION_FAILURE](-s-d-k_-d-e-r-i-v-e-d_-c-r-e-d-e-n-t-i-a-l-s_-a-c-t-i-v-a-t-i-o-n_-f-a-i-l-u-r-e/index.md) | Derived Credentials certificate fetch failed. |
| [SDK_DERIVED_CREDENTIALS_FAILURE](-s-d-k_-d-e-r-i-v-e-d_-c-r-e-d-e-n-t-i-a-l-s_-f-a-i-l-u-r-e/index.md) | Derived Credentials not valid or activation failed. |
| [SDK_INIT_ROTATION_FAILURE](-s-d-k_-i-n-i-t_-r-o-t-a-t-i-o-n_-f-a-i-l-u-r-e/index.md) | Initialization failed reflecting rotation operation faults. |
| [SDK_INIT_REQUIRED_FROM_OTHER_APP](-s-d-k_-i-n-i-t_-r-e-q-u-i-r-e-d_-f-r-o-m_-o-t-h-e-r_-a-p-p/index.md) | Another application must complete their initialization dependencies procedure first. |
| [SDK_CERT_PINNING_FAILED](-s-d-k_-c-e-r-t_-p-i-n-n-i-n-g_-f-a-i-l-e-d/index.md) | Certificate Pinning validation check on remote console SSL failed. |
| [SDK_MASTER_HMAC_REGISTER_FAILED](-s-d-k_-m-a-s-t-e-r_-h-m-a-c_-r-e-g-i-s-t-e-r_-f-a-i-l-e-d/index.md) | Registration of SDK application using Master HMAC failed. |
| [SDK_SERVER_COMMUNICATION_FAILED](-s-d-k_-s-e-r-v-e-r_-c-o-m-m-u-n-i-c-a-t-i-o-n_-f-a-i-l-e-d/index.md) | Connection request to Device Services endpoint failed. |
| [SDK_CERT_FETCH_FAILED](-s-d-k_-c-e-r-t_-f-e-t-c-h_-f-a-i-l-e-d/index.md) | Receiving targeted certificate properties from WS1 UEM Console failed. |
| [SDK_CONTEXT_EMAIL_NOT_VALID](-s-d-k_-c-o-n-t-e-x-t_-e-m-a-i-l_-n-o-t_-v-a-l-i-d/index.md) | Autodiscovery of server details failed using provided email. |
| [GATEWAY_INVALID_CONFIG](-g-a-t-e-w-a-y_-i-n-v-a-l-i-d_-c-o-n-f-i-g/index.md) | Provided Gateway Policy Network configuration has invalid elements. |
| [GATEWAY_FAILED_IN_CONFIGURING](-g-a-t-e-w-a-y_-f-a-i-l-e-d_-i-n_-c-o-n-f-i-g-u-r-i-n-g/index.md) | Network Gateway Proxy configuration failed with unexpected error. |
| [GATEWAY_PROXY_NOT_ENABLED](-g-a-t-e-w-a-y_-p-r-o-x-y_-n-o-t_-e-n-a-b-l-e-d/index.md) | Network Gateway Proxy mode is disabled. |
| [GATEWAY_PROXY_TYPE_NOT_SUPPORTED](-g-a-t-e-w-a-y_-p-r-o-x-y_-t-y-p-e_-n-o-t_-s-u-p-p-o-r-t-e-d/index.md) | Provided Proxy gateway type is none or unsupported. |
| [SDK_CONTEXT_SDK_SETTING_NOT_AVAILABLE](-s-d-k_-c-o-n-t-e-x-t_-s-d-k_-s-e-t-t-i-n-g_-n-o-t_-a-v-a-i-l-a-b-l-e/index.md) | Failed attempting to get SDK properties. Fetch properties configuration explicitly first. |
| [SDK_CONTEXT_USERNAME_PASSWORD_AUTHENTICATION_FAILED](-s-d-k_-c-o-n-t-e-x-t_-u-s-e-r-n-a-m-e_-p-a-s-s-w-o-r-d_-a-u-t-h-e-n-t-i-c-a-t-i-o-n_-f-a-i-l-e-d/index.md) | Input Username and password authentication request evaluation failed. |
| [SDK_CONTEXT_LOGIN_TYPE_FETCH_FAILED](-s-d-k_-c-o-n-t-e-x-t_-l-o-g-i-n_-t-y-p-e_-f-e-t-c-h_-f-a-i-l-e-d/index.md) | Attempted fetching of login type from console failed. |
| [SDK_CONTEXT_VALIDATE_QR_CODE_FAILED](-s-d-k_-c-o-n-t-e-x-t_-v-a-l-i-d-a-t-e_-q-r_-c-o-d-e_-f-a-i-l-e-d/index.md) | Supplied QR code validation processing failed. |
| [SDK_NO_ANCHOR_APP_FAILED](-s-d-k_-n-o_-a-n-c-h-o-r_-a-p-p_-f-a-i-l-e-d/index.md) | Anchor application was not detected or found on the system. |
| [SDK_CONTEXT_SSO_REGISTER_FAILED](-s-d-k_-c-o-n-t-e-x-t_-s-s-o_-r-e-g-i-s-t-e-r_-f-a-i-l-e-d/index.md) | Anchor Agent failed to process the SSO registration. |
| [SDK_CONTEXT_ACCEPT_EULA_FAILED](-s-d-k_-c-o-n-t-e-x-t_-a-c-c-e-p-t_-e-u-l-a_-f-a-i-l-e-d/index.md) | An error occurred while attempting to accept the EULA policies. |
| [SDK_CONTEXT_EULA_FETCH_FAILED](-s-d-k_-c-o-n-t-e-x-t_-e-u-l-a_-f-e-t-c-h_-f-a-i-l-e-d/index.md) | EULA terms detail fetching failed. |
| [SDK_CONTEXT_HMAC_NOT_AVAILABLE](-s-d-k_-c-o-n-t-e-x-t_-h-m-a-c_-n-o-t_-a-v-a-i-l-a-b-l-e/index.md) | Registration must be performed first to fetch the HMAC instance. |
| [SDK_CONTEXT_CREDENTIALS_VALIDATION_FAILED](-s-d-k_-c-o-n-t-e-x-t_-c-r-e-d-e-n-t-i-a-l-s_-v-a-l-i-d-a-t-i-o-n_-f-a-i-l-e-d/index.md) | Supplied user credentials validation failed. |
| [SDK_CONTEXT_GROUP_VALIDATION_FAILED](-s-d-k_-c-o-n-t-e-x-t_-g-r-o-u-p_-v-a-l-i-d-a-t-i-o-n_-f-a-i-l-e-d/index.md) | Validation of Group ID identifier failed. |
| [SDK_CONTEXT_URL_NOT_VALID](-s-d-k_-c-o-n-t-e-x-t_-u-r-l_-n-o-t_-v-a-l-i-d/index.md) | Server connection failed with the provided URL. |
| [SDK_CONTEXT_NOT_ABLE_TO_INITIALIZE](-s-d-k_-c-o-n-t-e-x-t_-n-o-t_-a-b-l-e_-t-o_-i-n-i-t-i-a-l-i-z-e/index.md) | Failed to initialize SDK framework; commonly because access is disabled or not a managed app. |
| [SDK_CONTEXT_NOT_ABLE_TO_FETCH_APP_SETTING](-s-d-k_-c-o-n-t-e-x-t_-n-o-t_-a-b-l-e_-t-o_-f-e-t-c-h_-a-p-p_-s-e-t-t-i-n-g/index.md) | Failed to download Application settings. The application likely requires the user to log in first. |
| [SDK_CONTEXT_NOT_ABLE_TO_FETCH_SDK_SETTING](-s-d-k_-c-o-n-t-e-x-t_-n-o-t_-a-b-l-e_-t-o_-f-e-t-c-h_-s-d-k_-s-e-t-t-i-n-g/index.md) | Failed to download SDK settings. The application likely requires the user to log in first. |
| [SDK_CONTEXT_NO_NETWORK](-s-d-k_-c-o-n-t-e-x-t_-n-o_-n-e-t-w-o-r-k/index.md) | No network connectivity is found while performing an operation. |
| [SDK_CONTEXT_MANAGER_SERVER_URL_MUST_VALIDATE](-s-d-k_-c-o-n-t-e-x-t_-m-a-n-a-g-e-r_-s-e-r-v-e-r_-u-r-l_-m-u-s-t_-v-a-l-i-d-a-t-e/index.md) | The provided server URL needs to be validated. |
| [SDK_CONTEXT_MANAGER_MUST_INIT_FIRST](-s-d-k_-c-o-n-t-e-x-t_-m-a-n-a-g-e-r_-m-u-s-t_-i-n-i-t_-f-i-r-s-t/index.md) | Context manager needs to be initialized before use. |
| [SDK_RES_DEVICE_INIT_WITHOUT_CONTEXT](-s-d-k_-r-e-s_-d-e-v-i-c-e_-i-n-i-t_-w-i-t-h-o-u-t_-c-o-n-t-e-x-t/index.md) | Device initialization requested without a valid Context. |
| [SDK_RES_DEVICE_SERVICE_NOT_AVAILABLE](-s-d-k_-r-e-s_-d-e-v-i-c-e_-s-e-r-v-i-c-e_-n-o-t_-a-v-a-i-l-a-b-l-e/index.md) | Could not communicate with WS1 MDM service or service intent is unavailable. |
| [SDK_RES_METHOD_NOT_AVAILABLE_WITH_ANCHOR_APP](-s-d-k_-r-e-s_-m-e-t-h-o-d_-n-o-t_-a-v-a-i-l-a-b-l-e_-w-i-t-h_-a-n-c-h-o-r_-a-p-p/index.md) | Method called is not supported on the currently installed version of anchor application. |
| [SDK_RES_DEVICE_NOT_ENROLLED](-s-d-k_-r-e-s_-d-e-v-i-c-e_-n-o-t_-e-n-r-o-l-l-e-d/index.md) | Device is not enrolled in WS1 MDM. |
| [SDK_RES_WEB_SERVICE_ERROR](-s-d-k_-r-e-s_-w-e-b_-s-e-r-v-i-c-e_-e-r-r-o-r/index.md) | Network web service returned an error. |
| [SDK_RES_INVALID_ARGUMENT](-s-d-k_-r-e-s_-i-n-v-a-l-i-d_-a-r-g-u-m-e-n-t/index.md) | The argument provided in the API method call was invalid. |
| [SDK_RES_UNEXPECTED_EXCEPTION](-s-d-k_-r-e-s_-u-n-e-x-p-e-c-t-e-d_-e-x-c-e-p-t-i-o-n/index.md) | An unexpected exception occurred during SDK operations. |
| [SDK_RES_UNAUTHORIZED_ACCESS](-s-d-k_-r-e-s_-u-n-a-u-t-h-o-r-i-z-e-d_-a-c-c-e-s-s/index.md) | Unauthorized access. Disallowed application or action. |
| [SDK_RES_FAIL](-s-d-k_-r-e-s_-f-a-i-l/index.md) | Operation failed. General failure code. |
| [SDK_RES_SUCCESS](-s-d-k_-r-e-s_-s-u-c-c-e-s-s/index.md) | Operation executed successfully. |

## Functions

| Name | Summary |
|---|---|
| [getStatusCode](get-status-code.md) | open fun [getStatusCode](get-status-code.md)(): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin-stdlib/kotlin/-int/index.html)<br>Provides code associated with current Status Message |
| [getStatusMessage](get-status-message.md) | open fun [getStatusMessage](get-status-message.md)(): [String](https://developer.android.com/reference/kotlin/java/lang/String.html)<br>Provides message associated with current Status Code |
