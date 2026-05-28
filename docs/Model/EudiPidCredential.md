# EudiPidCredential

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**given_name** | **string** | Current first name(s), including middle name(s) where applicable, of the individual to whom the PID relates. | [optional]
**given_name_birth** | **string** | First name(s), including middle name(s), of the individual at the time of birth. | [optional]
**family_name** | **string** | Current last name(s) or surname(s) of the individuals. | [optional]
**family_name_birth** | **string** | Last name(s) or surname(s) of the individual at the time of birth. | [optional]
**date_of_birth** | **\DateTime** | The date of birth of the individual. | [optional]
**birth_place** | **string** | Country (ISO 3166-1 alpha-2), state, province, district, local area, municipality, city, town, or village where the individual was born. | [optional]
**nationality** | **string[]** | One or more ISO 3166-1 alpha-2 country codes representing the nationality of the individual. | [optional]
**expiry_date** | **\DateTime** | Date when the PID expires.              Because PIDs are not necessarily backed by a physical document, this does not correspond to the expiration date of such. | [optional]
**issuing_authority** | **string** | Name of the administrative authority that issued the PID, or the ISO 3166 alpha-2 country code of the respective Member State if there is no separate authority entitled to issue PIDs. | [optional]
**issuing_country** | **string** | ISO 3166-1 alpha-2 country code of the country or territory of the issuer of the PID. | [optional]
**issuance_date** | **\DateTime** | Date when the PID was issued and/or the administrative validity period began. | [optional]
**trust_anchor** | **string** | URL where a machine-readable trust anchor for verifying the PID can be found. | [optional]
**attestation_legal_category** | **string** | Indicator that this credential has been issued specifically as PID.              When present, typically equal to \&quot;PID\&quot;. | [optional]
**document_number** | **string** | A number assigned to the PID by the issuer.              This does not correspond to the document number of a physical document. | [optional]
**issuing_jurisdiction** | **string** | ISO 3166-2 country-subdivision code for the jurisdiction that issued the PID. | [optional]
**location_status** | **string** | Location of validity status information for the PID, where revocation information is published. | [optional]
**sex** | **int** | Sex of the individual.              This is a superset of the ISO/IEC 5218 sex code standard, defining additional \&quot;other\&quot;, \&quot;inter\&quot;, \&quot;diverse\&quot;, and \&quot;open\&quot; values.              Possible values: - 0: Unknown - 1: Male - 2: Female - 3: Other - 4: Inter - 5: Diverse - 6: Open - 9: Not Applicable              For values 0, 1, 2, and 9, ISO/IEC 5218 applies. | [optional]
**email_address** | **string** | The individual&#39;s email address. | [optional]
**mobile_phone_number** | **string** | The mobile phone number of the individual, in international format. | [optional]
**personal_administrative_number** | **string** | A value assigned to the individual that is unique among all personal administrative numbers issued by the provider. | [optional]
**resident_address** | **string** | The full address of the individual&#39;s permanent residence. | [optional]
**resident_street** | **string** | The street name of the individual&#39;s permanent residence. | [optional]
**resident_house_number** | **string** | The house number of the individual&#39;s permanent residence. | [optional]
**resident_city** | **string** | The municipality, city, town, or village of the individual&#39;s permanent residence. | [optional]
**resident_state** | **string** | The state, province, district, or local area of the individual&#39;s permanent residence. | [optional]
**resident_postal_code** | **string** | The postal code of the individual&#39;s permanent residence. | [optional]
**resident_country** | **string** | The ISO 3166-1 alpha-2 country code of the individual&#39;s permanent residence. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
