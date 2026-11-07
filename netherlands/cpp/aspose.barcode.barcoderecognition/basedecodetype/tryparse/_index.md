---
title: "methode"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Converteert de tekenreeksrepresentatie van een SingleDecodeType naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is in C++."
type: docs
weight: 400
url: /nl/cpp/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


Converteert de tekenreeksrepresentatie van een [SingleDecodeType](../../singledecodetype/) naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | System::String | Een tekenreeks die een [SingleDecodeType](../../singledecodetype/) bevat in het formaat "EAN8" of "EAN13" of "CodaBar"... om te converteren. |
| result | System::SharedPtr\<SingleDecodeType\>\& | Een daadwerkelijke [SingleDecodeType](../../singledecodetype/) wordt geretourneerd wanneer de conversie succesvol is voltooid; anders wordt een onbepaald type geretourneerd: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Zie ook

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


Converteert de tekenreeksrepresentatie van een [MultiDecodeType](../../multidecodetype/) naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | System::String | Een tekenreeks die een [MultiDecodeType](../../multidecodetype/) representatie bevat om te converteren. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Een daadwerkelijke [MultiDecodeType](../../multidecodetype/) wordt geretourneerd wanneer de conversie succesvol is voltooid; anders wordt een onbepaald type geretourneerd: new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../../decodetype/none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Zie ook

* Class [MultiDecodeType](../../multidecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<BaseDecodeType\>\&) method


Converteert de tekenreeksrepresentatie van een [BaseDecodeType](../) naar zijn instantie, nadat het concrete type is bepaald. Een retourwaarde geeft aan of de conversie geslaagd of mislukt.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<BaseDecodeType> &result)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | System::String | Een tekenreeks die een [MultiDecodeType](../../multidecodetype/) representatie bevat om te converteren. |
| result | System::SharedPtr\<BaseDecodeType\>\& | Een daadwerkelijke [MultiDecodeType](../../multidecodetype/) wordt geretourneerd wanneer de conversie succesvol is voltooid; anders wordt een onbepaald type geretourneerd: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Zie ook

* Class [BaseDecodeType](../)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
