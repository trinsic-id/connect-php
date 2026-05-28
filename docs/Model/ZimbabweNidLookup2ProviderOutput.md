# ZimbabweNidLookup2ProviderOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**national_id_number** | **string** | Zimbabwe National ID number (NID) issued by the Zimbabwean government.              Format: - 8-9 digits followed by 1 letter and 2 digits - Regex: /^[0-9]{8,9}[A-Za-z]\\d{2}$/ - There is no publicly documented encoding scheme for encoding personal information in the NID - No check digit or algorithm has been publicly documented by the Zimbabwean government |
**given_name** | **string** | Given name(s) of the individual. |
**family_name** | **string** | Family name of the individual. |
**full_name** | **string** | Full name of the individual. |
**sex** | **string** | Sex of the individual.              Possible values: - Male - Female - Not Applicable - Unknown |
**date_of_birth** | **\DateTime** | Date of birth of the individual. |
**place_of_birth** | **string** | Place of birth, typically a municipality or city within Zimbabwe. | [optional]
**is_alive** | **bool** | Whether individual is reported as alive by the Zimbabwean government. | [optional]
**date_of_death** | **\DateTime** | Date of death of the individual, when available. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
