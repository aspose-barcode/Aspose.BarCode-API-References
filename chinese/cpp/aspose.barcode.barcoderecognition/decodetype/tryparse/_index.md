---
title: "method"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API 参考"
description: "方法。将 SingleDecodeType 的字符串表示转换为其实例。返回值指示转换在 C++ 中是成功还是失败。"
type: docs
weight: 500
url: /zh/cpp/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## DecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


将 [SingleDecodeType](../../singledecodetype/) 的字符串表示转换为其实例。返回值指示转换是否成功。

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
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
## DecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


将 [MultiDecodeType](../../multidecodetype/) 的字符串表示转换为其实例。返回值指示转换是否成功。

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| parsingType | System::String | 用于转换的字符串，格式为 "AllSupportedTypes" 或 "EAN8,EAN13,CodaBar"。 |
| result | System::SharedPtr\<MultiDecodeType\>\& | 实际的 [MultiDecodeType](../../multidecodetype/) 在转换成功完成时返回；否则返回不确定类型: new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## 另见

* Class [MultiDecodeType](../../multidecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
