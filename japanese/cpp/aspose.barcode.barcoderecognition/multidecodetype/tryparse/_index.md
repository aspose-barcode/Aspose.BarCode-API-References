---
title: "メソッド"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " method. MultiDecodeType の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します（C++）。"
type: docs
weight: 1100
url: /ja/cpp/aspose.barcode.barcoderecognition/multidecodetype/tryparse/
---
## MultiDecodeType::TryParse method


[MultiDecodeType](../) の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

```cpp
static bool Aspose::BarCode::BarCodeRecognition::MultiDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parsingType | System::String | 変換するための文字列で、形式は "AllSupportedTypes" または "EAN8,EAN13,CodaBar" のいずれかです。 |
| result | System::SharedPtr\<MultiDecodeType\>\& | 変換が正常に完了した場合、実際の [MultiDecodeType](../) が返されます； |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## 備考



それ以外の場合は不定型が返されます。

または [MultiDecodeType](../) ("None").

## 関連項目

* Class [MultiDecodeType](../)
* Class [MultiDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
