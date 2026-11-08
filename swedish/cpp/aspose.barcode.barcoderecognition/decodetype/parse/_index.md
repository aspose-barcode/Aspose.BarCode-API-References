---
title: "metod"
linktitle: "Parse"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Konverterar strängrepresentationen av en SingleDecodeType till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.barcode.barcoderecognition/decodetype/parse/
---
## DecodeType::Parse method


Konverterar strängrepresentationen av en [SingleDecodeType](../../singledecodetype/) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::Parse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parsingType | System::String | En sträng som innehåller en [SingleDecodeType](../../singledecodetype/) i formatet "EAN8" eller "EAN13" eller "CodaBar"... för konvertering. |
| result | System::SharedPtr\<SingleDecodeType\>\& | En faktisk [SingleDecodeType](../../singledecodetype/) returneras när konverteringen har slutförts framgångsrikt; annars returneras en obestämd typ: [DecodeType.None](../none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Se även

* Class [SingleDecodeType](../../singledecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
