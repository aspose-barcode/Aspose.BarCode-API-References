---
title: "método"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " method. Intenta analizar una cadena de elemento GS1 entre corchetes en la forma (AI)valor(AI)valor y devuelve errores de validación estructurados. Un literal ''('' dentro de un valor debe escribirse como (; no se admite ninguna otra secuencia de escape, y '')'' no requiere escape en C++."
type: docs
weight: 1600
url: /es/cpp/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext::TryParse method


Intenta analizar una cadena de elemento GS1 entre corchetes en la forma (AI)valor(AI)valor y devuelve errores de validación estructurados. Un '(' literal dentro de un valor debe escribirse como (; no se admite ninguna otra secuencia de escape, y ')' no requiere escape.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1Codetext::TryParse(System::String value, System::SharedPtr<GS1Codetext> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | System::String | Cadena de elemento GS1 entre corchetes para analizar. |
| result | System::SharedPtr\<GS1Codetext\>\& | Cuando este método devuelve true, contiene el texto de código GS1 analizado; de lo contrario, null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Contiene el resultado de validación, o null cuando *value* es null. |

### ReturnValue

True cuando el análisis tiene éxito; de lo contrario, false.

## Ver también

* Class [GS1Codetext](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
