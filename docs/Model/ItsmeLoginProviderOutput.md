# ItsmeLoginProviderOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**first_name** | **string** | The first name of the verified individual | [optional]
**last_name** | **string** | The last name of the verified individual | [optional]
**date_of_birth** | **\DateTime** | The date of birth of the verified individual | [optional]
**hashed_national_register_number** | **string** | The hashed version of the Belgian National Register Number of the verified individual.              By default, itsme does not return the raw National Register Number of the individual; instead, only a hashed version is returned.              Your account must be approved by itsme to receive the raw, unhashed National Register Number. | [optional]
**national_register_number** | **string** | The raw (not hashed) Belgian National Register Number (\&quot;Rijksregisternummer\&quot;) of the verified individual.              Only returned if your account has been explicitly authorized to receive it by itsme; by law, this data is considered sensitive personal data.              This is an 11-digit number in the format YYMMDDXXXCC, where: - YYMMDD represents the individual&#39;s date of birth (year, month, day). - XXX is a sequential birth number, odd for females and even for males. - CC is a checksum, calculated with the equation: 97 - (YYMMDDXXX mod 97)              For births in the year 2000 or later, the digit &#39;2&#39; is prepended to the first 9 digits during checksum calculation. | [optional]
**email** | **string** | The individual&#39;s email address. | [optional]
**phone_number** | **string** | The individual&#39;s phone number in international format. | [optional]
**gender** | **string** | The individual&#39;s gender.              Possible values: - Male - Female - Unknown - Not Applicable | [optional]
**nationality** | **string** | The individual&#39;s nationality as an ISO 3166-1 alpha-3 code. | [optional]
**birth_place** | **string** | The individual&#39;s place of birth. | [optional]
**document_number** | **string** | The document number | [optional]
**identity_document_expiration_date** | **\DateTime** | The expiration date of the identity document. | [optional]
**language** | **string** | The individual&#39;s language as an ISO 639-1 code. Expected values: NL, FR, DE, EN. | [optional]
**address** | [**\Trinsic\Api\Model\ItsmeAddress**](ItsmeAddress.md) | The individual&#39;s address | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
