# AppleWalletDigitalIdCredential

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**given_name_unicode** | **string** | First name(s), other name(s), or secondary identifier of the individual.              This field uses the full UTF-8 character set and can represent any name. | [optional]
**given_name_latin1** | **string** | First name(s), other name(s), or secondary identifier of the individual.              This field uses the Latin-1 character set and is limited to names represented by the English alphabet. represented using the English alphabet. | [optional]
**family_name_unicode** | **string** | Last name, surname, or primary identifier of the individual.              This field uses the full UTF-8 character set and can represent any name. | [optional]
**family_name_latin1** | **string** | Last name, surname, or primary identifier of the individual.              This field uses only the Latin-1 character set and is largely limited to names which can be represented using the English alphabet. | [optional]
**sex** | **int** | The individual&#39;s sex as an ISO/IEC 5218 code.              Possible values: - 0: Unknown - 1: Male - 2: Female - 9: Not Applicable | [optional]
**date_of_birth** | [**\Trinsic\Api\Model\AppleWalletDigitalIdBirthDate**](AppleWalletDigitalIdBirthDate.md) | The date of birth of the individual, possibly with an \&quot;approximate mask\&quot; indicating uncertain digits. | [optional]
**document_number** | **string** | The document number of the underlying passport used to create the Digital ID. | [optional]
**issuing_authority_unicode** | **string** | Name or identifier of the issuing authority of the credential, using the full UTF-8 character set.              This field&#39;s contents are arbitrary; it has no guaranteed format. | [optional]
**issuing_subdivision** | **string** | ISO 3166-2 country-subdivision code for the jurisdiction that issued the credential. | [optional]
**issuing_country** | **string** | ISO 3166-1 alpha-2 country code of the issuing authority&#39;s country or territory. | [optional]
**issue_date** | **\DateTime** | Date when the underlying passport used to create the Digital ID was issued. | [optional]
**expiry_date** | **\DateTime** | Date when the underlying passport used to create the Digital ID expires. | [optional]
**age_in_years** | **int** | The age of the individual, as of the issuance date of the credential. | [optional]
**age_over** | [**\Trinsic\Api\Model\AgeOverOutput[]**](AgeOverOutput.md) | Processed age-over claims returned by the credential. | [optional]
**resident_address_unicode** | **string** | The permanent address of the individual, using the full UTF-8 character set.              This is only present if the underlying passport contained an address, which is uncommon. | [optional]
**resident_city_unicode** | **string** | City of the individual&#39;s permanent address, using the full UTF-8 character set.              This is only present if the underlying passport contained an address, which is uncommon. | [optional]
**resident_city_latin1** | **string** | City of the individual&#39;s permanent address, using the Latin-1 character set.              This is only present if the underlying passport contained an address, which is uncommon. | [optional]
**resident_postal_code** | **string** | Postal code of the individual&#39;s permanent address.              This is only present if the underlying passport contained an address, which is uncommon. | [optional]
**resident_country** | **string** | ISO 3166-1 alpha-2 country code of the individual&#39;s permanent address.              This is only present if the underlying passport contained an address, which is uncommon. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
