---
title: "Clase GS1Codetext"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.ComplexBarcode.GS1Codetext. Representa el codetext de GS1 para codificar y decodificar como una secuencia ordenada de elementos Application Identifier. Se preservan el orden de origen y los Application Identifier repetidos. La representación entre corchetes tiene la forma AIvalueAIvalue. Un paréntesis de apertura literal dentro de un valor debe escribirse como  . Esta es la única secuencia de escape admitida. Un paréntesis de cierre dentro de un valor no requiere escape."
type: docs
weight: 530
url: /es/net/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class

Representa el codetext GS1 para codificar y decodificar como una secuencia ordenada de elementos Identificador de Aplicación. Se preservan el orden de origen y los Identificadores de Aplicación repetidos. La representación entre corchetes tiene la forma (AI)valor(AI)valor. Un paréntesis de apertura literal '(' dentro de un valor debe escribirse como \\(; esta es la única secuencia de escape admitida. Un paréntesis de cierre ')' dentro de un valor no requiere escape.

```csharp
public sealed class GS1Codetext : IComplexCodetext
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GS1Codetext](gs1codetext/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/barcodetype/) { get; set; } | Obtiene o establece el tipo de código de barras utilizado para codificar este codetext de GS1. Los tipos compatibles son GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR y los tipos GS1 DataBar. El valor predeterminado es GS1Code128. |
| [Count](../../aspose.barcode.complexbarcode/gs1codetext/count/) { get; } | Obtiene el número de elementos de Application Identifier. |
| [Elements](../../aspose.barcode.complexbarcode/gs1codetext/elements/) { get; } | Obtiene una copia de todos los elementos en el orden de origen. |
| [Item](../../aspose.barcode.complexbarcode/gs1codetext/item/) { get; } | Obtiene un elemento por su posición en la secuencia ordenada. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Parse](../../aspose.barcode.complexbarcode/gs1codetext/parse/)(string) | Analiza una cadena de elemento GS1 entre corchetes en la forma (AI)value(AI)value. Un '(' literal dentro de un valor debe escribirse como \(; no se admite ninguna otra secuencia de escape, y ')' no requiere escape. |
| [Add](../../aspose.barcode.complexbarcode/gs1codetext/add/)(string, string) | Añade un elemento de Application Identifier validado. |
| [GetAll](../../aspose.barcode.complexbarcode/gs1codetext/getall/)(string) | Obtiene todos los valores de un Application Identifier en el orden de origen. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/gs1codetext/getbarcodetype/)() | Obtiene el tipo de código de barras utilizado para codificar este codetext de GS1. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/gs1codetext/getconstructedcodetext/)() | Construye el texto codificado GS1 entre corchetes en la forma (AI)valor(AI)valor. Los paréntesis de apertura literales en los valores se escapan como \\(. |
| [GetFirst](../../aspose.barcode.complexbarcode/gs1codetext/getfirst/)(string) | Obtiene el primer valor de un Application Identifier. |
| [InitFromString](../../aspose.barcode.complexbarcode/gs1codetext/initfromstring/)(string) | Inicializa esta instancia a partir del texto codificado GS1 entre corchetes en la forma (AI)valor(AI)valor. Los elementos existentes se reemplazan solo después de que el texto codificado proporcionado se haya analizado correctamente. |
| override [ToString](../../aspose.barcode.complexbarcode/gs1codetext/tostring/)() | Devuelve la representación GS1 entre corchetes en la forma (AI)valor(AI)valor. |
| static [TryParse](../../aspose.barcode.complexbarcode/gs1codetext/tryparse/)(string, out GS1Codetext, out GS1ValidationResult) | Intenta analizar una cadena de elemento GS1 entre corchetes en la forma (AI)valor(AI)valor y devuelve errores de validación estructurados. Un '(' literal dentro de un valor debe escribirse como \\(; no se admite ninguna otra secuencia de escape, y ')' no requiere escape. |
| static [Validate](../../aspose.barcode.complexbarcode/gs1codetext/validate/)(string) | Valida una cadena de elemento GS1 entre corchetes en la forma (AI)valor(AI)valor sin construir un objeto. Un '(' literal dentro de un valor debe escribirse como \\(; no se admite ninguna otra secuencia de escape, y ')' no requiere escape. |

### Ver también

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


