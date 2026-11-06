---
title: "طريقة"
linktitle: "TryParse"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. يحول تمثيل السلسلة لـ MultiDecodeType إلى مثاله. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فاشلًا في C++."
type: docs
weight: 1100
url: /ar/cpp/aspose.barcode.barcoderecognition/multidecodetype/tryparse/
---
## MultiDecodeType::TryParse method


يحول تمثيل السلسلة لـ [MultiDecodeType](../) إلى مثاله. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فاشلًا.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::MultiDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| parsingType | System::String | سلسلة بالتنسيق إما "AllSupportedTypes" أو "EAN8,EAN13,CodaBar" للتحويل. |
| result | System::SharedPtr\<MultiDecodeType\>\& | يتم إرجاع [MultiDecodeType](../) فعلي عندما يكتمل التحويل بنجاح؛ |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## ملاحظات



وإلا فإنه يُرجع نوعًا غير محدد.

أو [MultiDecodeType](../) (\"None\").

## انظر أيضًا

* Class [MultiDecodeType](../)
* Class [MultiDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
