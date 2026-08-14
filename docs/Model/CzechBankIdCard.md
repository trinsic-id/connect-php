# CzechBankIdCard

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | The identity document type code.              Possible values are:              - ID - Identity card - P - Passport - DL - Driving license - IR - Residence permit - VS - Visa permit label - PS - Residential label - IX - Book with residence permit - IE - Form with temporary residence - OP - Identity card – without machine readable zone - CA - Passport of the Czech Republic resident – without machine readable zone - UNKNOWN - Unknown id card type | [optional]
**description** | **string** | The localized identity document type description. | [optional]
**country** | **string** | The country for which the identity document is valid. | [optional]
**number** | **string** | The identity document number. | [optional]
**valid_to** | **\DateTime** | The identity document expiration date. | [optional]
**issuer** | **string** | The office that issued the identity document. | [optional]
**issue_date** | **\DateTime** | The identity document issue date. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
