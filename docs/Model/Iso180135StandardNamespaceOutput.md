# Iso180135StandardNamespaceOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**given_name** | **string** | First name(s), other name(s), or secondary identifier of the individual. | [optional]
**given_name_national_character** | **string** | The given name of the individual using the full UTF-8 character set. | [optional]
**family_name** | **string** | Last name, surname, or primary identifier of the individual. | [optional]
**family_name_national_character** | **string** | The family name of the individual using the full UTF-8 character set. | [optional]
**date_of_birth** | **\DateTime** | The date of birth of the individual. | [optional]
**issue_date** | **\DateTime** | The date when the mDL was issued.              This date marks the beginning of the Administrative Validity Period of the mDL, which is usually (but not necessarily always) the same as the issue date of the underlying physical document used to create the mDL, if one exists. | [optional]
**expiry_date** | **\DateTime** | The date when the mDL expires.              This date marks the end of the Administrative Validity Period of the mDL, which is usually (but not necessarily always) the same as the expiration date of the underlying physical document used to create the mDL, if one exists. | [optional]
**issuing_country** | **string** | Alpha-2 country code of the issuing authority&#39;s country or territory. | [optional]
**issuing_authority** | **string** | Name or identifier of the mDL issuing authority.              This field&#39;s contents are arbitrary; it has no guaranteed format. | [optional]
**issuing_jurisdiction** | **string** | ISO 3166-2 country-subdivision code for the jurisdiction that issued the mDL. | [optional]
**nationality** | **string** | Nationality of the individual as an ISO 3166-1 alpha-2 country code. | [optional]
**document_number** | **string** | The document number assigned to the mDL.              This is typically the same as the document number of the underlying physical document used to create the mDL, if one exists. | [optional]
**driving_privileges** | [**\Trinsic\Api\Model\Iso180135DrivingPrivilege[]**](Iso180135DrivingPrivilege.md) | Driving privileges of the individual, parsed per ISO 18013-5. | [optional]
**un_distinguishing_sign** | **string** | The UN Distinguishing sign of the issuing country according to ISO/IEC 18013-1. | [optional]
**administrative_number** | **string** | Audit control number assigned by the issuing authority.              The meaning and semantics of this field are defined by the issuing authority in question. | [optional]
**sex** | **int** | The individual&#39;s sex as an ISO/IEC 5218 code.              Possible values:              - 0: Unknown - 1: Male - 2: Female - 9: Not Applicable | [optional]
**height_centimeters** | **int** | The individual&#39;s height in centimeters. | [optional]
**weight_kilograms** | **int** | The individual&#39;s weight in kilograms. | [optional]
**eye_color** | **string** | The individual&#39;s eye color.              Possible values:              - \&quot;black\&quot; - \&quot;blue\&quot; - \&quot;brown\&quot; - \&quot;dichromatic\&quot; - \&quot;grey\&quot; - \&quot;green\&quot; - \&quot;hazel\&quot; - \&quot;maroon\&quot; - \&quot;pink\&quot; - \&quot;unknown\&quot; | [optional]
**hair_color** | **string** | The individual&#39;s hair color.              Possible values: - \&quot;bald\&quot; - \&quot;black\&quot; - \&quot;blond\&quot; - \&quot;brown\&quot; - \&quot;grey\&quot; - \&quot;red\&quot; - \&quot;auburn\&quot; - \&quot;sandy\&quot; - \&quot;white\&quot; - \&quot;unknown\&quot; | [optional]
**birth_place** | **string** | Country and municipality or state/province where the individual was born. | [optional]
**resident_address** | **string** | Address where the individual resides.              The exact format of this field is variable and depends on the issuer. It may map exactly to a \&quot;Line1\&quot;, or it may include city, state, and/or zip code as well. | [optional]
**resident_city** | **string** | City where the individual resides. | [optional]
**resident_state** | **string** | State, province, or district where the individual resides. | [optional]
**resident_postal_code** | **string** | Postal code where the individual resides. | [optional]
**resident_country** | **string** | Country where the individual resides as an ISO 3166-1 alpha-2 country code. | [optional]
**portrait_capture_date** | **\DateTime** | Date and time when the portrait image was captured. | [optional]
**age_in_years** | **int** | Age of the individual in years. | [optional]
**age_birth_year** | **int** | Year of birth of the individual. | [optional]
**age_over** | [**\Trinsic\Api\Model\AgeOverOutput[]**](AgeOverOutput.md) | Processed age-over claims returned by the mDL. | [optional]
**biometric_template_face** | [**\Trinsic\Api\Model\Iso180132BiometricGroupTemplate**](Iso180132BiometricGroupTemplate.md) | Facial biometric template group from &#x60;biometric_template_face&#x60;, parsed per ISO 18013-2 Annex C. | [optional]
**biometric_template_voice** | [**\Trinsic\Api\Model\Iso180132BiometricGroupTemplate**](Iso180132BiometricGroupTemplate.md) | Vocal biometric template group from &#x60;biometric_template_voice&#x60;, parsed per ISO 18013-2 Annex C. | [optional]
**biometric_template_finger** | [**\Trinsic\Api\Model\Iso180132BiometricGroupTemplate**](Iso180132BiometricGroupTemplate.md) | Fingerprint biometric template group from &#x60;biometric_template_finger&#x60;, parsed per ISO 18013-2 Annex C. | [optional]
**biometric_template_iris** | [**\Trinsic\Api\Model\Iso180132BiometricGroupTemplate**](Iso180132BiometricGroupTemplate.md) | Iris biometric template group from &#x60;biometric_template_iris&#x60;, parsed per ISO 18013-2 Annex C. | [optional]
**biometric_template_retina** | [**\Trinsic\Api\Model\Iso180132BiometricGroupTemplate**](Iso180132BiometricGroupTemplate.md) | Retinal biometric template group from &#x60;biometric_template_retina&#x60;, parsed per ISO 18013-2 Annex C. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
