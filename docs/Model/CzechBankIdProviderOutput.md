# CzechBankIdProviderOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**subject_identifier** | **string** | The subject identifier for the verified individual. |
**full_name** | **string** | The individual&#39;s full name. | [optional]
**given_name** | **string** | The individual&#39;s given or first name. | [optional]
**family_name** | **string** | The individual&#39;s family or last name. | [optional]
**middle_name** | **string** | The individual&#39;s middle name. | [optional]
**nickname** | **string** | Nickname used by a physical person              A casual name, not necessarily the legal given name. | [optional]
**preferred_username** | **string** | The individual&#39;s preferred username.              The user has chosen this as the preferred name for logins. | [optional]
**gender** | **string** | The individual&#39;s gender.              Possible values: - Male - Female - Other              Only returned for Identify verifications. | [optional]
**date_of_birth** | **string** | The individual&#39;s date of birth.              This is a string because the value may have reduced precision, such as only a year. | [optional]
**birth_number** | **string** | The individual&#39;s Czech birth number.              This value is written without the traditional forward slash. Czech birth numbers are Czech public-authority identifiers administered through the Ministry of Interior&#39;s birth-number register. The Ministry can assign one to Czech citizens and to foreign nationals with temporary or permanent residence in the Czech Republic. For foreign nationals, this is still a Czech birth number in the Czech format, not an identity number from another country.              The common current format is YYXXDDSSSC: - YY: Two digit birth year - XX: Encoded birth month, see below for encoding logic - DD: Birth day - SSS: Sequence number - C: Modulo-11 checksum digit. Not present for people born before 1954. The encoded month is MM for men, MM + 50 for women, and can be MM + 20 for men or MM + 70 for women when additional number ranges are needed. Older numbers for people born before 1954 can use YYXXDDSSS and do not use the modulo-11 checksum.              Only returned for Identify verifications. | [optional]
**age** | **int** | The individual&#39;s age. | [optional]
**is_adult** | **bool** | Whether the individual is an adult.              In the Czech Republic, legal majority (adulthood) is reached at 18 years old. Only returned for Identify Plus verifications. | [optional]
**date_of_death** | **\DateTime** | The individual&#39;s date of death, if available. | [optional]
**birth_place** | **string** | The individual&#39;s place of birth.              Only returned for Identify Plus verifications. | [optional]
**birth_country** | **string** | The individual&#39;s country of birth.              Only returned for Identify Plus verifications. | [optional]
**primary_nationality** | **string** | The individual&#39;s primary nationality.              The value is an ISO 3166-1 alpha-2 country code. Only returned for Identify Plus verifications. | [optional]
**nationalities** | **string[]** | The individual&#39;s nationalities. | [optional]
**marital_status** | **string** | The individual&#39;s marital status.              Possible values: - COHABITATION - MARRIED - DIVORCED - REGISTERED_PARTNERSHIP - REGISTERED_PARTNERSHIP_CANCELED - WIDOWED - SINGLE - PARTNERSHIP - PARTNERSHIP_CANCELED - SEPARATED - REGISTERED_PARTNERSHIP_WIDOWED - LAPSED_MARRIAGE - UNKNOWN              Only returned for Identify Plus verifications. | [optional]
**email** | **string** | The individual&#39;s email address. | [optional]
**email_verified** | **bool** | Whether the individual&#39;s email address has been verified. | [optional]
**phone_number** | **string** | The individual&#39;s phone number.              This value is normalized to E.164 format. | [optional]
**phone_number_verified** | **bool** | Whether the individual&#39;s phone number has been verified. | [optional]
**is_politically_exposed_person** | **bool** | Whether the individual is a politically exposed person.              This follows Czech anti-money-laundering rules, indicating a person that is at risk for corruption, bribery or money laundering activities. Mandatory screening of these individuals is required for compliance. Typically set for people such as the Prime Minister, ministers, etc. | [optional]
**limited_legal_capacity** | **bool** | Whether the individual is a person with limited legal capacity. | [optional]
**verification** | [**\Trinsic\Api\Model\CzechBankIdVerification**](CzechBankIdVerification.md) | Metadata about how the identity information was verified for Anti Money Laundering scope.              Only returned for Identify AML verifications. | [optional]
**addresses** | [**\Trinsic\Api\Model\CzechBankIdAddress[]**](CzechBankIdAddress.md) | The individual&#39;s addresses.              This can include permanent residence and contact addresses. Only returned for Identify verifications. | [optional]
**id_cards** | [**\Trinsic\Api\Model\CzechBankIdCard[]**](CzechBankIdCard.md) | The individual&#39;s identity documents.              This can include document type, country, number, issuer, and validity dates. Only returned for Identify Plus verifications. | [optional]
**updated_at** | **\DateTime** | The UTC date and time when the identity data was last updated. | [optional]
**zone_info** | **string** | The individual&#39;s time zone.              This is represented as a zoneinfo/IANA Time Zone Database value. | [optional]
**locale** | **string** | The individual&#39;s locale.              This is represented as a BCP 47/RFC 5646 language tag. Some values may use an underscore separator, such as cs_CZ. | [optional]
**titles** | [**\Trinsic\Api\Model\CzechBankIdTitle[]**](CzechBankIdTitle.md) | The individual&#39;s title prefixes and suffixes.              Only returned for Identify verifications. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
