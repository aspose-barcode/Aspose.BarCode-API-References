---
title: "methode"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Converteert de stringrepresentatie van een MultiDecodeType naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is in C++."
type: docs
weight: 1100
url: /nl/cpp/aspose.barcode.barcoderecognition/multidecodetype/tryparse/
---
## MultiDecodeType::TryParse method


Converteert de stringrepresentatie van een [MultiDecodeType](../) naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::MultiDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | System::String | Een string in het formaat "AllSupportedTypes" of "EAN8,EAN13,CodaBar" om te converteren. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Een daadwerkelijke [MultiDecodeType](../) wordt geretourneerd wanneer de conversie succesvol is voltooid; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## Opmerkingen



anders retourneert het een onbepaald type.

of [MultiDecodeType](../) ("None").

## Zie ook

* Class [MultiDecodeType](../)
* Class [MultiDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
