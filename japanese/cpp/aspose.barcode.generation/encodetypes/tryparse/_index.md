---
title: "メソッド"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " method. C++ で BaseEncodeType の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。"
type: docs
weight: 400
url: /ja/cpp/aspose.barcode.generation/encodetypes/tryparse/
---
## EncodeTypes::TryParse method


[BaseEncodeType](../../baseencodetype/) の文字列表現をインスタンスに変換します。戻り値は変換が成功したか失敗したかを示します。

```cpp
static bool Aspose::BarCode::Generation::EncodeTypes::TryParse(System::String parsingType, System::SharedPtr<BaseEncodeType> &result)
```


| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parsingType | System::String | 変換するための "Index:-1; Name:None" 形式の文字列。 |
| result | System::SharedPtr\<BaseEncodeType\>\& | 変換が正常に完了した場合に返される実際の SingleEncodeType; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## 備考



それ以外の場合は null を返します。

## 関連項目

* Class [BaseEncodeType](../../baseencodetype/)
* Class [EncodeTypes](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
