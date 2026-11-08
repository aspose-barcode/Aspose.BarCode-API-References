---
title: "Aspose::BarCode::ComplexBarcode::GS1Codetext clase"
linktitle: "GS1Codetext"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::ComplexBarcode::GS1Codetext clase. Representa el codetexto GS1 para codificar y decodificar como una secuencia ordenada de elementos Identificador de Aplicación. Se conserva el orden de origen y los Identificadores de Aplicación repetidos. La representación entre corchetes tiene la forma (AI)valor(AI)valor. Un paréntesis de apertura literal ''('' dentro de un valor debe escribirse como (; esta es la única secuencia de escape admitida. Un paréntesis de cierre '')'' dentro de un valor no requiere escape en C++."
type: docs
weight: 500
url: /es/cpp/aspose.barcode.complexbarcode/gs1codetext/
---
## GS1Codetext class


Representa el texto de código GS1 para codificar y decodificar como una secuencia ordenada de elementos Identificador de Aplicación. Se preserva el orden de origen y los Identificadores de Aplicación repetidos. La representación entre paréntesis tiene la forma (AI)valor(AI)valor. Un paréntesis de apertura literal '(' dentro de un valor debe escribirse como (; esta es la única secuencia de escape admitida. Un paréntesis de cierre ')' dentro de un valor no requiere escape.

```cpp
class GS1Codetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Add](./add/)(System::String, System::String) | Agrega un elemento Application Identifier validado. |
| [get_BarcodeType](./get_barcodetype/)() const | Obtiene el tipo de código de barras utilizado para codificar este codetexto GS1. Los tipos compatibles son GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR y tipos GS1 DataBar. El valor predeterminado es GS1Code128. |
| [get_Count](./get_count/)() | Obtiene el número de elementos Application Identifier. |
| [get_Elements](./get_elements/)() | Obtiene una copia de todos los elementos en el orden de origen. |
| [GetAll](./getall/)(System::String) | Obtiene todos los valores de un Identificador de Aplicación en orden de origen. |
| [GetBarcodeType](./getbarcodetype/)() override | Obtiene el tipo de código de barras utilizado para codificar este codetexto GS1. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construye el codetexto GS1 entre corchetes en la forma (AI)valor(AI)valor. Los paréntesis de apertura literales en los valores se escapan como (. |
| [GetFirst](./getfirst/)(System::String) | Obtiene el primer valor de un Identificador de Aplicación. |
| [GS1Codetext](./gs1codetext/)() | Inicializa un codetexto GS1 vacío. |
| [idx_get](./idx_get/)(int32_t) | Obtiene un elemento por su posición en la secuencia ordenada. |
| [InitFromString](./initfromstring/)(System::String) override | Inicializa esta instancia a partir de un codetexto GS1 entre corchetes en la forma (AI)valor(AI)valor. Los elementos existentes se reemplazan solo después de que el codetexto proporcionado se haya analizado correctamente. |
| static [Parse](./parse/)(System::String) | Analiza una cadena de elemento GS1 entre corchetes en la forma (AI)valor(AI)valor. Un '(' literal dentro de un valor debe escribirse como (; no se admite ninguna otra secuencia de escape, y ')' no requiere escape. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Establece el tipo de código de barras utilizado para codificar este codetexto GS1. Los tipos compatibles son GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix, GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR y tipos GS1 DataBar. El valor predeterminado es GS1Code128. |
| [ToString](./tostring/)() const override | Devuelve la representación entre corchetes de GS1 en la forma (AI)valor(AI)valor. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<GS1Codetext\>\&, System::SharedPtr\<Common::GS1ValidationResult\>\&) | Intenta analizar una cadena de elemento GS1 entre corchetes en la forma (AI)valor(AI)valor y devuelve errores de validación estructurados. Un '(' literal dentro de un valor debe escribirse como (; no se admite ninguna otra secuencia de escape, y ')' no requiere escape. |
| static [Validate](./validate/)(System::String) | Valida una cadena de elemento GS1 entre corchetes en la forma (AI)valor(AI)valor sin construir un objeto. Un '(' literal dentro de un valor debe escribirse como (; no se admite ninguna otra secuencia de escape, y ')' no requiere escape. |
## Ver también

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
