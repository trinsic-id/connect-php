# ClearProviderOutputDocument

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**nationality** | **string** | The nationality scanned from the document, normalized to an ISO 3166-1 alpha-2 country code. | [optional]
**document_type** | **string** | The document type scanned by CLEAR.              Known values: - drivers_license - paper_passport - passport_card - id_card - visa - health_care_card - other | [optional]
**issuing_country** | **string** | The ISO 3166-1 alpha-2 country code of issue. | [optional]
**issuing_subdivision** | **string** | The ISO 3166 subdivision issuer of the document. | [optional]
**document_number** | **string** | The document number scanned from the document. | [optional]
**date_of_expiry** | **\DateTime** | The document expiration date. | [optional]
**gender** | **string** | The gender scanned from the document. CLEAR does not publish a closed set of possible values for this field. | [optional]
**address** | [**\Trinsic\Api\Model\ClearProviderOutputAddress**](ClearProviderOutputAddress.md) | The address scanned from the document. | [optional]
**date_of_birth** | **\DateTime** | The date of birth scanned from the document. | [optional]
**first_name** | **string** | The first name scanned from the document. | [optional]
**last_name** | **string** | The last name scanned from the document. | [optional]
**middle_name** | **string** | The middle name scanned from the document. | [optional]
**full_name** | **string** | The full name scanned from the document. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
