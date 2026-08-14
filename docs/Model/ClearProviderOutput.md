# ClearProviderOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**authenticated** | **bool** | Whether CLEAR authenticated the individual. | [optional]
**authentication_methods** | **string[]** | The methods the individual authenticated with during the CLEAR flow.              Known values: - webauthn - email - sms_otp | [optional]
**activated_authentication_methods** | **string[]** | The authentication methods the individual activated but did not use as a pre-existing credential during this session.              Known values: - webauthn - totp | [optional]
**checks** | [**\Trinsic\Api\Model\ClearProviderOutputCheck[]**](ClearProviderOutputCheck.md) | The checks CLEAR performed on the individual&#39;s data and each check&#39;s result. | [optional]
**check_metadata** | **string[]** | CLEAR error or metadata codes that influenced check results. | [optional]
**completed_at** | **\DateTime** | The time the CLEAR verification session completed, as a UTC timestamp. | [optional]
**created_at** | **\DateTime** | The time the CLEAR verification session was created, as a UTC timestamp. | [optional]
**email** | **string** | The individual&#39;s verified email address from the session. | [optional]
**expires_at** | **\DateTime** | The time the CLEAR verification session expires, as a UTC timestamp. | [optional]
**fields_to_collect** | **string[]** | The fields CLEAR still required to complete the current verification step. | [optional]
**ip** | **string[]** | The IP addresses used to access this CLEAR verification session. | [optional]
**phone** | **string** | The individual&#39;s verified phone number, normalized to international E.164 format. | [optional]
**status** | **string** | The CLEAR verification session status.              Known values: - success - fail - awaiting_user_input - deferred - processing_data - expired - awaiting_manual_review - manual_success - manual_fail - canceled | [optional]
**updated_at** | **\DateTime** | The time the CLEAR verification session was most recently updated, as a UTC timestamp. | [optional]
**user_agent** | **string[]** | The browser user agents that accessed this CLEAR verification session. | [optional]
**user_created** | **bool** | Whether CLEAR created a new individual account during this session. | [optional]
**user_id** | **string** | The CLEAR identifier for the individual. | [optional]
**traits** | [**\Trinsic\Api\Model\ClearProviderOutputTraits**](ClearProviderOutputTraits.md) | The individual traits CLEAR returned after collecting enough information to make a decision. | [optional]
**idv_status** | **string** | The identity verification status.              Known documented value: - verified: CLEAR indicates the individual is verified. | [optional]
**sessions** | [**\Trinsic\Api\Model\ClearProviderOutputSessionInfo[]**](ClearProviderOutputSessionInfo.md) | Frontend session metadata CLEAR collected. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
