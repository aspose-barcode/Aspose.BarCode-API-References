---
title: "metod"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Konverterar strängrepresentationen av en MultiDecodeType till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades i C++."
type: docs
weight: 1100
url: /sv/cpp/aspose.barcode.barcoderecognition/multidecodetype/tryparse/
---
## MultiDecodeType::TryParse method


Konverterar strängrepresentationen av en [MultiDecodeType](../) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::MultiDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parsingType | System::String | En sträng i formatet antingen "AllSupportedTypes" eller "EAN8,EAN13,CodaBar" för att konvertera. |
| result | System::SharedPtr\<MultiDecodeType\>\& | En faktisk [MultiDecodeType](../) returneras när konverteringen har slutförts framgångsrikt; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## Anmärkningar



annars returneras en obestämd typ.

eller [MultiDecodeType](../) ("None").

## Se även

* Class [MultiDecodeType](../)
* Class [MultiDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
