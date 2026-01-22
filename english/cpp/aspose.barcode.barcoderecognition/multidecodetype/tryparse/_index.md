---
title:  method
linktitle: TryParse
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Converts the string representation of a MultiDecodeType to its instance. A return value indicates whether the conversion succeeded or failed in C++.'
type: docs
weight: 1200
url: /cpp/aspose.barcode.barcoderecognition/multidecodetype/tryparse/
---
## MultiDecodeType::TryParse method


Converts the string representation of a [MultiDecodeType](../) to its instance. A return value indicates whether the conversion succeeded or failed.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::MultiDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | System::String | A string in the format as either "AllSupportedTypes" or "EAN8,EAN13,CodaBar" to convert. |
| result | System::SharedPtr\<MultiDecodeType\>\& | An actual [MultiDecodeType](../) is returned, when conversion has completed successfully; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## Remarks



otherwise it returns indefinite type. 

or [MultiDecodeType](../) ("None").

## See Also

* Class [MultiDecodeType](../)
* Class [MultiDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
