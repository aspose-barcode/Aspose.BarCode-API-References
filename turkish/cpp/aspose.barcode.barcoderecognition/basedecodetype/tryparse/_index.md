---
title: "metot"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " yöntemi. SingleDecodeType'ın dize temsilini örneğine dönüştürür. Bir dönüş değeri, dönüşümün C++'ta başarılı olup olmadığını gösterir."
type: docs
weight: 400
url: /tr/cpp/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


Bir [SingleDecodeType](../../singledecodetype/) dize temsilini örneğine dönüştürür. Bir dönüş değeri, dönüşümün başarılı olup olmadığını gösterir.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | System::String | Dönüştürmek için "EAN8" veya "EAN13" veya "CodaBar"... biçiminde bir [SingleDecodeType](../../singledecodetype/) içeren bir dize. |
| result | System::SharedPtr\<SingleDecodeType\>\& | Dönüşüm başarılı bir şekilde tamamlandığında gerçek bir [SingleDecodeType](../../singledecodetype/) döndürülür; aksi takdirde belirsiz tür döndürülür: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Ayrıca Bakınız

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


Bir [MultiDecodeType](../../multidecodetype/) dize temsilini örneğine dönüştürür. Bir dönüş değeri, dönüşümün başarılı olup olmadığını gösterir.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | System::String | Dönüştürmek için bir [MultiDecodeType](../../multidecodetype/) temsilini içeren bir dize. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Dönüşüm başarılı bir şekilde tamamlandığında gerçek bir [MultiDecodeType](../../multidecodetype/) döndürülür; aksi takdirde belirsiz tür döndürülür: new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../../decodetype/none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Ayrıca Bakınız

* Class [MultiDecodeType](../../multidecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<BaseDecodeType\>\&) method


Somut tür belirlenerek bir [BaseDecodeType](../) dize temsilini örneğine dönüştürür. Bir dönüş değeri, dönüşümün başarılı olup olmadığını gösterir.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<BaseDecodeType> &result)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parsingType | System::String | Dönüştürmek için bir [MultiDecodeType](../../multidecodetype/) temsilini içeren bir dize. |
| result | System::SharedPtr\<BaseDecodeType\>\& | Dönüşüm başarılı bir şekilde tamamlandığında gerçek bir [MultiDecodeType](../../multidecodetype/) döndürülür; aksi takdirde belirsiz tür döndürülür: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Ayrıca Bakınız

* Class [BaseDecodeType](../)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
