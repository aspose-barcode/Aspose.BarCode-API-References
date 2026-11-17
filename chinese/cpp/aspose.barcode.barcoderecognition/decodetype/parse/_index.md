---
title: "method"
linktitle: "Parse"
second_title: "Aspose.BarCode for C++ API 参考"
description: "方法。将 SingleDecodeType 的字符串表示转换为其实例。返回值指示转换在 C++ 中是成功还是失败。"
type: docs
weight: 400
url: /zh/cpp/aspose.barcode.barcoderecognition/decodetype/parse/
---
## DecodeType::Parse method


将 [SingleDecodeType](../../singledecodetype/) 的字符串表示转换为其实例。返回值指示转换是否成功。

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::Parse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| parsingType | System::String | 包含 [SingleDecodeType](../../singledecodetype/) 的字符串，格式如 "EAN8"、"EAN13" 或 "CodaBar"... 用于转换。 |
| result | System::SharedPtr\<SingleDecodeType\>\& | 实际的 [SingleDecodeType](../../singledecodetype/) 在转换成功完成时返回；否则返回不确定类型: [DecodeType.None](../none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## 另见

* Class [SingleDecodeType](../../singledecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
