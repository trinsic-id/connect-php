# EvrotrustProviderOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**names** | **string** | The full name of the individual. | [optional]
**latin_names** | **string** | The full Latin-script name of the individual. | [optional]
**first_name** | **string** | The given name of the individual. | [optional]
**middle_name** | **string** | The middle name of the individual. | [optional]
**last_name** | **string** | The family name of the individual. | [optional]
**first_name_latin** | **string** | The Latin-script given name of the individual. | [optional]
**middle_name_latin** | **string** | The Latin-script middle name of the individual. | [optional]
**last_name_latin** | **string** | The Latin-script family name of the individual. | [optional]
**nationality** | **string** | The nationality label of the individual. | [optional]
**nationality_country** | **string** | The nationality country of the individual. | [optional]
**nationality_country_code** | **string** | The nationality country code of the individual.              Evrotrust uses ISO 3166-1 alpha-3 country codes. | [optional]
**gender** | **string** | The gender label of the individual.              Known values in Evrotrust API docs: - Male: the individual is male. - Female: the individual is female. | [optional]
**gender_latin** | **string** | The Latin-script gender label of the individual.              Known values in Evrotrust API docs: - Male: the individual is male. - Female: the individual is female. | [optional]
**user_gender** | **string** | The gender value from Evrotrust&#39;s user data object.              Evrotrust documents this separately from the identification metadata gender labels. Known values: - Male: the individual is male. - Female: the individual is female. | [optional]
**date_of_birth** | **\DateTime** | The date of birth of the individual in YYYY-MM-DD format. | [optional]
**place_of_birth** | **string** | The place of birth of the individual, if available. | [optional]
**identification_number** | **string** | The national identification number of the individual.              The format depends on the verified document and issuing country. | [optional]
**document_type** | **string** | The localized document type label of the identity document.              For Evrotrust&#39;s canonical document type code, see &#x60;docType&#x60;. | [optional]
**doc_type** | **string** | The canonical Evrotrust document type code.              Known values: - IDcard: an identity card. - Passport: a passport. | [optional]
**document_number** | **string** | The identity document number. | [optional]
**document_issuer_name** | **string** | The name of the authority that issued the identity document. | [optional]
**document_issue_date** | **\DateTime** | The identity document issue date in YYYY-MM-DD format.              Evrotrust documents timestamp &#x60;0&#x60; for this field as no value; it is omitted from provider-specific output. | [optional]
**document_valid_date** | **\DateTime** | The identity document expiration date in YYYY-MM-DD format.              Evrotrust documents timestamp &#x60;0&#x60; for this field as no value; it is omitted from provider-specific output. | [optional]
**document_country** | **string** | The identity document issuing country. | [optional]
**document_country_code** | **string** | The identity document issuing country code.              Evrotrust uses ISO 3166-1 alpha-3 country codes. | [optional]
**address** | **string** | The full address of the individual. | [optional]
**address_components** | [**\Trinsic\Api\Model\EvrotrustAddressComponents**](EvrotrustAddressComponents.md) | The structured address fragments of the individual, if available. | [optional]
**email_addresses** | **string[]** | The email addresses of the individual, if available. | [optional]
**phone_numbers** | **string[]** | The phone numbers of the individual in E.164 format, if available. | [optional]
**identification_reason** | **string** | The relying party-provided reason for requesting identification. | [optional]
**identification_before** | **string** | The deadline or contextual value supplied for the identification request. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
