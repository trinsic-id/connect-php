# VerimiProviderOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**full_name** | **string** | The full name of the individual. | [optional]
**date_of_birth** | **\DateTime** | The date of birth of the individual. | [optional]
**given_name** | **string** | The given name of the individual. | [optional]
**middle_name** | **string** | The middle name of the individual. | [optional]
**family_name** | **string** | The family name of the individual. | [optional]
**email** | **string** | The email address of the individual. | [optional]
**email_verified** | **bool** | Whether the email address has been verified by Verimi. | [optional]
**phone_number** | **string** | The phone number of the individual in E.164 format. | [optional]
**phone_number_verified** | **bool** | Whether the phone number has been verified by Verimi. | [optional]
**gender** | **string** | The gender of the individual. | [optional]
**zone_information** | **string** | The individual&#39;s time zone as an IANA Time Zone Database zoneinfo identifier. | [optional]
**locale** | **string** | The selected language or locale of the individual as a BCP 47 language tag. | [optional]
**citizenship** | **string** | The citizenship of the individual.              This is an ISO-3166-1 alpha-2 country code. | [optional]
**place_of_birth** | **string** | The place of birth of the individual. | [optional]
**document_number** | **string** | The document number of the identity document used by the individual. | [optional]
**document_type** | **string** | The identity document type.              Known values: - I: ID card. - P: Passport. | [optional]
**document_expiration_date** | **\DateTime** | The expiration date of the identity document. | [optional]
**document_issue_date** | **\DateTime** | The issue date of the identity document. | [optional]
**document_issuing_authority** | **string** | The authority that issued the identity document. | [optional]
**verification_method** | **string** | The verification method used to prove the individual&#39;s identity. | [optional]
**verification_date** | **\DateTime** | The date when the individual proved their identity with Verimi. | [optional]
**level_of_assurance** | **string** | The level of assurance for the verification.              Known values: - Low: The individual has self-asserted their identity. - Substantial: The individual has completed identity proofing and strong authentication. - High: The individual has completed identity proofing with stronger cryptographic authentication requirements. | [optional]
**authentication_method** | **string** | The authentication method for the completed identification.              Known values: - email - loa.dipp.default - loa.dipp.2fa - idcard | [optional]
**pseudonym** | **string** | The pseudonymous identifier.              For German eID, this is the restricted identifier (rID), scoped to the relying-party sector. | [optional]
**address** | [**\Trinsic\Api\Model\VerimiAddressOutput**](VerimiAddressOutput.md) | The individual&#39;s structured address. | [optional]
**issuing_country** | **string** | The ISO 3166-1 alpha-2 country code for the country that issued the identity document. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
