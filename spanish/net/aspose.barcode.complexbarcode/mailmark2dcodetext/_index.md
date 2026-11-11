---
title: "Clase Mailmark2DCodetext"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.ComplexBarcode.Mailmark2DCodetext. Clase para codificar y decodificar el texto incrustado en el código Royal Mail 2D Mailmark."
type: docs
weight: 650
url: /es/net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class

Clase para codificar y decodificar el texto incrustado en el código Royal Mail 2D Mailmark.

```csharp
public sealed class Mailmark2DCodetext : IComplexCodetext
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Mailmark2DCodetext](mailmark2dcodetext/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmark2dcodetext/class/) { get; set; } | Identifica la clase del elemento. |
| [CustomerContent](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontent/) { get; set; } | Espacio opcional para uso del cliente. |
| [CustomerContentEncodeMode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontentencodemode/) { get; set; } | Modo de codificación del código de barras Datamatrix. Valor predeterminado: EncodeMode.C40. |
| [DataMatrixType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/datamatrixtype/) { get; set; } | El tipo de Mailmark 2D define el tamaño del código de barras Data Matrix. |
| [DestinationPostCodeAndDPS](../../aspose.barcode.complexbarcode/mailmark2dcodetext/destinationpostcodeanddps/) { get; set; } | Contiene el código postal de la dirección de entrega con DPS. Si es interior, el código postal/DP contiene el siguiente número de caracteres: Área (1 o 2 caracteres) Distrito (1 o 2 caracteres) Sector (1 carácter) Unidad (2 caracteres) DPS (2 caracteres). El código postal y el DPS deben cumplir con un formato PAF® válido. |
| [InformationTypeID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/informationtypeid/) { get; set; } | Identifica la carga útil del código de barras Royal Mail Mailmark para cada tipo de producto. |
| [ItemID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/itemid/) { get; set; } | Identifica el elemento único dentro del ID de la cadena de suministro. Cada código de barras Mailmark debe llevar un ID para que pueda ser identificado de forma única durante al menos 90 días. Valor máximo: 99999999. |
| [ReturnToSenderPostCode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/returntosenderpostcode/) { get; set; } | Contiene el código postal de devolución al remitente pero sin DPS. El CP (sin DPS) debe cumplir con un formato PAF®. |
| [RTSFlag](../../aspose.barcode.complexbarcode/mailmark2dcodetext/rtsflag/) { get; set; } | Indicador que muestra qué nivel de servicio de devolución al remitente se está solicitando. |
| [SupplyChainID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/supplychainid/) { get; set; } | Identifica el grupo único de clientes involucrados en el envío. Valor máximo: 9999999. |
| [UPUCountryID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/upucountryid/) { get; set; } | Identifica el ID de país UPU. Longitud máxima: 4 caracteres. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/versionid/) { get; set; } | Identifica la versión del código de barras según cada ID de tipo de información. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getbarcodetype/)() | Obtiene el tipo de código de barras. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getconstructedcodetext/)() | Construye codetext a partir de datos Mailmark. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmark2dcodetext/initfromstring/)(string) | Inicializa los datos Mailmark a partir del codetext construido. |

### Ver también

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


