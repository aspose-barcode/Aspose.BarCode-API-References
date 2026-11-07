---
title: "メソッド"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "メソッド。SingleDecodeType の文字列表現をそのインスタンスに変換します。戻り値は、C++ で変換が成功したか失敗したかを示します。"
type: docs
weight: 400
url: /ja/cpp/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


[SingleDecodeType](../../singledecodetype/) の文字列表現をそのインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parsingType | System::String | 変換するための、"EAN8"、"EAN13"、または "CodaBar" などの形式で表された [SingleDecodeType](../../singledecodetype/) を含む文字列。 |
| result | System::SharedPtr\<SingleDecodeType\>\& | 変換が正常に完了した場合は実際の [SingleDecodeType](../../singledecodetype/) が返されます。そうでない場合は不定の型、[DecodeType.None](../../decodetype/none/) が返されます。 |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## 関連項目

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


[MultiDecodeType](../../multidecodetype/) の文字列表現をそのインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parsingType | System::String | 変換するための [MultiDecodeType](../../multidecodetype/) 表現を含む文字列。 |
| result | System::SharedPtr\<MultiDecodeType\>\& | 変換が正常に完了した場合は実際の [MultiDecodeType](../../multidecodetype/) が返されます。そうでない場合は不定の型、new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../../decodetype/none/)) が返されます。 |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## 関連項目

* Class [MultiDecodeType](../../multidecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<BaseDecodeType\>\&) method


[BaseDecodeType](../) の文字列表現を具体的な型を決定した上でそのインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<BaseDecodeType> &result)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parsingType | System::String | 変換するための [MultiDecodeType](../../multidecodetype/) 表現を含む文字列。 |
| result | System::SharedPtr\<BaseDecodeType\>\& | 変換が正常に完了した場合は実際の [MultiDecodeType](../../multidecodetype/) が返されます。そうでない場合は不定の型、[DecodeType.None](../../decodetype/none/) が返されます。 |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## 関連項目

* Class [BaseDecodeType](../)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
