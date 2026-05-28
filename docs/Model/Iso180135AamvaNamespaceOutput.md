# Iso180135AamvaNamespaceOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**domestic_driving_privileges** | [**\Trinsic\Api\Model\Iso180135AamvaDomesticDrivingPrivilege[]**](Iso180135AamvaDomesticDrivingPrivilege.md) | Domestic categories of vehicles, restrictions, and conditions, parsed per AAMVA Section 7.2.4. | [optional]
**name_suffix** | **string** | Name suffix of the individual that has been issued the credential. | [optional]
**organ_donor** | **bool** | Whether the individual is an organ donor. | [optional]
**veteran** | **bool** | Whether the individual is a veteran. | [optional]
**family_name_truncation** | **string** | Indicates whether the family name has been truncated.              Possible values: - &#39;T&#39;: Truncated - &#39;N&#39;: Not truncated - &#39;U&#39;: Unknown whether truncated | [optional]
**given_name_truncation** | **string** | Indicates whether the given name has been truncated.              Possible values: - &#39;T&#39;: Truncated - &#39;N&#39;: Not truncated - &#39;U&#39;: Unknown whether truncated | [optional]
**aka_family_name_v2** | **string** | Other family name by which the individual is known. | [optional]
**aka_given_name_v2** | **string** | Other given name by which the individual is known. | [optional]
**aka_suffix** | **string** | Other suffix by which the individual is known. | [optional]
**weight_range** | [**\Trinsic\Api\Model\Iso180135AamvaWeightRange**](Iso180135AamvaWeightRange.md) | Approximate weight range of the individual, in kilograms. | [optional]
**race_ethnicity** | **string** | AAMVA D20 race or ethnicity code of the individual. | [optional]
**sex** | **int** | The sex of the individual as an AAMVA-defined sex code.              This is distinct from an ISO/IEC 5218 sex code in two ways: there is no \&quot;Unknown\&quot; value, and \&quot;Not Applicable\&quot; is replaced with \&quot;Not Specified\&quot;.              Possible values: - 1: Male - 2: Female - 9: Not Specified | [optional]
**first_name** | **string** | First name of the individual. | [optional]
**middle_names** | **string** | Middle name or names of the individual. | [optional]
**first_name_truncation** | **string** | Whether the first name has been truncated. | [optional]
**middle_names_truncation** | **string** | Whether the middle name has been truncated. | [optional]
**edl_credential** | **int** | Deprecated AAMVA EDL (Enhanced Driver&#39;s License) credential indicator.              If present, indicates the type of the EDL credential.              Possible values: 1: Driver&#39;s License 2: Identification Card | [optional]
**edl_credential_v2** | **bool** | Whether the credential is an Enhanced Driver&#39;s License (EDL). | [optional]
**dhs_compliance** | **bool** | Whether the credential is REAL ID compliant. &#x60;true&#x60; for fully compliant (\&quot;F\&quot;), &#x60;false&#x60; for non-compliant (\&quot;N\&quot;), &#x60;null&#x60; when not present. | [optional]
**resident_county** | **string** | Deprecated county code for the county where the individual lives. | [optional]
**resident_county_v2** | **string** | County code for the county where the individual lives. | [optional]
**hazmat_endorsement_expiration_date** | **\DateTime** | Date on which the hazardous material endorsement expires. | [optional]
**cdl_indicator** | **bool** | Whether the credential is a Commercial Driver&#39;s License (CDL) per FMCSA. | [optional]
**cdl_non_domiciled** | **bool** | Deprecated. Whether the CDL holder is non-domiciled in the issuing jurisdiction. | [optional]
**cdl_non_domiciled_v2** | **bool** | Whether the CDL holder is non-domiciled in the issuing jurisdiction. | [optional]
**dhs_compliance_text** | **string** | Text agreed on between the issuing authority and DHS for non-compliant credentials. | [optional]
**dhs_temporary_lawful_status** | **bool** | Whether the individual has DHS temporary lawful status. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
