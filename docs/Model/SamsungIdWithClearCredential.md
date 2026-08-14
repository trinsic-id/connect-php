# SamsungIdWithClearCredential

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**given_name** | **string** | First name(s), other name(s), or secondary identifier of the individual. | [optional]
**family_name** | **string** | Last name, surname, or primary identifier of the individual. | [optional]
**date_of_birth** | **\DateTime** | The date of birth of the individual. | [optional]
**issue_date** | **\DateTime** | The date the Samsung ID was issued.              This is not the issue date of the passport used to create the Samsung ID; see &#x60;originalDocumentIssueDate&#x60;. | [optional]
**expiry_date** | **\DateTime** | The date the Samsung ID expires.              This is not necessarily the expiry date of the passport used to create the Samsung ID; see &#x60;originalDocumentExpiryDate&#x60;. | [optional]
**original_document_issue_date** | **\DateTime** | Issue date of the underlying passport used to create the Samsung ID. | [optional]
**original_document_expiry_date** | **\DateTime** | Expiry date of the underlying passport used to create the Samsung ID. | [optional]
**document_number** | **string** | The document number of the underlying passport used to create the Samsung ID. | [optional]
**issuing_authority** | **string** | Identifier of Samsung as the issuing authority of the Samsung ID credential.              This always begins with \&quot;XS-\&quot;. | [optional]
**sex** | **int** | The individual&#39;s sex as an ISO/IEC 5218 code.              Possible values: - 0: Unknown - 1: Male - 2: Female - 9: Not Applicable | [optional]
**dhs_compliance** | **bool** | Whether the credential is compliant with REAL ID.              This is always &#x60;true&#x60; for Samsung ID with CLEAR credentials. | [optional]
**age_in_years** | **int** | Age of the individual in years. | [optional]
**age_birth_year** | **int** | Year of birth of the individual. | [optional]
**age_over** | [**\Trinsic\Api\Model\AgeOverOutput[]**](AgeOverOutput.md) | Processed age-over claims returned by the credential. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
