# IndonesiaNikMatch

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**full_name** | [**\Trinsic\Api\Model\IndonesiaNikMatchField**](IndonesiaNikMatchField.md) | Full name match result from Indonesia NIK verification. | [optional]
**date_of_birth** | [**\Trinsic\Api\Model\IndonesiaNikMatchField**](IndonesiaNikMatchField.md) | Date of birth match result from Indonesia NIK verification. | [optional]
**national_id_number** | [**\Trinsic\Api\Model\IndonesiaNikMatchField**](IndonesiaNikMatchField.md) | NIK number match result from Indonesia NIK verification.              NIK stands for Nomor Induk Kependudukan. It is Indonesia&#39;s unique population identity number, issued by Indonesia&#39;s population administration and civil registration authority (Dukcapil) under the Ministry of Home Affairs. A NIK has 16 digits: - Digits 1-2 are the province code. - Digits 3-4 are the regency or city code within that province. - Digits 5-6 are the district code within that regency or city. - Digits 7-12 encode date of birth as DDMMYY. For female NIK holders, the day is increased by 40. - Digits 13-16 are an issuance serial number. | [optional]
**province_code** | **string** | Two-digit province code extracted from digits 1-2 of the NIK number. | [optional]
**regency_or_city_code** | **string** | Four-digit regency or city code extracted from digits 1-4 of the NIK number, including the province code prefix. | [optional]
**district_code** | **string** | Six-digit district code extracted from digits 1-6 of the NIK number, including province and regency/city code prefixes. | [optional]
**date_of_birth_national_id_number** | **\DateTime** | Date of birth extracted from digits 7-12 of the NIK number.              The NIK encodes date of birth as DDMMYY. For female NIK holders, the encoded day is increased by 40 before being stored in the NIK number. | [optional]
**sex_national_id_number** | **string** | Sex extracted from the birth-day portion of the NIK number.              The encoded day value is increased by 40 for female NIK holders. | [optional]
**serial_number** | **string** | Four-digit issuance serial number extracted from digits 13-16 of the NIK number. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
