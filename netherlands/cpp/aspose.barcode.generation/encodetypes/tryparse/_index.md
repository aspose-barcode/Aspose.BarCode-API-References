---
title: "methode"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Converteert de stringrepresentatie van een BaseEncodeType naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is in C++."
type: docs
weight: 400
url: /nl/cpp/aspose.barcode.generation/encodetypes/tryparse/
---
## EncodeTypes::TryParse method


Converteert de tekenreeksrepresentatie van een [BaseEncodeType](../../baseencodetype/) naar zijn instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is.

```cpp
static bool Aspose::BarCode::Generation::EncodeTypes::TryParse(System::String parsingType, System::SharedPtr<BaseEncodeType> &result)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parsingType | System::String | Een string in het formaat "Index:-1; Name:None" om te converteren. |
| result | System::SharedPtr\<BaseEncodeType\>\& | Een daadwerkelijke SingleEncodeType wordt geretourneerd wanneer de conversie succesvol is voltooid; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## Opmerkingen



anders retourneert het null.

## Zie ook

* Class [BaseEncodeType](../../baseencodetype/)
* Class [EncodeTypes](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
