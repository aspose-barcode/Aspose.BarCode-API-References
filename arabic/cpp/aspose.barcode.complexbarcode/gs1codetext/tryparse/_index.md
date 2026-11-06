---
title: "طريقة"
linktitle: "TryParse"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. يحاول تحليل سلسلة عنصر GS1 محاطة بالأقواس بالشكل (AI)value(AI)value ويعيد أخطاء تحقق منظمة. يجب كتابة الحرف الحرفي ''('' داخل قيمة كـ (; لا يُدعم أي تسلسل هروب آخر، و '')'' لا يتطلب الهروب في C++."
type: docs
weight: 1600
url: /ar/cpp/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext::TryParse method


يحاول تحليل سلسلة عنصر GS1 بين الأقواس بالشكل (AI)value(AI)value ويعيد أخطاء التحقق المهيكلة. يجب كتابة '(' حرفيًا داخل القيمة كـ (; لا يتم دعم أي تسلسل هروب آخر، ولا يلزم هروب ')' .

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1Codetext::TryParse(System::String value, System::SharedPtr<GS1Codetext> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | System::String | سلسلة عنصر GS1 محاطة بالأقواس لتتم معالجتها. |
| result | System::SharedPtr\<GS1Codetext\>\& | عند إرجاع هذه الطريقة true، يحتوي على نص شفرة GS1 المحلل؛ وإلا يكون null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | يحتوي على نتيجة التحقق، أو null عندما تكون *value*  null. |

### ReturnValue

True عندما ينجح التحليل؛ وإلا false.

## انظر أيضًا

* Class [GS1Codetext](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1Codetext](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
