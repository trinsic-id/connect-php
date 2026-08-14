# Iso180132BiometricTemplateHeader

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**patron_header_version** | **int** | Patron header version (defaults to 0x0101). | [optional]
**biometric_type** | **int** | Biometric type code per ISO 18013-2. | [optional]
**biometric_sub_type** | **int** | Biometric sub-type code per ISO 18013-2. | [optional]
**creation_date** | **\DateTime** | Date and time the biometric template was created. | [optional]
**biometric_information_record_creator** | **string** | Name of the Biometric Information Record (BIR) creator. | [optional]
**validity_period** | [**\Trinsic\Api\Model\Iso180132BiometricValidityPeriod**](Iso180132BiometricValidityPeriod.md) | Validity period of the biometric data block. | [optional]
**biometric_data_block_product** | [**\Trinsic\Api\Model\Iso180132BiometricDataBlockProduct**](Iso180132BiometricDataBlockProduct.md) | Owner and type identifying the product that produced the biometric data block. | [optional]
**biometric_data_block_format_owner** | **int** | Format owner of the biometric data block. | [optional]
**biometric_data_block_format_type** | **int** | Format type of the biometric data block. | [optional]
**biometric_information_record_index** | **string** | Index identifier of the Biometric Information Record, when present. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
