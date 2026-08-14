# ClearProviderOutputCheck

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**verification_check_name** | **string** | The verification check name as specified in the CLEAR verification configuration. | [optional]
**value** | **bool** | The boolean check value.              This can be null when a check is skipped or unable to evaluate to a deterministic result. | [optional]
**status** | **string** | Whether CLEAR performed the check.              Known values: - completed - skipped - error | [optional]
**check_result** | **string** | The granular CLEAR result for this check.              Known values: - success - failure - indeterminate - not_applicable - awaiting_async_response | [optional]
**additional_details** | [**\Trinsic\Api\Model\ClearProviderOutputCheckAdditionalDetails**](ClearProviderOutputCheckAdditionalDetails.md) | Additional structured details CLEAR used for this check. Currently modeled details: watchlistHits. | [optional]
**params** | **array<string,mixed>** | Custom parameters configured for this CLEAR check. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
