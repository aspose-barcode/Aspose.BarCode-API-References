---
title: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext فئة"
linktitle: "USADriveIdCodetext"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext فئة. فئة لتشفير وفك تشفير النص المضمن في رمز PDF417 لرخصة القيادة الأمريكية في C++."
type: docs
weight: 2900
url: /ar/cpp/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class


فئة لتشفير وفك تشفير النص المضمن في رمز PDF417 لرخصة القيادة الأمريكية [License](../../aspose.barcode/license/).

```cpp
class USADriveIdCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_AAMVAVersionNumber](./get_aamvaversionnumber/)() const | رقم إصدار AAMVA 00-99 |
| [get_IssuerIdentificationNumber](./get_issueridentificationnumber/)() const | هذا الرقم يحدد بشكل فريد الولاية المصدرة ويمكن الحصول عليه عن طريق الاتصال بسلطة الإصدار ISO (AAMVA). يجب ترميز الرقم الكامل المكوّن من 6 أرقام IIN. |
| [get_JurisdictionSpecificSubfile](./get_jurisdictionspecificsubfile/)() const | حقول خاصة بالولاية |
| [get_JurisdictionVersionNumber](./get_jurisdictionversionnumber/)() const | رقم إصدار الولاية 00-99 |
| [get_MandatoryElements](./get_mandatoryelements/)() const | العناصر (الحقول) الإلزامية للبطاقة |
| [get_NumberOfEntries](./get_numberofentries/)() const | عدد 00-99 من الملفات الفرعية |
| [get_OptionalElements](./get_optionalelements/)() const | العناصر (الحقول) الاختيارية للبطاقة |
| [get_SubfileDesignator](./get_subfiledesignator/)() const | يحتوي على معلومات حول الملفات الفرعية التالية، الأنواع، الإزاحات والطول. مهم: عند ضبط النوع فقط، سيتم ضبط الإزاحة والطول تلقائيًا. |
| [GetBarcodeType](./getbarcodetype/)() override | إرجاع نوع الباركود لرخصة القيادة الأمريكية (Pdf417) |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | إنشاء نص الترميز من بيانات رخصة القيادة الأمريكية |
| [InitFromString](./initfromstring/)(System::String) override | تهيئة كائن رخصة القيادة الأمريكية من نص الترميز |
| [SaveToXml](./savetoxml/)(System::SharedPtr\<System::IO::Stream\>) | يحفظ إلى XML |
| [set_AAMVAVersionNumber](./set_aamvaversionnumber/)(System::String) | رقم إصدار AAMVA 00-99 |
| [set_IssuerIdentificationNumber](./set_issueridentificationnumber/)(System::String) | هذا الرقم يحدد بشكل فريد الولاية المصدرة ويمكن الحصول عليه عن طريق الاتصال بسلطة الإصدار ISO (AAMVA). يجب ترميز الرقم الكامل المكوّن من 6 أرقام IIN. |
| [set_JurisdictionSpecificSubfile](./set_jurisdictionspecificsubfile/)(System::SharedPtr\<USADriveIdJurisdSubfile\>) | حقول خاصة بالولاية |
| [set_JurisdictionVersionNumber](./set_jurisdictionversionnumber/)(System::String) | رقم إصدار الولاية 00-99 |
| [set_MandatoryElements](./set_mandatoryelements/)(System::SharedPtr\<USADriveIdCodetext::MandatoryFields\>) | العناصر (الحقول) الإلزامية للبطاقة |
| [set_NumberOfEntries](./set_numberofentries/)(int32_t) | عدد 00-99 من الملفات الفرعية |
| [set_OptionalElements](./set_optionalelements/)(System::SharedPtr\<USADriveIdCodetext::OptionalFields\>) | العناصر (الحقول) الاختيارية للبطاقة |
| [set_SubfileDesignator](./set_subfiledesignator/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<USADriveIdCodetext::SubfileProperties\>>>) | يحتوي على معلومات حول الملفات الفرعية التالية، الأنواع، الإزاحات والطول. مهم: عند ضبط النوع فقط، سيتم ضبط الإزاحة والطول تلقائيًا. |
| [USADriveIdCodetext](./usadriveidcodetext/)() | المنشئ الافتراضي |
## انظر أيضًا

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
