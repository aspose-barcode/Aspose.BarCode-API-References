---
title: "método"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Convierte la representación en cadena de un SingleDecodeType a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló en C++."
type: docs
weight: 400
url: /es/cpp/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


Convierte la representación en cadena de un [SingleDecodeType](../../singledecodetype/) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parsingType | System::String | Una cadena que contiene un [SingleDecodeType](../../singledecodetype/) en el formato "EAN8" o "EAN13" o "CodaBar"... para convertir. |
| result | System::SharedPtr\<SingleDecodeType\>\& | Se devuelve un [SingleDecodeType](../../singledecodetype/) real, cuando la conversión se ha completado con éxito; de lo contrario devuelve el tipo indefinido: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Ver también

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


Convierte la representación en cadena de un [MultiDecodeType](../../multidecodetype/) a su instancia. Un valor de retorno indica si la conversión tuvo éxito o falló.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parsingType | System::String | Una cadena que contiene una representación de [MultiDecodeType](../../multidecodetype/) para convertir. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Se devuelve un [MultiDecodeType](../../multidecodetype/) real, cuando la conversión se ha completado con éxito; de lo contrario devuelve el tipo indefinido: new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../../decodetype/none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Ver también

* Class [MultiDecodeType](../../multidecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<BaseDecodeType\>\&) method


Convierte la representación en cadena de un [BaseDecodeType](../) a su instancia, habiendo determinado el tipo concreto. Un valor de retorno indica si la conversión tuvo éxito o falló.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<BaseDecodeType> &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| parsingType | System::String | Una cadena que contiene una representación de [MultiDecodeType](../../multidecodetype/) para convertir. |
| result | System::SharedPtr\<BaseDecodeType\>\& | Se devuelve un [MultiDecodeType](../../multidecodetype/) real, cuando la conversión se ha completado con éxito; de lo contrario devuelve el tipo indefinido: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Ver también

* Class [BaseDecodeType](../)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
