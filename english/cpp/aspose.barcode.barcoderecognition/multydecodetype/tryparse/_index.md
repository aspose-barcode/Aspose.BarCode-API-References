---
title: Aspose::BarCode::BarCodeRecognition::MultyDecodeType::TryParse method
linktitle: TryParse
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::MultyDecodeType::TryParse method. Converts the string representation of a MultyDecodeType to its instance. A return value indicates whether the conversion succeeded or failed in C++.'
type: docs
weight: 1200
url: /cpp/aspose.barcode.barcoderecognition/multydecodetype/tryparse/
---
## MultyDecodeType::TryParse method


Converts the string representation of a [MultyDecodeType](../) to its instance. A return value indicates whether the conversion succeeded or failed.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::MultyDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultyDecodeType> &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | System::String | A string in the format as either "AllSupportedTypes" or "EAN8,EAN13,CodaBar" to convert. |
| result | System::SharedPtr\<MultyDecodeType\>\& | An actual [MultyDecodeType](../) is returned, when conversion has completed successfully; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## Remarks



otherwise it returns indefinite type. 

or [MultyDecodeType](../) ("None").

## See Also

* Class [MultyDecodeType](../)
* Class [MultyDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
