---
title: "método"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " method. Convierte la representación en cadena de un MultiDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló en C++."
type: docs
weight: 1100
url: /es/cpp/aspose.barcode.barcoderecognition/multidecodetype/tryparse/
---
## MultiDecodeType::TryParse method


Convierte la representación en cadena de un [MultiDecodeType](../) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::MultiDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parsingType | System::String | Una cadena con el formato "AllSupportedTypes" o "EAN8,EAN13,CodaBar" para convertir. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Se devuelve un [MultiDecodeType](../) real cuando la conversión se ha completado con éxito; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## Observaciones



de lo contrario devuelve un tipo indefinido.

o [MultiDecodeType](../) ("None").

## Ver también

* Class [MultiDecodeType](../)
* Class [MultiDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
