---
title: "metod"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API-referens"
description: " method. Konverterar strängrepresentationen av en BaseEncodeType till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.barcode.generation/encodetypes/tryparse/
---
## EncodeTypes::TryParse method


Konverterar strängrepresentationen av en [BaseEncodeType](../../baseencodetype/) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

```cpp
static bool Aspose::BarCode::Generation::EncodeTypes::TryParse(System::String parsingType, System::SharedPtr<BaseEncodeType> &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parsingType | System::String | En sträng i formatet "Index:-1; Name:None" att konvertera. |
| resultat | System::SharedPtr\<BaseEncodeType\>\& | En faktisk SingleEncodeType returneras, när konverteringen har slutförts framgångsrikt; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## Anmärkningar



annars returneras null.

## Se även

* Class [BaseEncodeType](../../baseencodetype/)
* Class [EncodeTypes](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
