---
title: "Aspose::BarCode::Generation::CodetextParameters class"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::Generation::CodetextParameters. معلمات النص المشفر في C++."
type: docs
weight: 1500
url: /ar/cpp/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class


معلمات Codetext.

```cpp
class CodetextParameters : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_Alignment](./get_alignment/)() const | يحصل على محاذاة نص الكود. القيمة الافتراضية: [StringAlignment.Center](../textalignment/). |
| [get_Color](./get_color/)() const | حدد لون عرض CodeText. القيمة الافتراضية: Color.Black. |
| [get_Font](./get_font/)() const | حدد خط عرض CodeText. القيمة الافتراضية: Arial 5pt عادي. يتم تجاهلها إذا تم تعيين FontMode إلى [FontMode.Auto](../aztecencodemode/). |
| [get_FontMode](./get_fontmode/)() const | حدد FontMode. إذا تم تعيين FontMode إلى Auto، سيتم حساب حجم الخط تلقائيًا بناءً على قيمة xDimension. يُنصح باستخدام [FontMode.Auto](../aztecencodemode/) خاصةً في [AutoSizeMode.Nearest](../autosizemode/) أو [AutoSizeMode.Interpolation](../autosizemode/). القيمة الافتراضية: [FontMode.Auto](../aztecencodemode/). |
| [get_Location](./get_location/)() const | حدد موقع عرض CodeText، اضبطه على [CodeLocation.None](../codelocation/) لإخفاء CodeText. القيمة الافتراضية: [CodeLocation.Below](../codelocation/) للباركودات أحادية الأبعاد و[CodeLocation.None](../codelocation/) للباركودات ثنائية الأبعاد. |
| [get_NoWrap](./get_nowrap/)() const | حدد التفاف الكلمات (فواصل الأسطر) داخل النص. القيمة الافتراضية: false. |
| [get_Space](./get_space/)() const | المسافة بين CodeText و[BarCode](../../aspose.barcode/) بوحدة [Unit ](../unit/). القيمة الافتراضية: 2pt. يتم تجاهلها بالنسبة إلى EAN8، EAN13، UPCE، UPCA، ISBN، ISMN، ISSN، UpcaGs1DatabarCoupon. |
| [get_TwoDDisplayText](./get_twoddisplaytext/)() const | النص الذي سيُعرض بدلاً من codetext في الباركودات ثنائية الأبعاد. يُستخدم لـ: Aztec، Pdf417، DataMatrix، QR، MaxiCode، DotCode |
| [set_Alignment](./set_alignment/)(TextAlignment) | يضبط محاذاة نص الكود. القيمة الافتراضية: [StringAlignment.Center](../textalignment/). |
| [set_Color](./set_color/)(System::Drawing::Color) | حدد لون عرض CodeText. القيمة الافتراضية: Color.Black. |
| [set_FontMode](./set_fontmode/)(Aspose::BarCode::Generation::FontMode) | حدد FontMode. إذا تم تعيين FontMode إلى Auto، سيتم حساب حجم الخط تلقائيًا بناءً على قيمة xDimension. يُنصح باستخدام [FontMode.Auto](../aztecencodemode/) خاصةً في [AutoSizeMode.Nearest](../autosizemode/) أو [AutoSizeMode.Interpolation](../autosizemode/). القيمة الافتراضية: [FontMode.Auto](../aztecencodemode/). |
| [set_Location](./set_location/)(CodeLocation) | حدد موقع عرض CodeText، اضبطه على [CodeLocation.None](../codelocation/) لإخفاء CodeText. القيمة الافتراضية: [CodeLocation.Below](../codelocation/) للباركودات أحادية الأبعاد و[CodeLocation.None](../codelocation/) للباركودات ثنائية الأبعاد. |
| [set_NoWrap](./set_nowrap/)(bool) | حدد التفاف الكلمات (فواصل الأسطر) داخل النص. القيمة الافتراضية: false. |
| [set_Space](./set_space/)(System::SharedPtr\<Unit\>) | المسافة بين CodeText و[BarCode](../../aspose.barcode/) بوحدة [Unit ](../unit/). القيمة الافتراضية: 2pt. يتم تجاهلها بالنسبة إلى EAN8، EAN13، UPCE، UPCA، ISBN، ISMN، ISSN، UpcaGs1DatabarCoupon. |
| [set_TwoDDisplayText](./set_twoddisplaytext/)(System::String) | النص الذي سيُعرض بدلاً من codetext في الباركودات ثنائية الأبعاد. يُستخدم لـ: Aztec، Pdf417، DataMatrix، QR، MaxiCode، DotCode |
| [ToString](./tostring/)() const override | يعيد تمثيلًا نصيًا مقروءًا للإنسان لهذا [CodetextParameters](./). |
## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
