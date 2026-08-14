# NigeriaNinLookup3ProviderOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**national_identity_number** | **string** | National Identification Number (NIN).              This is a unique, permanent identifier assigned by the National Identity Management Commission (NIMC) upon enrollment.              Format: - 11 numeric digits - No publicly known encoding scheme is used to encode personal information in the NIN - Last digit is a checksum using the Verhoeff algorithm | [optional]
**given_name** | **string** | The given name of the individual. | [optional]
**middle_name** | **string** | The middle name of the individual. | [optional]
**family_name** | **string** | The family name of the individual. | [optional]
**sex** | **string** | The sex of the individual.              Possible values: - Male - Female | [optional]
**date_of_birth** | **\DateTime** | The date of birth of the individual. | [optional]
**birth_country** | **string** | Country of birth as an ISO 3166-1 alpha-2 code. | [optional]
**birth_state** | **string** | State of birth as recorded by National Identity Management Commission (NIMC). | [optional]
**phone_number** | **string** | Phone number registered with National Identity Management Commission (NIMC).              Format: - International E.164 | [optional]
**street_address** | **string** | Street or residence line registered with National Identity Management Commission (NIMC).              This is the street-level address line only. Town, Local Government Area, and state are returned separately. | [optional]
**residence_town** | **string** | Town of residence registered with National Identity Management Commission (NIMC). | [optional]
**local_government_area** | **string** | Local Government Area of residence.              Nigeria is divided into 774 Local Government Areas (LGAs), which are the third-tier administrative divisions below states and the Federal Capital Territory. LGAs are roughly equivalent to counties or municipalities in other countries. | [optional]
**state** | **string** | State of residence registered with National Identity Management Commission (NIMC). | [optional]
**next_of_kin_first_name** | **string** | First name of the individual&#39;s next of kin. | [optional]
**next_of_kin_street_address** | **string** | Street or residence line of the individual&#39;s next of kin. | [optional]
**next_of_kin_local_government_area** | **string** | Local Government Area of the individual&#39;s next of kin. | [optional]
**next_of_kin_town** | **string** | Town of residence of the individual&#39;s next of kin. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
