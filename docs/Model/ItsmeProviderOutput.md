# ItsmeProviderOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**date_of_birth** | **\DateTime** | The date of birth of the verified individual.              Availability by ID document issuing country: always returned for supported issuing countries except Belgium, where it is best effort. | [optional]
**email** | **string** | The email address of the verified individual.              Availability by ID document issuing country: best effort for all supported issuing countries. | [optional]
**phone_number** | **string** | The phone number of the verified individual, with a leading + country calling code.              Availability by ID document issuing country: always returned for all supported issuing countries. | [optional]
**sub** | **string** | The stable OpenID Connect (OIDC) subject (sub) identifier.              This should be a stable identifier, however, if a user deletes and recreates an account, this identifier will change. | [optional]
**full_name** | **string** | The full name of the verified individual.              Availability by ID document issuing country: always returned for all supported issuing countries. | [optional]
**given_name** | **string** | The given name of the verified individual.              Availability by ID document issuing country: best effort for all supported issuing countries. | [optional]
**family_name** | **string** | The family name of the verified individual.              Availability by ID document issuing country: always returned for all supported issuing countries. | [optional]
**date_of_birth_as_string** | **string** | The date of birth of the verified individual in itsme&#39;s document-facing string format.              Availability by ID document issuing country: best effort for Belgian-issued ID documents; not returned for other supported issuing countries. | [optional]
**gender** | **string** | The gender claim for the verified individual.              Availability by ID document issuing country: always returned for supported issuing countries except Netherlands, where it is best effort.              Known values: - Female - Male - Unknown | [optional]
**locale** | **string** | The itsme app language as an uppercase language code.              Availability by ID document issuing country: best effort for all supported issuing countries.              Known values: - NL - FR - DE - EN | [optional]
**picture_url** | **string** | The URL of the profile picture resource.              Availability by ID document issuing country: always returned for supported issuing countries except Belgium, where it is best effort. | [optional]
**email_verified** | **bool** | Whether itsme reports the email address as verified.              Availability by ID document issuing country: returned only if &#x60;email&#x60; is available.              Note: itsme currently documents that this value is usually false because email verification is not implemented in its systems. | [optional]
**phone_number_verified** | **bool** | Whether itsme reports the phone number as verified.              Availability by ID document issuing country: always returned for all supported issuing countries. | [optional]
**address** | [**\Trinsic\Api\Model\ItsmeProviderAddress**](ItsmeProviderAddress.md) | The address of the verified individual.              Availability by ID document issuing country: always returned for Belgian-issued ID documents, best effort for Netherlands-issued ID documents, and not returned for other supported issuing countries. | [optional]
**citizenship** | **string** | The citizenship of the verified individual as an ISO 3166-1 alpha-2 country code.              Availability by ID document issuing country: always returned for supported issuing countries except Belgium, where it is best effort. | [optional]
**belgian_national_number** | [**\Trinsic\Api\Model\ItsmeBelgianNationalNumber**](ItsmeBelgianNationalNumber.md) | The Belgian National Register Number and related metadata.              Availability by ID document issuing country: returned only for Belgian-issued ID documents. | [optional]
**belgian_identity_card** | [**\Trinsic\Api\Model\ItsmeBelgianIdentityCard**](ItsmeBelgianIdentityCard.md) | The Belgian eID card document number and related metadata.              Availability by ID document issuing country: returned only for Belgian-issued ID documents. | [optional]
**identity_document** | [**\Trinsic\Api\Model\ItsmeIdentityDocument**](ItsmeIdentityDocument.md) | The identity document and related metadata.              Availability by ID document issuing country: always returned for all supported issuing countries. | [optional]
**place_of_birth** | [**\Trinsic\Api\Model\ItsmePlaceOfBirth**](ItsmePlaceOfBirth.md) | The place of birth.              Availability by ID document issuing country: best effort for Belgian-issued ID documents; not returned for other supported issuing countries. | [optional]
**device** | [**\Trinsic\Api\Model\ItsmeDirectDevice**](ItsmeDirectDevice.md) | The device metadata for the verification.              Availability by ID document issuing country: best effort for all supported issuing countries. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
