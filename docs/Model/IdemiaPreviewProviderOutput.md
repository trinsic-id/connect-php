# IdemiaPreviewProviderOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**sub** | **string** | The OpenID Connect subject identifier for the verified individual. | [optional]
**name** | **string** | The individual&#39;s full name. | [optional]
**given_name** | **string** | The individual&#39;s given name. | [optional]
**middle_name** | **string** | The individual&#39;s middle name. | [optional]
**family_name** | **string** | The individual&#39;s family name. | [optional]
**nickname** | **string** | The individual&#39;s nickname. | [optional]
**preferred_username** | **string** | The individual&#39;s preferred username. | [optional]
**profile** | **string** | The individual&#39;s profile URL. | [optional]
**picture** | **string** | URL of the individual&#39;s profile picture. | [optional]
**website** | **string** | The individual&#39;s website URL. | [optional]
**birthdate** | **string** | The individual&#39;s date of birth in YYYY-MM-DD format. | [optional]
**date_of_birth** | **\DateTime** | The individual&#39;s date of birth as returned by legacy Idemia claim sets. | [optional]
**gender** | **string** | The individual&#39;s gender. | [optional]
**zoneinfo** | **string** | The individual&#39;s time zone. | [optional]
**locale** | **string** | The individual&#39;s locale. | [optional]
**preferred_language** | **string** | The individual&#39;s preferred language. | [optional]
**updated_at** | **int** | Timestamp when the individual&#39;s profile data was last updated. | [optional]
**email** | **string** | The individual&#39;s email address. | [optional]
**email_verified** | **bool** | Whether the individual&#39;s email address has been verified. | [optional]
**phone_number** | **string** | The individual&#39;s phone number. | [optional]
**phone_number_verified** | **bool** | Whether the individual&#39;s phone number has been verified. | [optional]
**mobile_phone_number** | **string** | The individual&#39;s mobile phone number returned by the mobile_phone scope. | [optional]
**address** | [**\Trinsic\Api\Model\IdemiaPreviewProviderAddress**](IdemiaPreviewProviderAddress.md) | The individual&#39;s address. | [optional]
**pcr** | **string** | Idemia pairwise relying-party correlation reference. | [optional]
**mid_uid** | **string** | Idemia Mobile ID unique identifier. | [optional]
**user_name** | **string** | The user name returned by Idemia. | [optional]
**inum** | **string** | Idemia client information identifier. | [optional]
**role** | **string** | Permission role returned by Idemia. | [optional]
**personal_identity_code** | **string** | Personal identity code returned by Idemia when available. | [optional]
**person_identity_code_sample** | **string** | Sample personal identity code returned by Idemia when available. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
