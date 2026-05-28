# SouthAfricaNidMatch2Input

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id_number** | **string** | The South African National Identity Number (13 digits).              Issued for life by the Department of Home Affairs (DHA) and stored in the HANIS (Home Affairs National Identification System) database. The same number is mandatory for banking, employment, taxation, and voting, and is printed on both the legacy green ID book and the Smart ID Card (rolled out from 2013 onward).              Format: - YYMMDD G(4) C A Z - YYMMDD is the date of birth - G(4) is the gender code (below 5000 female, 5000 or above male) - C is the citizenship indicator (0 citizen, 1 permanent resident) - A is reserved (it had a politically sensitive meaning in the past, but is currently   semantically meaningless) - Z is a Luhn check digit | [optional]
**given_name** | **string** | The user&#39;s first name as it appears in their National ID | [optional]
**family_name** | **string** | The user&#39;s last name as it appears in their National ID | [optional]
**middle_name** | **string** | The user&#39;s middle name as it appears in their National ID (optional) | [optional]
**date_of_birth** | **\DateTime** | The user&#39;s date of birth, in &#x60;YYYY-MM-DD&#x60; format | [optional]
**sex** | [**\Trinsic\Api\Model\SouthAfricaNidMatch2InputSex**](SouthAfricaNidMatch2InputSex.md) | The user&#39;s sex as it appears in their National ID | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
