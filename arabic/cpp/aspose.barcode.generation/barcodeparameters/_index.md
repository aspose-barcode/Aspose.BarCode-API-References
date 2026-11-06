---
title: "Aspose::BarCode::Generation::BarcodeParameters فئة"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::Generation::BarcodeParameters فئة. معلمات توليد الباركود في C++."
type: docs
weight: 500
url: /ar/cpp/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class


معلمات توليد الباركود.

```cpp
class BarcodeParameters : public System::Object
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_AustralianPost](./get_australianpost/)() const | معلمات الباركود AustralianPost. |
| [get_Aztec](./get_aztec/)() const | معلمات Aztec. |
| [get_BarColor](./get_barcolor/)() const | لون الأعمدة. القيمة الافتراضية: Color.Black. |
| [get_BarHeight](./get_barheight/)() const | ارتفاع أعمدة الباركودات أحادية الأبعاد في قيمة [Unit](../unit/). يتم تجاهله إذا تم تعيين خاصية [BaseGenerationParameters::AutoSizeMode](../) إلى [AutoSizeMode.Nearest](../autosizemode/) أو [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_BarWidthReduction](./get_barwidthreduction/)() const | احصل أو عيّن قيمة تقليل الأعمدة التي تُستخدم لتعويض انتشار الحبر أثناء الطباعة. القيمة الافتراضية: 0 |
| [get_ChecksumAlwaysShow](./get_checksumalwaysshow/)() const | اعرض دائمًا رقم التحقق في النص القابل للقراءة للإنسان لباركودات Code128 وGS1Code128. |
| [get_Codabar](./get_codabar/)() const | معلمات Codabar. |
| [get_Codablock](./get_codablock/)() const | معلمات Codablock. |
| [get_Code128](./get_code128/)() const | معلمات Code128. |
| [get_Code16K](./get_code16k/)() const | معلمات Code16K. |
| [get_CodeTextParameters](./get_codetextparameters/)() const | معلمات Codetext. |
| [get_Coupon](./get_coupon/)() const | معلمات القسيمة. تُستخدم لـ UpcaGs1DatabarCoupon، UpcaGs1Code128Coupon. |
| [get_DataBar](./get_databar/)() const | معلمات Databar. |
| [get_DataMatrix](./get_datamatrix/)() const | معلمات DataMatrix. |
| [get_DotCode](./get_dotcode/)() const | معلمات DotCode. |
| [get_FilledBars](./get_filledbars/)() const | يحصل على قيمة تشير إلى ما إذا كانت الأشرطة مملوءة. يخص فقط باركودات 1D. القيمة الافتراضية: true. |
| [get_GS1](./get_gs1/)() const | معلمات GS1. |
| [get_GS1CompositeBar](./get_gs1compositebar/)() const | معلمات شريط GS1 Composite. |
| [get_HanXin](./get_hanxin/)() const | معلمات HanXin. |
| [get_IsChecksumEnabled](./get_ischecksumenabled/)() const |  |
| [get_ITF](./get_itf/)() const | معلمات ITF. |
| [get_MaxiCode](./get_maxicode/)() const | معلمات MaxiCode. |
| [get_Padding](./get_padding/)() const | هوامش الباركود. القيمة الافتراضية: 5pt 5pt 5pt 5pt. |
| [get_PatchCode](./get_patchcode/)() const | معلمات PatchCode. |
| [get_Pdf417](./get_pdf417/)() const | معلمات PDF417. |
| [get_Postal](./get_postal/)() const | معلمات البريد. تُستخدم لـ Postnet، Planet. |
| [get_QR](./get_qr/)() const | معلمات QR وMicroQR وRectMicroQR. |
| [get_Supplement](./get_supplement/)() const | معلمات الإضافة. تُستخدم لـ Interleaved2of5، Standard2of5، EAN13، EAN8، UPCA، UPCE، ISBN، ISSN، ISMN. |
| [get_ThrowExceptionWhenCodeTextIncorrect](./get_throwexceptionwhencodetextincorrect/)() const | يخص فقط باركودات 1D. إذا كان نص الرمز غير صحيح وتم تعيين القيمة إلى true - سيتم إلقاء استثناء. وإلا سيتم تصحيح نص الرمز ليتطابق مع مواصفات الباركود. سيتم دائمًا إلقاء الاستثناء لـ: رموز Databar إذا كان نص الرمز غير صحيح. لن يتم إلقاء الاستثناء أبدًا لـ: AustraliaPost، SingapurePost، Code39FullASCII، Code93، Code16K، رموز Code128 إذا كان نص الرمز غير صحيح. |
| [get_WideNarrowRatio](./get_widenarrowratio/)() const | نسبة الأشرطة العريضة إلى الأشرطة الضيقة. القيمة الافتراضية: 3، أي أن الأشرطة العريضة أوسع بثلاث مرات من الأشرطة الضيقة. يُستخدم لـ: ITF، PZN، PharmaCode، Standard2of5، Interleaved2of5، Matrix2of5، ItalianPost25، IATA2of5، VIN، DeutschePost، OPC، Code32، DataLogic2of5، PatchCode، Code39، Code39FullASCII. |
| [get_XDimension](./get_xdimension/)() const | البُعد x هو أصغر عرض لوحدة [BarCode](../../aspose.barcode/) من الأشرطة أو الفراغات. زيادة هذا سيزيد من عرض صورة الباركود بالكامل. يتم تجاهله إذا تم تعيين خاصية [BaseGenerationParameters::AutoSizeMode](../) إلى [AutoSizeMode.Nearest](../autosizemode/) أو [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_BarColor](./set_barcolor/)(System::Drawing::Color) | لون الأعمدة. القيمة الافتراضية: Color.Black. |
| [set_BarHeight](./set_barheight/)(System::SharedPtr\<Unit\>) | ارتفاع أعمدة الباركودات أحادية الأبعاد في قيمة [Unit](../unit/). يتم تجاهله إذا تم تعيين خاصية [BaseGenerationParameters::AutoSizeMode](../) إلى [AutoSizeMode.Nearest](../autosizemode/) أو [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_BarWidthReduction](./set_barwidthreduction/)(System::SharedPtr\<Unit\>) | احصل أو عيّن قيمة تقليل الأعمدة التي تُستخدم لتعويض انتشار الحبر أثناء الطباعة. القيمة الافتراضية: 0 |
| [set_ChecksumAlwaysShow](./set_checksumalwaysshow/)(bool) | اعرض دائمًا رقم التحقق في النص القابل للقراءة للإنسان لباركودات Code128 وGS1Code128. |
| [set_FilledBars](./set_filledbars/)(bool) | يضبط قيمة تشير إلى ما إذا كانت الأشرطة مملوءة. يخص فقط باركودات 1D. القيمة الافتراضية: true. |
| [set_GS1CompositeBar](./set_gs1compositebar/)(System::SharedPtr\<GS1CompositeBarParameters\>) | معلمات شريط GS1 Composite. |
| [set_IsChecksumEnabled](./set_ischecksumenabled/)(EnableChecksum) |  |
| [set_ThrowExceptionWhenCodeTextIncorrect](./set_throwexceptionwhencodetextincorrect/)(bool) | يخص فقط باركودات 1D. إذا كان نص الرمز غير صحيح وتم تعيين القيمة إلى true - سيتم إلقاء استثناء. وإلا سيتم تصحيح نص الرمز ليتطابق مع مواصفات الباركود. سيتم دائمًا إلقاء الاستثناء لـ: رموز Databar إذا كان نص الرمز غير صحيح. لن يتم إلقاء الاستثناء أبدًا لـ: AustraliaPost، SingapurePost، Code39FullASCII، Code93، Code16K، رموز Code128 إذا كان نص الرمز غير صحيح. |
| [set_WideNarrowRatio](./set_widenarrowratio/)(float) | نسبة الأشرطة العريضة إلى الأشرطة الضيقة. القيمة الافتراضية: 3، أي أن الأشرطة العريضة أوسع بثلاث مرات من الأشرطة الضيقة. يُستخدم لـ: ITF، PZN، PharmaCode، Standard2of5، Interleaved2of5، Matrix2of5، ItalianPost25، IATA2of5، VIN، DeutschePost، OPC، Code32، DataLogic2of5، PatchCode، Code39، Code39FullASCII. |
| [set_XDimension](./set_xdimension/)(System::SharedPtr\<Unit\>) | البُعد x هو أصغر عرض لوحدة [BarCode](../../aspose.barcode/) من الأشرطة أو الفراغات. زيادة هذا سيزيد من عرض صورة الباركود بالكامل. يتم تجاهله إذا تم تعيين خاصية [BaseGenerationParameters::AutoSizeMode](../) إلى [AutoSizeMode.Nearest](../autosizemode/) أو [AutoSizeMode.Interpolation](../autosizemode/). |
## انظر أيضًا

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
