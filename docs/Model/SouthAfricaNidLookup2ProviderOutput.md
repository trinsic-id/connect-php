# SouthAfricaNidLookup2ProviderOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**national_id_number** | **string** | The South African National Identity Number (13 digits).              Issued for life by the Department of Home Affairs (DHA) and stored in the HANIS (Home Affairs National Identification System) database. The same number is mandatory for banking, employment, taxation, and voting, and is printed on both the legacy green ID book and the Smart ID Card (rolled out from 2013 onward).              Format: - YYMMDD G(4) C A Z - YYMMDD is the date of birth - G(4) is the gender code (below 5000 female, 5000 or above male) - C is the citizenship indicator (0 citizen, 1 permanent resident) - A is reserved (it had a politically sensitive meaning in the past, but is currently   semantically meaningless) - Z is a Luhn check digit | [optional]
**citizenship_status** | **string** | Citizenship status of the individual.              Possible values: - Citizen - PermanentResident - Refugee | [optional]
**first_name** | **string** | First name of the individual. | [optional]
**family_name** | **string** | Family name of the individual. | [optional]
**full_name** | **string** | Full name of the individual. | [optional]
**sex** | **string** | Sex of the individual.              Possible values: - Male - Female | [optional]
**date_of_birth** | **\DateTime** | Date of birth of the individual. | [optional]
**nationality** | **string** | Nationality of the individual as an ISO 3166-1 alpha-2 country code.              Set to ZA when CitizenshipStatus is Citizen. Null when not a South African citizen (Permanent Resident or Refugee). | [optional]
**date_of_death** | **\DateTime** | Date of death of the individual, if recorded by DHA (Department of Home Affairs).              Null if the individual is alive, or the data is missing from the registry. | [optional]
**birth_country** | **string** | Country of birth of the individual as an ISO 3166-1 alpha-2 country code. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
