---
title: "طريقة"
linktitle: "TryParse"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. يحول تمثيل السلسلة لـ BaseEncodeType إلى مثاله. قيمة الإرجاع تشير إلى ما إذا كان التحويل قد نجح أو فشل في C++."
type: docs
weight: 400
url: /ar/cpp/aspose.barcode.generation/encodetypes/tryparse/
---
## EncodeTypes::TryParse method


يقوم بتحويل تمثيل السلسلة من [BaseEncodeType](../../baseencodetype/) إلى مثاله. قيمة الإرجاع تشير إلى ما إذا كان التحويل ناجحًا أم فشل.

```cpp
static bool Aspose::BarCode::Generation::EncodeTypes::TryParse(System::String parsingType, System::SharedPtr<BaseEncodeType> &result)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| parsingType | System::String | سلسلة بالتنسيق "Index:-1; Name:None" للتحويل. |
| result | System::SharedPtr\<BaseEncodeType\>\& | إرجاع SingleEncodeType الفعلي، عندما يكتمل التحويل بنجاح؛ |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## ملاحظات



وإلا فإنه يُرجع null.

## انظر أيضًا

* Class [BaseEncodeType](../../baseencodetype/)
* Class [EncodeTypes](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
