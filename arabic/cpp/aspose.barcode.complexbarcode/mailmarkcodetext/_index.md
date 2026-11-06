---
title: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext فئة"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext فئة. فئة لتشفير وفك تشفير النص المضمن في رمز Mailmark رباعي الحالة الخاص بـ Royal Mail في C++."
type: docs
weight: 1500
url: /ar/cpp/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class


فئة لتشفير وفك تشفير النص المضمن في رمز Royal Mailmark رباعي الحالة.

```cpp
class MailmarkCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_Class](./get_class/)() const | "0" - خالي أو اختبار "1" - 1C (تجزئة) "2" - 2C (تجزئة) "3" - 3C (تجزئة) "4" - مميز (RetailPublishing Mail) (للاستخدام المستقبلي المحتمل) "5" - مؤجل (تجزئة) "6" - هواء (تجزئة) (للاستخدام المستقبلي المحتمل) "7" - سطح (تجزئة) (للاستخدام المستقبلي المحتمل) "8" - مميز (وصول الشبكة) "9" - قياسي (وصول الشبكة) |
| [get_DestinationPostCodePlusDPS](./get_destinationpostcodeplusdps/)() const | يجب أن يتوافق كل من PC و DP مع تنسيق PAF. سلسلة مكونة من تسعة أحرف تمثل "XY11     " دوليًا (لاحظ المسافات الخمس المتبقية) أو نمط من الأحرف يمثل رمز فرز محلي. يتكون رمز الفرز المحلي من رمز بريدي خارجي، ورمز بريدي داخلي، وملحق نقطة التسليم. |
| [get_Format](./get_format/)() const | "0" – خالي أو اختبار "1" – رسالة "2" – رسالة كبيرة |
| [get_ItemID](./get_itemid/)() const | القيمة القصوى هي 99999999. |
| [get_SupplychainID](./get_supplychainid/)() const | القيم القصوى هي 99 لباركود C و 999999 لباركود L. |
| [get_VersionID](./get_versionid/)() const | حاليًا "1" – لباركود Mailmark (0 و 2 إلى 9 و A إلى Z محجوز للاستخدام المستقبلي) |
| [GetBarcodeType](./getbarcodetype/)() override | يحصل على نوع الباركود. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | إنشاء نص الترميز من بيانات Mailmark. |
| [InitFromString](./initfromstring/)(System::String) override | يُهيئ بيانات Mailmark من نص الترميز المُنشأ. |
| [MailmarkCodetext](./mailmarkcodetext/)() | يُهيئ مثيلًا جديدًا من الفئة [MailmarkCodetext](./). |
| [set_Class](./set_class/)(System::String) | "0" - خالي أو اختبار "1" - 1C (تجزئة) "2" - 2C (تجزئة) "3" - 3C (تجزئة) "4" - مميز (RetailPublishing Mail) (للاستخدام المستقبلي المحتمل) "5" - مؤجل (تجزئة) "6" - هواء (تجزئة) (للاستخدام المستقبلي المحتمل) "7" - سطح (تجزئة) (للاستخدام المستقبلي المحتمل) "8" - مميز (وصول الشبكة) "9" - قياسي (وصول الشبكة) |
| [set_DestinationPostCodePlusDPS](./set_destinationpostcodeplusdps/)(System::String) | يجب أن يتوافق كل من PC و DP مع تنسيق PAF. سلسلة مكونة من تسعة أحرف تمثل "XY11     " دوليًا (لاحظ المسافات الخمس المتبقية) أو نمط من الأحرف يمثل رمز فرز محلي. يتكون رمز الفرز المحلي من رمز بريدي خارجي، ورمز بريدي داخلي، وملحق نقطة التسليم. |
| [set_Format](./set_format/)(int32_t) | "0" – خالي أو اختبار "1" – رسالة "2" – رسالة كبيرة |
| [set_ItemID](./set_itemid/)(int32_t) | القيمة القصوى هي 99999999. |
| [set_SupplychainID](./set_supplychainid/)(int32_t) | القيم القصوى هي 99 لباركود C و 999999 لباركود L. |
| [set_VersionID](./set_versionid/)(int32_t) | حاليًا "1" – لباركود Mailmark (0 و 2 إلى 9 و A إلى Z محجوز للاستخدام المستقبلي) |
## انظر أيضًا

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
