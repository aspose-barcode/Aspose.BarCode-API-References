---
title: "Methode"
linktitle: "TryParse"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " method. Konvertiert die Zeichenkettenrepräsentation eines MultiDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung in C++ erfolgreich war oder fehlgeschlagen ist."
type: docs
weight: 1100
url: /de/cpp/aspose.barcode.barcoderecognition/multidecodetype/tryparse/
---
## MultiDecodeType::TryParse method


Konvertiert die String‑Darstellung eines [MultiDecodeType](../) in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::MultiDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingType | System::String | Ein String im Format entweder "AllSupportedTypes" oder "EAN8,EAN13,CodaBar", der konvertiert werden soll. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Ein tatsächlicher [MultiDecodeType](../) wird zurückgegeben, wenn die Konvertierung erfolgreich abgeschlossen wurde; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## Hinweise



Andernfalls gibt er einen unbestimmten Typ zurück.

oder [MultiDecodeType](../) ("None").

## Siehe auch

* Class [MultiDecodeType](../)
* Class [MultiDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
