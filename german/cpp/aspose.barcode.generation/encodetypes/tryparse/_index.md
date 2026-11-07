---
title: "Methode"
linktitle: "TryParse"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " method. Konvertiert die Zeichenketten-Darstellung eines BaseEncodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung in C++ erfolgreich war oder fehlgeschlagen ist."
type: docs
weight: 400
url: /de/cpp/aspose.barcode.generation/encodetypes/tryparse/
---
## EncodeTypes::TryParse method


Konvertiert die Zeichenkettenrepräsentation eines [BaseEncodeType](../../baseencodetype/) in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

```cpp
static bool Aspose::BarCode::Generation::EncodeTypes::TryParse(System::String parsingType, System::SharedPtr<BaseEncodeType> &result)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingType | System::String | Eine Zeichenkette im Format "Index:-1; Name:None" zum Konvertieren. |
| Ergebnis | System::SharedPtr\<BaseEncodeType\>\& | Ein tatsächlicher SingleEncodeType wird zurückgegeben, wenn die Konvertierung erfolgreich abgeschlossen wurde; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## Hinweise



ansonsten wird null zurückgegeben.

## Siehe auch

* Class [BaseEncodeType](../../baseencodetype/)
* Class [EncodeTypes](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
