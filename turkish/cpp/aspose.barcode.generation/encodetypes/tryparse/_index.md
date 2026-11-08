---
title: "metot"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " method. Bir BaseEncodeType'ın dize temsilini örneğine dönüştürür. Dönen değer, dönüşümün C++'da başarılı olup olmadığını gösterir."
type: docs
weight: 400
url: /tr/cpp/aspose.barcode.generation/encodetypes/tryparse/
---
## EncodeTypes::TryParse method


[BaseEncodeType](../../baseencodetype/) öğesinin dize temsilini örneğine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir.

```cpp
static bool Aspose::BarCode::Generation::EncodeTypes::TryParse(System::String parsingType, System::SharedPtr<BaseEncodeType> &result)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | System::String | Dönüştürmek için "Index:-1; Name:None" biçiminde bir dize. |
| result | System::SharedPtr\<BaseEncodeType\>\& | Dönüşüm başarıyla tamamlandığında gerçek bir SingleEncodeType döndürür; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## Açıklamalar



Aksi takdirde null döndürür.

## Ayrıca Bakınız

* Class [BaseEncodeType](../../baseencodetype/)
* Class [EncodeTypes](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
