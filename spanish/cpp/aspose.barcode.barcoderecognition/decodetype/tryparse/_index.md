---
title: "método"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Convierte la representación en cadena de un SingleDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló en C++."
type: docs
weight: 500
url: /es/cpp/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## DecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


Convierte la representación en cadena de un [SingleDecodeType](../../singledecodetype/) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parsingType | System::String | Una cadena que contiene un [SingleDecodeType](../../singledecodetype/) en el formato "EAN8" o "EAN13" o "CodaBar"... para convertir. |
| result | System::SharedPtr\<SingleDecodeType\>\& | Un [SingleDecodeType](../../singledecodetype/) real devuelve, cuando la conversión se ha completado con éxito; de lo contrario devuelve el tipo indefinido: [DecodeType.None](../none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Ver también

* Class [SingleDecodeType](../../singledecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## DecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


Convierte la representación en cadena de un [MultiDecodeType](../../multidecodetype/) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parsingType | System::String | Una cadena con el formato "AllSupportedTypes" o "EAN8,EAN13,CodaBar" para convertir. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Se devuelve un [MultiDecodeType](../../multidecodetype/) real, cuando la conversión se ha completado con éxito; de lo contrario devuelve el tipo indefinido: new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Ver también

* Class [MultiDecodeType](../../multidecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
