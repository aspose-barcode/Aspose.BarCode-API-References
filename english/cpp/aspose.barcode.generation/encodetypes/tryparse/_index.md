---
title:  method
linktitle: TryParse
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Converts the string representation of a BaseEncodeType to its instance. A return value indicates whether the conversion succeeded or failed in C++.'
type: docs
weight: 400
url: /cpp/aspose.barcode.generation/encodetypes/tryparse/
---
## EncodeTypes::TryParse method


Converts the string representation of a [BaseEncodeType](../../baseencodetype/) to its instance. A return value indicates whether the conversion succeeded or failed.

```cpp
static bool Aspose::BarCode::Generation::EncodeTypes::TryParse(System::String parsingType, System::SharedPtr<BaseEncodeType> &result)
```


| Parameter | Type | Description |
| --- | --- | --- |
| parsingType | System::String | A string in the format as "Index:-1; Name:None" to convert. |
| result | System::SharedPtr\<BaseEncodeType\>\& | An actual SingleEncodeType returns, when conversion has completed successfully; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## Remarks



otherwise it returns null.

## See Also

* Class [BaseEncodeType](../../baseencodetype/)
* Class [EncodeTypes](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
