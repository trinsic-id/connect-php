# KoreaTelcoMatchProviderOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**phone_number** | **string** | The phone number submitted for the carrier match. | [optional]
**tele_type** | **string** | The mobile carrier used for the match.              Supported values: Lgu, Skt, Kt. | [optional]
**result_code** | **string** | The carrier match result code.              Common result codes: - \&quot;0000\&quot;: Successful match - \&quot;0001\&quot;: Failed - Verification Information Mismatch (General) - \&quot;0002\&quot;: Failed - Unable to Verify Phone Number - \&quot;0004\&quot;: Failed - Date of Birth Verification Error - \&quot;0005\&quot;: Failed - Gender Verification Error - \&quot;0006\&quot;: Failed - Name Verification Error - \&quot;0009\&quot;: Failed - Device OS Mismatch | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
