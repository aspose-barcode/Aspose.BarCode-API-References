---
title: "طريقة"
linktitle: "Parse"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " method. يحول تمثيل السلسلة لنوع SingleDecodeType إلى مثيله. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فشل في C++."
type: docs
weight: 400
url: /ar/cpp/aspose.barcode.barcoderecognition/decodetype/parse/
---
## DecodeType::Parse method


يحول تمثيل السلسلة لنوع [SingleDecodeType](../../singledecodetype/) إلى مثيله. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فشل.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::Parse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| parsingType | System::String | سلسلة تحتوي على [SingleDecodeType](../../singledecodetype/) بالتنسيق مثل "EAN8" أو "EAN13" أو "CodaBar"... للتحويل. |
| result | System::SharedPtr\<SingleDecodeType\>\& | تُعيد قيمة فعلية من نوع [SingleDecodeType](../../singledecodetype/) عندما يكتمل التحويل بنجاح؛ وإلا فإنها تُعيد النوع غير المحدد: [DecodeType.None](../none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## انظر أيضًا

* Class [SingleDecodeType](../../singledecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
