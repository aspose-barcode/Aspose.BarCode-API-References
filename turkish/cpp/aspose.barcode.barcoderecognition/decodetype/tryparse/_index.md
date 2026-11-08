---
title: "metot"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " yöntemi. SingleDecodeType'ın dize temsilini örneğine dönüştürür. Bir dönüş değeri, dönüşümün C++'ta başarılı olup olmadığını gösterir."
type: docs
weight: 500
url: /tr/cpp/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## DecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


Bir [SingleDecodeType](../../singledecodetype/) dize temsilini örneğine dönüştürür. Bir dönüş değeri, dönüşümün başarılı olup olmadığını gösterir.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | System::String | Dönüştürmek için "EAN8" veya "EAN13" veya "CodaBar"... biçiminde bir [SingleDecodeType](../../singledecodetype/) içeren bir dize. |
| result | System::SharedPtr\<SingleDecodeType\>\& | Gerçek bir [SingleDecodeType](../../singledecodetype/) döner, dönüşüm başarıyla tamamlandığında; aksi takdirde belirsiz bir tür döndürür: [DecodeType.None](../none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Ayrıca Bakınız

* Class [SingleDecodeType](../../singledecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## DecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


Bir [MultiDecodeType](../../multidecodetype/) dize temsilini örneğine dönüştürür. Bir dönüş değeri, dönüşümün başarılı olup olmadığını gösterir.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | System::String | Dönüştürmek için "AllSupportedTypes" ya da "EAN8,EAN13,CodaBar" biçiminde bir dize. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Gerçek bir [MultiDecodeType](../../multidecodetype/) döndürülür, dönüşüm başarıyla tamamlandığında; aksi takdirde belirsiz bir tür döndürülür: yeni [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Ayrıca Bakınız

* Class [MultiDecodeType](../../multidecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
