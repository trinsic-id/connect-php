# DiiaIssuerOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**common_name** | **string** | Certificate issuer common name. | [optional]
**organization** | **string** | Certificate issuer organization. | [optional]
**country** | **string** | Issuer country code in ISO 3166-1 alpha-2 format. | [optional]
**locality** | **string** | City or region where the issuer is located. | [optional]
**serial_number** | **string** | Unique identifier assigned to the issuing certificate authority.              Typically formatted as \&quot;{country}-{registration code}-{sequence}\&quot;. | [optional]
**national_registration_number** | **string** | The organizationIdentifier attribute from the certificate Issuer Distinguished Name.              Ukrainian organization identifiers commonly use the ETSI format \&quot;{identifier-type}{country-code}-{identifier}\&quot;.              Components: - identifier-type (3 chars): NTR (National Trade Register). - country-code (2 chars): ISO 3166-1 alpha-2 country code, typically UA. - identifier: The legal entity registration code.              For Diia.Signature, this is issuer metadata rather than a natural person&#39;s RNOKPP. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
