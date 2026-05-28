# Iso180132BiometricTemplate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**header** | [**\Trinsic\Api\Model\Iso180132BiometricTemplateHeader**](Iso180132BiometricTemplateHeader.md) | Header describing the biometric template. |
**data_block** | **string** | The raw data block, in a biometric type- and format-specific encoding.              For &#x60;face&#x60; and &#x60;signature_usual_mark&#x60;, this is a raw JPEG or JPEG2000 image.              See ISO 18013-2 and 18013-5. |
**data_is_encrypted** | **bool** | Whether the data block is encrypted. |
**biometric_information_record_payload** | **string** | Optional Biometric Information Record payload, containing arbitrary domestic data. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
