---
title: "Methode"
linktitle: "TryParse"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Konvertiert die Zeichenkettenrepräsentation eines SingleDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung in C++ erfolgreich war oder fehlgeschlagen ist."
type: docs
weight: 500
url: /de/cpp/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## DecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


Konvertiert die Zeichenkettenrepräsentation eines [SingleDecodeType](../../singledecodetype/) in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingType | System::String | Eine Zeichenkette, die einen [SingleDecodeType](../../singledecodetype/) im Format "EAN8" oder "EAN13" oder "CodaBar"... zum Konvertieren enthält. |
| result | System::SharedPtr\<SingleDecodeType\>\& | Ein tatsächlicher [SingleDecodeType](../../singledecodetype/) wird zurückgegeben, wenn die Konvertierung erfolgreich abgeschlossen wurde; andernfalls wird der unbestimmte Typ zurückgegeben: [DecodeType.None](../none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Siehe auch

* Class [SingleDecodeType](../../singledecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## DecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


Konvertiert die Zeichenkettenrepräsentation eines [MultiDecodeType](../../multidecodetype/) in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingType | System::String | Ein String im Format entweder "AllSupportedTypes" oder "EAN8,EAN13,CodaBar", der konvertiert werden soll. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Ein tatsächlicher [MultiDecodeType](../../multidecodetype/) wird zurückgegeben, wenn die Konvertierung erfolgreich abgeschlossen wurde; andernfalls wird der unbestimmte Typ zurückgegeben: new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Siehe auch

* Class [MultiDecodeType](../../multidecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
