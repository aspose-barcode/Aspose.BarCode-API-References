---
title: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext clase"
linktitle: "USADriveIdCodetext"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext class. Clase para codificar y decodificar el texto incrustado en el código PDF417 de la Licencia de Conducción de EE. UU. en C++."
type: docs
weight: 2900
url: /es/cpp/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class


Clase para codificar y decodificar el texto incrustado en el código PDF417 de la [Licencia](../../aspose.barcode/license/) de Conducción de EE. UU.

```cpp
class USADriveIdCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_AAMVAVersionNumber](./get_aamvaversionnumber/)() const | Número de Versión AAMVA 00-99 |
| [get_IssuerIdentificationNumber](./get_issueridentificationnumber/)() const | Este número identifica de forma única la jurisdicción emisora y puede obtenerse contactando a la Autoridad Emisora ISO (AAMVA). Se debe codificar el IIN completo de 6 dígitos. |
| [get_JurisdictionSpecificSubfile](./get_jurisdictionspecificsubfile/)() const | Campos Específicos de la Jurisdicción |
| [get_JurisdictionVersionNumber](./get_jurisdictionversionnumber/)() const | Número de Versión de la Jurisdicción 00-99 |
| [get_MandatoryElements](./get_mandatoryelements/)() const | Elementos obligatorios (campos) de la tarjeta |
| [get_NumberOfEntries](./get_numberofentries/)() const | Número 00-99 de subarchivos |
| [get_OptionalElements](./get_optionalelements/)() const | Elementos opcionales (campos) de la tarjeta |
| [get_SubfileDesignator](./get_subfiledesignator/)() const | Contiene información sobre los siguientes subarchivos, tipos, desplazamientos y longitudes. Importante: establezca solo el tipo, el desplazamiento y la longitud se establecerán automáticamente. |
| [GetBarcodeType](./getbarcodetype/)() override | Devuelve el tipo de código de barras de la Licencia de EE. UU. (Pdf417) |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construir codetext a partir de los datos de la Licencia de EE. UU. |
| [InitFromString](./initfromstring/)(System::String) override | Inicializar el objeto de Licencia de EE. UU. a partir del codetext |
| [SaveToXml](./savetoxml/)(System::SharedPtr\<System::IO::Stream\>) | Guarda en XML |
| [set_AAMVAVersionNumber](./set_aamvaversionnumber/)(System::String) | Número de Versión AAMVA 00-99 |
| [set_IssuerIdentificationNumber](./set_issueridentificationnumber/)(System::String) | Este número identifica de forma única la jurisdicción emisora y puede obtenerse contactando a la Autoridad Emisora ISO (AAMVA). Se debe codificar el IIN completo de 6 dígitos. |
| [set_JurisdictionSpecificSubfile](./set_jurisdictionspecificsubfile/)(System::SharedPtr\<USADriveIdJurisdSubfile\>) | Campos Específicos de la Jurisdicción |
| [set_JurisdictionVersionNumber](./set_jurisdictionversionnumber/)(System::String) | Número de Versión de la Jurisdicción 00-99 |
| [set_MandatoryElements](./set_mandatoryelements/)(System::SharedPtr\<USADriveIdCodetext::MandatoryFields\>) | Elementos obligatorios (campos) de la tarjeta |
| [set_NumberOfEntries](./set_numberofentries/)(int32_t) | Número 00-99 de subarchivos |
| [set_OptionalElements](./set_optionalelements/)(System::SharedPtr\<USADriveIdCodetext::OptionalFields\>) | Elementos opcionales (campos) de la tarjeta |
| [set_SubfileDesignator](./set_subfiledesignator/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<USADriveIdCodetext::SubfileProperties\>>>) | Contiene información sobre los siguientes subarchivos, tipos, desplazamientos y longitudes. Importante: establezca solo el tipo, el desplazamiento y la longitud se establecerán automáticamente. |
| [USADriveIdCodetext](./usadriveidcodetext/)() | Constructor predeterminado |
## Ver también

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
