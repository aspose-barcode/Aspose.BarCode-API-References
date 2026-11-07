---
title: "Methode"
linktitle: "Parse"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Konvertiert die Zeichenkettenrepräsentation eines SingleDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung in C++ erfolgreich war oder fehlgeschlagen ist."
type: docs
weight: 400
url: /de/cpp/aspose.barcode.barcoderecognition/decodetype/parse/
---
## DecodeType::Parse method


Konvertiert die Zeichenkettenrepräsentation eines [SingleDecodeType](../../singledecodetype/) in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::Parse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
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
