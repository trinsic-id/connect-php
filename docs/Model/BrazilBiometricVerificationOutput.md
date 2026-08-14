# BrazilBiometricVerificationOutput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**selfie_verification_probability** | **string** | The probability of the selfie verification being successful.              Possible values: - VeryLow - Low - High - VeryHigh | [optional]
**selfie_liveness_outcome** | **string** | The outcome of the selfie verification.              Possible values: - Real - Fake - BadQuality | [optional]
**database_selfie_available** | **bool** | Whether the government database had biometrics available for the individual.              Also false in some cases biometrics are available but not sufficient for selfie verification. | [optional]
**selfie_similarity_percentage** | **float** | Similarity match score of selfie verification.              Ranges from 0.0 to 1.0. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
