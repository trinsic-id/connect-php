# CzechBankIdAddress

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | The address type.              Possible values are: - PERMANENT_RESIDENCE - SECONDARY_RESIDENCE - UNKNOWN | [optional]
**street** | **string** | The street name.              This is usually present, but unused for small villages. | [optional]
**building_apartment** | **string** | The address land registry number.              This is usually present, but unused for small houses. | [optional]
**street_number** | **string** | The additional address house number.              This is usually present, but unused for small villages. | [optional]
**evidence_number** | **string** | The house evidence number.              This is rarely used in suburbs. An evidence number is used for addresses that are residential, temporary or non-residential buildings, e.g. cabins, garages etc. | [optional]
**city** | **string** | The city name. |
**city_area** | **string** | The city area name.              This is usually present. | [optional]
**zipcode** | **string** | The zip of the address. |
**country** | **string** | The country code in ISO 3166-1 alpha-2 format. |
**ruian_reference** | **string** | The address identifier in the Czech RUIAN address register.              RUIAN is the Czech Register of Territorial Identification, Addresses, and Real Estate. This value identifies the address record in that register and can be used to reconcile the address against Czech government address data. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
