---
title: "طريقة"
linktitle: "TryParse"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. تحاول تحليل عنوان URI غير المضغوط لـ GS1 Digital Link وتعيد أخطاء التحقق المهيكلة في C++."
type: docs
weight: 2000
url: /ar/cpp/aspose.barcode.complexbarcode/gs1digitallink/tryparse/
---
## GS1DigitalLink::TryParse method


يحاول تحليل عنوان URI غير مضغوط للرابط الرقمي GS1 ويعيد أخطاء تحقق منظمة.

```cpp
static bool Aspose::BarCode::ComplexBarcode::GS1DigitalLink::TryParse(System::String value, System::SharedPtr<GS1DigitalLink> &result, System::SharedPtr<Common::GS1ValidationResult> &validationResult)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | System::String | عنوان URI لـ GS1 Digital Link للتحليل. |
| result | System::SharedPtr\<GS1DigitalLink\>\& | عند إرجاع هذه الطريقة true، يحتوي على GS1 Digital Link الذي تم تحليله؛ وإلا يكون null. |
| validationResult | System::SharedPtr\<Common::GS1ValidationResult\>\& | يحتوي على نتيجة التحقق، أو null عندما تكون *value*  null. |

### ReturnValue

True عندما ينجح التحليل؛ وإلا false.

## انظر أيضًا

* Class [GS1DigitalLink](../)
* Class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* Class [GS1DigitalLink](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
