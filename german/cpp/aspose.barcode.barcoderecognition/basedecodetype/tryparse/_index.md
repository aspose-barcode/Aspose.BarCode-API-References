---
title: "Methode"
linktitle: "TryParse"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Konvertiert die Zeichenkettenrepräsentation eines SingleDecodeType in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung in C++ erfolgreich war oder fehlgeschlagen ist."
type: docs
weight: 400
url: /de/cpp/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


Konvertiert die Zeichenkettenrepräsentation eines [SingleDecodeType](../../singledecodetype/) in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingType | System::String | Eine Zeichenkette, die einen [SingleDecodeType](../../singledecodetype/) im Format "EAN8" oder "EAN13" oder "CodaBar"... zum Konvertieren enthält. |
| result | System::SharedPtr\<SingleDecodeType\>\& | Ein tatsächlicher [SingleDecodeType](../../singledecodetype/) wird zurückgegeben, wenn die Konvertierung erfolgreich abgeschlossen wurde; andernfalls wird der unbestimmte Typ zurückgegeben: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Siehe auch

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


Konvertiert die Zeichenkettenrepräsentation eines [MultiDecodeType](../../multidecodetype/) in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingType | System::String | Eine Zeichenkette, die eine [MultiDecodeType](../../multidecodetype/)-Darstellung zum Konvertieren enthält. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Ein tatsächlicher [MultiDecodeType](../../multidecodetype/) wird zurückgegeben, wenn die Konvertierung erfolgreich abgeschlossen wurde; andernfalls wird der unbestimmte Typ zurückgegeben: new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../../decodetype/none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Siehe auch

* Class [MultiDecodeType](../../multidecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<BaseDecodeType\>\&) method


Konvertiert die Zeichenkettenrepräsentation eines [BaseDecodeType](../) in seine Instanz, nachdem der konkrete Typ ermittelt wurde. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<BaseDecodeType> &result)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| parsingType | System::String | Eine Zeichenkette, die eine [MultiDecodeType](../../multidecodetype/)-Darstellung zum Konvertieren enthält. |
| result | System::SharedPtr\<BaseDecodeType\>\& | Ein tatsächlicher [MultiDecodeType](../../multidecodetype/) wird zurückgegeben, wenn die Konvertierung erfolgreich abgeschlossen wurde; andernfalls wird der unbestimmte Typ zurückgegeben: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Siehe auch

* Class [BaseDecodeType](../)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
