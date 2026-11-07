---
title: "メソッド"
linktitle: "Parse"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " method. C++ で BaseEncodeType の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。"
type: docs
weight: 300
url: /ja/cpp/aspose.barcode.generation/encodetypes/parse/
---
## EncodeTypes::Parse method


[BaseEncodeType](../../baseencodetype/) の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

```cpp
static bool Aspose::BarCode::Generation::EncodeTypes::Parse(System::String parsingType, System::SharedPtr<BaseEncodeType> &result)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parsingType | System::String | 変換するための [BaseEncodeType](../../baseencodetype/) 表現を含む文字列です。 |
| result | System::SharedPtr\<BaseEncodeType\>\& | 変換が正常に完了したときに実際の [BaseEncodeType](../../baseencodetype/) が返されます。 |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## 備考



それ以外の場合は null を返します。

## 関連項目

* Class [BaseEncodeType](../../baseencodetype/)
* Class [EncodeTypes](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
