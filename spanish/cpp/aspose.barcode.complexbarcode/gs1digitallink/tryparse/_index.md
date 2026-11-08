---
title: "método"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Intenta analizar un URI de GS1 Digital Link sin comprimir y devuelve errores de validación estructurados en C++."
type: docs
weight: 2000
url: /es/cpp/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink::TryParse method


Intenta analizar un URI de Enlace Digital GS1 sin comprimir y devuelve errores de validación estructurados.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1DigitalLink::TryParse(System::String value, System::SharedPtr<GS1DigitalLink> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | System::String | URI de GS1 Digital Link a analizar. |
| result | System::SharedPtr\<GS1DigitalLink\>\& | Cuando este método devuelve true, contiene el GS1 Digital Link analizado; de lo contrario, null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | Contiene el resultado de validación, o null cuando *value* es null. |

### ReturnValue

True cuando el análisis tiene éxito; de lo contrario, false.

## Ver también

* Class [GS1DigitalLink](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
