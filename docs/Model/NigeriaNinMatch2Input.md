# NigeriaNinMatch2Input

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id_number** | **string** | National Identification Number (NIN).              This is a unique, permanent identifier assigned by the National Identity Management Commission (NIMC) upon enrollment.              Format: - 11 numeric digits - No publicly known encoding scheme is used to encode personal information in the NIN - Last digit is a checksum using the Verhoeff algorithm | [optional]
**given_name** | **string** | The user&#39;s first name as it appears in their National ID | [optional]
**family_name** | **string** | The user&#39;s last name as it appears in their National ID | [optional]
**middle_name** | **string** | The user&#39;s middle name as it appears in their National ID (optional) | [optional]
**date_of_birth** | **\DateTime** | The user&#39;s date of birth, in &#x60;YYYY-MM-DD&#x60; format | [optional]
**sex** | [**\Trinsic\Api\Model\NigeriaNinMatch2InputSex**](NigeriaNinMatch2InputSex.md) | The user&#39;s sex as it appears in their National ID | [optional]
**phone_number** | **string** | The user&#39;s phone number as it appears in their National ID (optional). Must be in E.164 international format: \&quot;+234XXXXXXXXX\&quot; | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
