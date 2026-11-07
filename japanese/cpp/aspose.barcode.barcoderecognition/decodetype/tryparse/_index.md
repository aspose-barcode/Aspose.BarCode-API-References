---
title: "メソッド"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "メソッド。SingleDecodeType の文字列表現をそのインスタンスに変換します。戻り値は、C++ で変換が成功したか失敗したかを示します。"
type: docs
weight: 500
url: /ja/cpp/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## DecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


[SingleDecodeType](../../singledecodetype/) の文字列表現をそのインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parsingType | System::String | 変換するための、"EAN8"、"EAN13"、または "CodaBar" などの形式で表された [SingleDecodeType](../../singledecodetype/) を含む文字列。 |
| result | System::SharedPtr\<SingleDecodeType\>\& | 実際の [SingleDecodeType](../../singledecodetype/) は、変換が正常に完了した場合に返されます。それ以外の場合は不定の型 [DecodeType.None](../none/) を返します。 |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## 関連項目

* Class [SingleDecodeType](../../singledecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## DecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


[MultiDecodeType](../../multidecodetype/) の文字列表現をそのインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parsingType | System::String | 変換するための文字列で、形式は "AllSupportedTypes" または "EAN8,EAN13,CodaBar" のいずれかです。 |
| result | System::SharedPtr\<MultiDecodeType\>\& | 実際の [MultiDecodeType](../../multidecodetype/) は、変換が正常に完了した場合に返されます。それ以外の場合は不定の型として new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../none/)) を返します。 |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## 関連項目

* Class [MultiDecodeType](../../multidecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
