# MoldovaVehicleRegistrationCertificateCredential

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**plate_number** | **string** | The registered vehicle&#39;s plate number. | [optional]
**idnv** | **string** | The registered vehicle&#39;s IDNV (Numărul de Identificare a Vehiculului), the identifier assigned to the vehicle in the Moldovan State Register of Transport.              This is a Moldovan registry identifier and is distinct from the manufacturer&#39;s VIN. | [optional]
**vin** | **string** | The vehicle&#39;s manufacturer-assigned Vehicle Identification Number (VIN), per ISO 3779. | [optional]
**make** | **string** | The make (manufacturer brand) of the vehicle. | [optional]
**model** | **string** | The commercial model name of the vehicle. | [optional]
**color** | **string** | The color of the vehicle, as recorded by the issuer.              TODO: Possible values? | [optional]
**category** | **string** | The vehicle&#39;s EU vehicle category code. | [optional]
**year** | **int** | The vehicle&#39;s year of manufacture. | [optional]
**body_number** | **string** | The body number of the vehicle, if recorded separately from the VIN. | [optional]
**body_type** | **string** | The body type of the vehicle, as recorded by the issuer.              This is a free text field with no guaranteed format. | [optional]
**chassis_number** | **string** | The chassis number of the vehicle, if recorded separately from the VIN. | [optional]
**engine_volume** | **string** | The engine displacement volume of the vehicle, as recorded by the issuer (typically in cubic centimeters).              This is a free text field with no guaranteed format. | [optional]
**engine_type** | **string** | The engine/fuel type of the vehicle, as recorded by the issuer.              This is a free text field with no guaranteed format. | [optional]
**engine_number** | **string** | The engine number of the vehicle. | [optional]
**authorized_weight** | **int** | The maximum technically permissible laden mass of the vehicle, in kilograms. | [optional]
**weight** | **int** | The mass of the vehicle in service (unladen / kerb weight), in kilograms. | [optional]
**places** | **int** | The number of seating positions in the vehicle, including the driver. | [optional]
**idnp** | **string** | The IDNP (Numărul de Identificare Personal) of the vehicle&#39;s registered holder.              This is a 13-digit number which uniquely identifies all natural persons in the Republic of Moldova. It has the format &#x60;2YYYOOOSSSSSX&#x60;, where: - &#x60;2&#x60; is the literal number &#x60;2&#x60; to indicate that the identifier belongs to a natural person - &#x60;YYY&#x60; is the last 3 digits of the year in which the identifier was issued - &#x60;OOO&#x60; is the code of the registrar office which issued the identifier - &#x60;SSSSS&#x60; is the sequential birth number for that year - &#x60;X&#x60; is a check digit              Note that the year encoded in the identifier is not necessarily the same as the year of birth of the individual. | [optional]
**family_name** | **string** | The family name (surname) of the vehicle&#39;s registered holder. | [optional]
**given_name** | **string** | The given name(s) of the vehicle&#39;s registered holder. | [optional]
**address** | **string** | The registered address of the vehicle&#39;s holder, as a single formatted string. | [optional]
**vehicle_right** | **string** | The legal relationship the registration holder has to the vehicle (e.g. owner vs. authorized user), as recorded by the issuer.              TODO: Values | [optional]
**special_remarks** | **string[]** | Free-text remarks or annotations recorded on the registration certificate. | [optional]
**issue_date** | **\DateTime** | The date the registration certificate was issued. | [optional]
**expiry_date** | **\DateTime** | The date the registration certificate expires. | [optional]
**issuing_authority** | **string** | The name of the authority that issued the registration certificate. | [optional]
**document_number** | **string** | The number of the registration certificate document itself. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
