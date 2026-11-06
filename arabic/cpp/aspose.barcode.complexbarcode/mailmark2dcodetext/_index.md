---
title: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext فئة"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext فئة. فئة للترميز وفك الترميز للنص المضمن في رمز Royal Mail 2D Mailmark في C++."
type: docs
weight: 1400
url: /ar/cpp/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class


فئة لتشفير وفك تشفير النص المضمن في رمز Royal Mail 2D Mailmark.

```cpp
class Mailmark2DCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_Class](./get_class/)() const | يحدد فئة العنصر. |
| [get_CustomerContent](./get_customercontent/)() const | مساحة اختيارية لاستخدام العميل. |
| [get_CustomerContentEncodeMode](./get_customercontentencodemode/)() const | وضع الترميز لباركود Datamatrix. القيمة الافتراضية: EncodeMode.C40. |
| [get_DataMatrixType](./get_datamatrixtype/)() const | نوع 2D Mailmark يحدد حجم باركود Data Matrix. |
| [get_DestinationPostCodeAndDPS](./get_destinationpostcodeanddps/)() const | يحتوي على الرمز البريدي لعنوان التسليم [Address](../address/) مع DPS. إذا كان داخليًا، فإن الرمز البريدي/DP يحتوي على عدد الأحرف التالي: المنطقة (حرف أو حرفين) الحي (حرف أو حرفين) القطاع (حرف واحد) الوحدة (حرفان) DPS (حرفان). يجب أن يتوافق الرمز البريدي و DPS مع تنسيق PAF® صالح. |
| [get_InformationTypeID](./get_informationtypeid/)() const | يحدد حمولة باركود Royal Mail Mailmark لكل نوع منتج. |
| [get_ItemID](./get_itemid/)() const | يحدد العنصر الفريد داخل معرف سلسلة الإمداد. يجب أن يحمل كل باركود Mailmark معرفًا حتى يمكن تحديده بشكل فريد لمدة لا تقل عن 90 يومًا. القيمة القصوى: 99999999. |
| [get_ReturnToSenderPostCode](./get_returntosenderpostcode/)() const | يحتوي على رمز البريد للعودة إلى المرسل ولكن بدون DPS. يجب أن يتوافق الرمز البريدي (بدون DPS) مع تنسيق PAF®. |
| [get_RTSFlag](./get_rtsflag/)() const | علامة تشير إلى مستوى خدمة العودة إلى المرسل المطلوبة. |
| [get_SupplyChainID](./get_supplychainid/)() const | يحدد المجموعة الفريدة من العملاء المشاركين في الإرسال. القيمة القصوى: 9999999. |
| [get_UPUCountryID](./get_upucountryid/)() const | يحدد معرف دولة UPU. الحد الأقصى للطول: 4 أحرف. |
| [get_VersionID](./get_versionid/)() const | يحدد إصدار الباركود وفقًا لكل معرف نوع المعلومات. |
| [GetBarcodeType](./getbarcodetype/)() override | يحصل على نوع الباركود. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | إنشاء نص الترميز من بيانات Mailmark. |
| [InitFromString](./initfromstring/)(System::String) override | يُهيئ بيانات Mailmark من نص الترميز المُنشأ. |
| [Mailmark2DCodetext](./mailmark2dcodetext/)() | منشئ. إنشاء مثيل افتراضي من الفئة [Mailmark2DCodetext](./). |
| [set_Class](./set_class/)(System::String) | يحدد فئة العنصر. |
| [set_CustomerContent](./set_customercontent/)(System::String) | مساحة اختيارية لاستخدام العميل. |
| [set_CustomerContentEncodeMode](./set_customercontentencodemode/)(Generation::DataMatrixEncodeMode) | وضع الترميز لباركود Datamatrix. القيمة الافتراضية: EncodeMode.C40. |
| [set_DataMatrixType](./set_datamatrixtype/)(Mailmark2DType) | نوع 2D Mailmark يحدد حجم باركود Data Matrix. |
| [set_DestinationPostCodeAndDPS](./set_destinationpostcodeanddps/)(System::String) | يحتوي على الرمز البريدي لعنوان التسليم [Address](../address/) مع DPS. إذا كان داخليًا، فإن الرمز البريدي/DP يحتوي على عدد الأحرف التالي: المنطقة (حرف أو حرفين) الحي (حرف أو حرفين) القطاع (حرف واحد) الوحدة (حرفان) DPS (حرفان). يجب أن يتوافق الرمز البريدي و DPS مع تنسيق PAF® صالح. |
| [set_InformationTypeID](./set_informationtypeid/)(System::String) | يحدد حمولة باركود Royal Mail Mailmark لكل نوع منتج. |
| [set_ItemID](./set_itemid/)(int32_t) | يحدد العنصر الفريد داخل معرف سلسلة الإمداد. يجب أن يحمل كل باركود Mailmark معرفًا حتى يمكن تحديده بشكل فريد لمدة لا تقل عن 90 يومًا. القيمة القصوى: 99999999. |
| [set_ReturnToSenderPostCode](./set_returntosenderpostcode/)(System::String) | يحتوي على رمز البريد للعودة إلى المرسل ولكن بدون DPS. يجب أن يتوافق الرمز البريدي (بدون DPS) مع تنسيق PAF®. |
| [set_RTSFlag](./set_rtsflag/)(System::String) | علامة تشير إلى مستوى خدمة العودة إلى المرسل المطلوبة. |
| [set_SupplyChainID](./set_supplychainid/)(int32_t) | يحدد المجموعة الفريدة من العملاء المشاركين في الإرسال. القيمة القصوى: 9999999. |
| [set_UPUCountryID](./set_upucountryid/)(System::String) | يحدد معرف دولة UPU. الحد الأقصى للطول: 4 أحرف. |
| [set_VersionID](./set_versionid/)(System::String) | يحدد إصدار الباركود وفقًا لكل معرف نوع المعلومات. |
## انظر أيضًا

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
