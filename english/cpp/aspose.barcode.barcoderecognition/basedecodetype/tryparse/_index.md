---
title:  method
linktitle: TryParse
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Converts the string representation of a SingleDecodeType to its instance. A return value indicates whether the conversion succeeded or failed in C++.'
type: docs
weight: 300
url: /cpp/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


Converts the string representation of a [SingleDecodeType](../../singledecodetype/) to its instance. A return value indicates whether the conversion succeeded or failed.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | System::String | A string containing a [SingleDecodeType](../../singledecodetype/) in the format as "EAN8" or "EAN13" or "CodaBar"... to convert. |
| result | System::SharedPtr\<SingleDecodeType\>\& | An actual [SingleDecodeType](../../singledecodetype/) is returned, when conversion has completed successfully; otherwise it returns indefinite type: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## See Also

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


Converts the string representation of a [MultiDecodeType](../../multidecodetype/) to its instance. A return value indicates whether the conversion succeeded or failed.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | System::String | A string containing a [MultiDecodeType](../../multidecodetype/) representation to convert. |
| result | System::SharedPtr\<MultiDecodeType\>\& | An actual [MultiDecodeType](../../multidecodetype/) is returned, when conversion has completed successfully; otherwise it returns indefinite type: new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../../decodetype/none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## See Also

* Class [MultiDecodeType](../../multidecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<BaseDecodeType\>\&) method


Converts the string representation of a [BaseDecodeType](../) to its instance, having determined the concrete type. A return value indicates whether the conversion succeeded or failed.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<BaseDecodeType> &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | System::String | A string containing a [MultiDecodeType](../../multidecodetype/) representation to convert. |
| result | System::SharedPtr\<BaseDecodeType\>\& | An actual [MultiDecodeType](../../multidecodetype/) is returned, when conversion has completed successfully; otherwise it returns indefinite type: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## See Also

* Class [BaseDecodeType](../)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
