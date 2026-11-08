---
title: "metod"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Konverterar strängrepresentationen av en SingleDecodeType till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


Konverterar strängrepresentationen av en [SingleDecodeType](../../singledecodetype/) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parsingType | System::String | En sträng som innehåller en [SingleDecodeType](../../singledecodetype/) i formatet "EAN8" eller "EAN13" eller "CodaBar"... för konvertering. |
| result | System::SharedPtr\<SingleDecodeType\>\& | En faktisk [SingleDecodeType](../../singledecodetype/) returneras när konverteringen har slutförts framgångsrikt; annars returneras en obestämd typ: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Se även

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


Konverterar strängrepresentationen av en [MultiDecodeType](../../multidecodetype/) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parsingType | System::String | En sträng som innehåller en [MultiDecodeType](../../multidecodetype/) representation för konvertering. |
| result | System::SharedPtr\<MultiDecodeType\>\& | En faktisk [MultiDecodeType](../../multidecodetype/) returneras när konverteringen har slutförts framgångsrikt; annars returneras en obestämd typ: new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../../decodetype/none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Se även

* Class [MultiDecodeType](../../multidecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<BaseDecodeType\>\&) method


Konverterar strängrepresentationen av en [BaseDecodeType](../) till dess instans, efter att ha bestämt den konkreta typen. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<BaseDecodeType> &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parsingType | System::String | En sträng som innehåller en [MultiDecodeType](../../multidecodetype/) representation för konvertering. |
| result | System::SharedPtr\<BaseDecodeType\>\& | En faktisk [MultiDecodeType](../../multidecodetype/) returneras när konverteringen har slutförts framgångsrikt; annars returneras en obestämd typ: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Se även

* Class [BaseDecodeType](../)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
