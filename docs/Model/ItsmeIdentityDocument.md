# ItsmeIdentityDocument

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**serial_number** | **string** | The identity document serial number.              Availability by ID document issuing country: always returned for all supported issuing countries. | [optional]
**type_code** | **string** | The identity document type code.              Availability by ID document issuing country: always returned for all supported issuing countries.              itsme documents this as a 1 or 2 character ICAO code. - Identity cards start with &#x60;I&#x60; - passports start with &#x60;P&#x60; | [optional]
**issuing_country** | **string** | The issuing country as an ISO 3166-1 alpha-2 country code.              Availability by ID document issuing country: always returned for all supported issuing countries. | [optional]
**validity_from** | **\DateTime** | The identity document validity start date time.              Availability by ID document issuing country: best effort for Belgian-issued ID documents; not returned for other supported issuing countries. | [optional]
**validity_to** | **\DateTime** | The identity document validity end date time.              Availability by ID document issuing country: always returned for supported issuing countries except Belgium, where it is best effort. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
