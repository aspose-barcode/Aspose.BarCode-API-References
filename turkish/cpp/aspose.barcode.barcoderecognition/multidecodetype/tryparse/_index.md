---
title: "metot"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " method. Bir MultiDecodeType'ın dize temsilini örneğine dönüştürür. Dönüş değeri, dönüşümün C++ içinde başarılı olup olmadığını gösterir."
type: docs
weight: 1100
url: /tr/cpp/aspose.barcode.barcoderecognition/multidecodetype/tryparse/
---
## MultiDecodeType::TryParse method


[MultiDecodeType](../) dize temsilini örneğine dönüştürür. Dönüş değeri, dönüşümün başarılı olup olmadığını gösterir.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::MultiDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | System::String | Dönüştürmek için "AllSupportedTypes" ya da "EAN8,EAN13,CodaBar" biçiminde bir dize. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Dönüşüm başarılı bir şekilde tamamlandığında gerçek bir [MultiDecodeType](../) döndürülür; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## Açıklamalar



Aksi takdirde belirsiz bir tip döndürür.

veya [MultiDecodeType](../) ("None").

## Ayrıca Bakınız

* Class [MultiDecodeType](../)
* Class [MultiDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
