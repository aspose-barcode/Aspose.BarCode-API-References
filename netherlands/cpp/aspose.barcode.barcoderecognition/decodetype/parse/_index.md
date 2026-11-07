---
title: "methode"
linktitle: "Parse"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Converteert de tekenreeksrepresentatie van een SingleDecodeType naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is in C++."
type: docs
weight: 400
url: /nl/cpp/aspose.barcode.barcoderecognition/decodetype/parse/
---
## DecodeType::Parse method


Converteert de tekenreeksrepresentatie van een [SingleDecodeType](../../singledecodetype/) naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::Parse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | System::String | Een tekenreeks die een [SingleDecodeType](../../singledecodetype/) bevat in het formaat "EAN8" of "EAN13" of "CodaBar"... om te converteren. |
| result | System::SharedPtr\<SingleDecodeType\>\& | Een daadwerkelijke [SingleDecodeType](../../singledecodetype/) retourneert, wanneer de conversie succesvol is voltooid; anders retourneert het een onbepaald type: [DecodeType.None](../none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Zie ook

* Class [SingleDecodeType](../../singledecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
