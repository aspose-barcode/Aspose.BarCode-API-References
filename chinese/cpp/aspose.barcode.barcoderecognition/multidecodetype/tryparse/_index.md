---
title: "method"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。将 MultiDecodeType 的字符串表示转换为其实例。返回值指示转换是成功还是失败（C++）。"
type: docs
weight: 1100
url: /zh/cpp/aspose.barcode.barcoderecognition/multidecodetype/tryparse/
---
## MultiDecodeType::TryParse method


将 [MultiDecodeType](../) 的字符串表示转换为其实例。返回值指示转换是成功还是失败。

```cpp
static bool Aspose::BarCode::BarCodeRecognition::MultiDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| parsingType | System::String | 用于转换的字符串，格式为 "AllSupportedTypes" 或 "EAN8,EAN13,CodaBar"。 |
| result | System::SharedPtr\<MultiDecodeType\>\& | 当转换成功完成时，返回实际的 [MultiDecodeType](../)； |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## 备注



否则返回不确定类型。

或 [MultiDecodeType](../) ("None").

## 另见

* Class [MultiDecodeType](../)
* Class [MultiDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
