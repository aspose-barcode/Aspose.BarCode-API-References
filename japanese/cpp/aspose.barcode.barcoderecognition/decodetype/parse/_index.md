---
title: "メソッド"
linktitle: "Parse"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: "メソッド。SingleDecodeType の文字列表現をそのインスタンスに変換します。戻り値は、C++ で変換が成功したか失敗したかを示します。"
type: docs
weight: 400
url: /ja/cpp/aspose.barcode.barcoderecognition/decodetype/parse/
---
## DecodeType::Parse method


[SingleDecodeType](../../singledecodetype/) の文字列表現をそのインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::Parse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
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
