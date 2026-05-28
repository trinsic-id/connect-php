# GoogleWalletIdPassCredential

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**given_name** | **string** | First name(s), other name(s), or secondary identifier of the individual. | [optional]
**family_name** | **string** | Last name, surname, or primary identifier of the individual. | [optional]
**date_of_birth** | **\DateTime** | The date of birth of the individual. | [optional]
**issue_date** | **\DateTime** | The date when the ID Pass was issued.              This is not the same as the issue date of the underlying physical passport used to create the ID Pass. | [optional]
**expiry_date** | **\DateTime** | The date when the ID Pass expires.              This is not necessarily the same as the expiration date of the underlying physical passport used to create the ID Pass. | [optional]
**issuing_country** | **string** | Alpha-2 country code of the issuing authority&#39;s country or territory. | [optional]
**issuing_authority** | **string** | Name or identifier of the mDL issuing authority.              This field&#39;s contents are arbitrary; it has no guaranteed format. | [optional]
**nationality** | **string** | Nationality of the individual as an ISO 3166-1 alpha-2 country code. | [optional]
**document_number** | **string** | The number of the underlying passport used to create the ID Pass. | [optional]
**sex** | **int** | The individual&#39;s sex as an ISO/IEC 5218 code.              Possible values: - 0: Unknown - 1: Male - 2: Female - 9: Not Applicable | [optional]
**age_over** | [**\Trinsic\Api\Model\AgeOverOutput[]**](AgeOverOutput.md) | Processed age-over claims returned by the ID Pass. | [optional]
**issue_date_of_underlying_document** | **\DateTime** | Date when the underlying passport backing this digital credential was originally issued. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
