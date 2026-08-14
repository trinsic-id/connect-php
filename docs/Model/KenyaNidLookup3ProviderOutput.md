# KenyaNidLookup3ProviderOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id_number** | **string** | The Kenya National ID Number (Nambari ya Kitambulisho) or Unique Personal Identifier (Maisha Namba).              This is the primary unique identifier for Kenyan citizens in all government systems, issued by the National Registration Bureau (NRB). The format is either 8 digits for National ID or 9 digits for Maisha Namba UPI (the new format since 2023). | [optional]
**first_name** | **string** | The first name of the individual. | [optional]
**surname** | **string** | The surname of the individual. | [optional]
**other_name** | **string** | Other name (middle name) of the individual. | [optional]
**sex** | **string** | The sex of the individual.              Possible values: - Male - Female | [optional]
**date_of_birth** | **\DateTime** | The date of birth of the individual.              Format - YYYY-MM-DD | [optional]
**citizenship** | **string** | Citizenship of the individual.              Format - ISO 3166-1 alpha-2 country code | [optional]
**serial_number** | **string** | The physical card serial number printed on the Kenya National ID card.              This is distinct from the ID Number and serves as a card issuance tracking identifier maintained by IPRS. This value changes each time a new physical card is issued (loss, damage, renewal). | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
