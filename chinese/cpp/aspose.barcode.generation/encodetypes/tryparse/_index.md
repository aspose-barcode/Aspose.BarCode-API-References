---
title: "method"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。将 BaseEncodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败（C++）。"
type: docs
weight: 400
url: /zh/cpp/aspose.barcode.generation/encodetypes/tryparse/
---
## EncodeTypes::TryParse method


将 [BaseEncodeType](../../baseencodetype/) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。

```cpp
static bool Aspose::BarCode::Generation::EncodeTypes::TryParse(System::String parsingType, System::SharedPtr<BaseEncodeType> &result)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| parsingType | System::String | 格式为 "Index:-1; Name:None" 的字符串，用于转换。 |
| result | System::SharedPtr\<BaseEncodeType\>\& | 当转换成功完成时，返回实际的 SingleEncodeType； |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## 备注



否则返回 null。

## 另见

* Class [BaseEncodeType](../../baseencodetype/)
* Class [EncodeTypes](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
