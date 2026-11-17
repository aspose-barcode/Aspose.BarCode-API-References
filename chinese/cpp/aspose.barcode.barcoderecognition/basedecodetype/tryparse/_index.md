---
title: "method"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ API 参考"
description: "方法。将 SingleDecodeType 的字符串表示转换为其实例。返回值指示转换在 C++ 中是成功还是失败。"
type: docs
weight: 400
url: /zh/cpp/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


将 [SingleDecodeType](../../singledecodetype/) 的字符串表示转换为其实例。返回值指示转换是否成功。

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| parsingType | System::String | 包含 [SingleDecodeType](../../singledecodetype/) 的字符串，格式如 "EAN8"、"EAN13" 或 "CodaBar"... 用于转换。 |
| result | System::SharedPtr\<SingleDecodeType\>\& | 当转换成功完成时返回实际的 [SingleDecodeType](../../singledecodetype/)；否则返回不确定类型： [DecodeType.None](../../decodetype/none/)。 |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## 另见

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


将 [MultiDecodeType](../../multidecodetype/) 的字符串表示转换为其实例。返回值指示转换是否成功。

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| parsingType | System::String | 包含 [MultiDecodeType](../../multidecodetype/) 表示的字符串，用于转换。 |
| result | System::SharedPtr\<MultiDecodeType\>\& | 当转换成功完成时返回实际的 [MultiDecodeType](../../multidecodetype/)；否则返回不确定类型：new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../../decodetype/none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## 另见

* Class [MultiDecodeType](../../multidecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<BaseDecodeType\>\&) method


将 [BaseDecodeType](../) 的字符串表示转换为其实例，并确定具体类型。返回值指示转换是否成功。

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<BaseDecodeType> &result)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| parsingType | System::String | 包含 [MultiDecodeType](../../multidecodetype/) 表示的字符串，用于转换。 |
| result | System::SharedPtr\<BaseDecodeType\>\& | 当转换成功完成时返回实际的 [MultiDecodeType](../../multidecodetype/)；否则返回不确定类型： [DecodeType.None](../../decodetype/none/)。 |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## 另见

* Class [BaseDecodeType](../)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
