---
title: "Clase USADriveIdCodetext"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.ComplexBarcode.USADriveIdCodetext. Clase para codificar y decodificar el texto incrustado en el código PDF417 de la Licencia de Conducir de EE. UU."
type: docs
weight: 810
url: /es/net/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class

Clase para codificar y decodificar el texto incrustado en el código PDF417 de la licencia de conducir de EE. UU.

```csharp
public sealed class USADriveIdCodetext : IComplexCodetext
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [USADriveIdCodetext](usadriveidcodetext/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AAMVAVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/aamvaversionnumber/) { get; set; } | Número de versión AAMVA 00-99 |
| [IssuerIdentificationNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/issueridentificationnumber/) { get; set; } | Este número identifica de forma única la jurisdicción emisora y puede obtenerse contactando a la Autoridad emisora ISO (AAMVA). Se debe codificar el IIN completo de 6 dígitos. |
| [JurisdictionSpecificSubfile](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionspecificsubfile/) { get; set; } | Campos específicos de la jurisdicción |
| [JurisdictionVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionversionnumber/) { get; set; } | Número de versión de la jurisdicción 00-99 |
| [MandatoryElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/mandatoryelements/) { get; set; } | Elementos obligatorios (campos) de la tarjeta |
| [NumberOfEntries](../../aspose.barcode.complexbarcode/usadriveidcodetext/numberofentries/) { get; set; } | Número 00-99 de subarchivos |
| [OptionalElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/optionalelements/) { get; set; } | Elementos opcionales (campos) de la tarjeta |
| [SubfileDesignator](../../aspose.barcode.complexbarcode/usadriveidcodetext/subfiledesignator/) { get; set; } | Contiene información sobre los siguientes subarchivos, tipos, desplazamientos y longitudes. Importante: establezca solo el tipo, el desplazamiento y la longitud se establecerán automáticamente. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/usadriveidcodetext/getbarcodetype/)() | Devuelve el tipo de código de barras de la licencia de EE. UU. (Pdf417) |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/usadriveidcodetext/getconstructedcodetext/)() | Construye el texto de código a partir de los datos de la licencia de EE. UU. |
| [InitFromString](../../aspose.barcode.complexbarcode/usadriveidcodetext/initfromstring/)(string) | Inicializa el objeto de licencia de EE. UU. a partir del texto de código |
| [SaveToXml](../../aspose.barcode.complexbarcode/usadriveidcodetext/savetoxml/)(Stream) | Guarda en XML |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| class [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields) | Elementos obligatorios (campos) de la tarjeta |
| class [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields) | Elementos opcionales (campos) de la tarjeta |
| class [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties) | Las propiedades de subarchivo USA DL, desplazamiento y longitud, se establecen automáticamente. |

### Ver también

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


