# DiiaSubjectOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**common_name** | **string** | Full name. | [optional]
**country** | **string** | Country code in ISO 3166-1 alpha-2 format. | [optional]
**serial_number** | **string** | The SERIALNUMBER attribute from the certificate Subject Distinguished Name. This is not the X.509 certificate serial number field.              For Ukrainian natural person certificates this commonly uses the ETSI natural person semantics identifier format \&quot;{identifier-type}{country-code}-{identifier}\&quot;.              Components: - identifier-type (3 chars): TIN (Tax Identification Number) for RNOKPP. - country-code (2 chars): ISO 3166-1 alpha-2 country code, typically UA. - identifier: RNOKPP, the Ukrainian individual taxpayer registration number. | [optional]
**given_name** | **string** | Given name. | [optional]
**surname** | **string** | Surname. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
