---
title: "Clase GS1DigitalLink"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.ComplexBarcode.GS1DigitalLink. Representa el texto de código GS1 Digital Link para codificar y decodificar como una secuencia ordenada de elementos de Identificador de Aplicación. Se conserva el orden de origen y los Identificadores de Aplicación repetidos. El texto de código construido es una URI GS1 Digital Link sin comprimir. Los parámetros de consulta y fragmentos de URI que no son GS1 se ignoran al analizar."
type: docs
weight: 540
url: /es/net/aspose.barcode.complexbarcode/gs1digitallink/
---
## GS1DigitalLink class

Representa el codetext GS1 Digital Link para codificar y decodificar como una secuencia ordenada de elementos Identificador de Aplicación. Se preservan el orden de origen y los Identificadores de Aplicación repetidos. El codetext construido es un URI GS1 Digital Link sin comprimir. Los parámetros de consulta y fragmentos de URI que no son GS1 se ignoran al analizar.

```csharp
public sealed class GS1DigitalLink : IComplexCodetext
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GS1DigitalLink](gs1digitallink/#constructor)(string) | Inicializa un GS1 Digital Link vacío con la raíz de URI especificada. La clave primaria se selecciona automáticamente cuando hay exactamente un candidato a clave primaria. |
| [GS1DigitalLink](gs1digitallink/#constructor_1)(string, string) | Inicializa un GS1 Digital Link vacío con la raíz de URI especificada y la clave primaria. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/barcodetype/) { get; set; } | Obtiene o establece el tipo de código de barras utilizado para codificar este GS1 Digital Link. Los tipos compatibles son QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF y Code128. El valor predeterminado es QR. |
| [Count](../../aspose.barcode.complexbarcode/gs1digitallink/count/) { get; } | Obtiene el número de elementos de Application Identifier. |
| [Elements](../../aspose.barcode.complexbarcode/gs1digitallink/elements/) { get; } | Obtiene una copia de todos los elementos en el orden de origen. |
| [Item](../../aspose.barcode.complexbarcode/gs1digitallink/item/) { get; } | Obtiene un elemento por su posición en la secuencia ordenada. |
| [PrimaryApplicationIdentifier](../../aspose.barcode.complexbarcode/gs1digitallink/primaryapplicationidentifier/) { get; } | Obtiene el Application Identifier utilizado como la clave primaria del Digital Link. Null significa que la clave primaria se selecciona automáticamente cuando se construye el URI. |
| [UriStem](../../aspose.barcode.complexbarcode/gs1digitallink/uristem/) { get; } | Obtiene el prefijo absoluto del URI antes del segmento de ruta de la clave primaria de GS1. La base no contiene una cadena de consulta ni fragmento. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create)(string, GS1Codetext) | Crea un GS1 Digital Link copiando todos los elementos del codetext de GS1 y seleccionando la única clave primaria disponible. |
| static [Create](../../aspose.barcode.complexbarcode/gs1digitallink/create/#create_1)(string, GS1Codetext, string) | Crea un GS1 Digital Link copiando todos los elementos del codetext de GS1 y utilizando la clave primaria especificada. |
| static [Parse](../../aspose.barcode.complexbarcode/gs1digitallink/parse/)(string) | Analiza un URI de GS1 Digital Link sin comprimir. |
| [Add](../../aspose.barcode.complexbarcode/gs1digitallink/add/)(string, string) | Añade un elemento de Application Identifier validado. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1digitallink/getall/)(string) | Obtiene todos los valores de un Application Identifier en el orden de origen. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1digitallink/getbarcodetype/)() | Obtiene el tipo de código de barras utilizado para codificar este GS1 Digital Link. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1digitallink/getconstructedcodetext/)() | Construye el URI de GS1 Digital Link sin comprimir. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1digitallink/getfirst/)(string) | Obtiene el primer valor de un Application Identifier. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1digitallink/initfromstring/)(string) | Inicializa esta instancia a partir de un URI de GS1 Digital Link sin comprimir. El estado existente se reemplaza solo después de que el URI proporcionado se haya analizado correctamente. El tipo de código de barras seleccionado se conserva. |
| [ToGS1Codetext](../../aspose.barcode.complexbarcode/gs1digitallink/togs1codetext/)() | Crea un codetext de GS1 independiente que contiene los elementos actuales de GS1. La información solo de URI no se incluye. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1digitallink/tostring/)() | Devuelve el URI de GS1 Digital Link sin comprimir. |
| [ToUriString](../../aspose.barcode.complexbarcode/gs1digitallink/touristring/)() | Formatea el estado actual del objeto como un URI de GS1 Digital Link sin comprimir. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1digitallink/tryparse/)(string, out GS1DigitalLink, out GS1ValidationResult) | Intenta analizar un URI de GS1 Digital Link sin comprimir y devuelve errores de validación estructurados. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1digitallink/validate/)(string) | Valida un URI de GS1 Digital Link sin comprimir sin construir un objeto. |

### Ver también

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


