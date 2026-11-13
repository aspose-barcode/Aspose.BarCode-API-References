---
title: "BarcodeParameters"
second_title: "Aspose.BarCode لـ Python عبر .NET مرجع API"
description: 
type: docs
url: /ar/python-net/aspose.barcode.generation/barcodeparameters/
---

## BarcodeParameters class

معلمات توليد الباركود.

يعرض نوع BarcodeParameters الأعضاء التالية:
## الخصائص
| الاسم | الوصف |
| :- | :- |
| x_dimension | البُعد-x هو أصغر عرض لوحدة أشرطة أو فراغات الباركود.<br/>            زيادة هذا سيزيد عرض صورة الباركود بالكامل.<br/>            يتم التجاهل إذا تم تعيين خاصية [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) إلى AutoSizeMode.Nearest أو AutoSizeMode.Interpolation. |
| bar_height | ارتفاع أشرطة الباركود أحادي الأبعاد بوحدة [Unit](/barcode/python-net/aspose.barcode.generation/unit/).<br/>            يتم التجاهل إذا تم تعيين خاصية [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) إلى AutoSizeMode.Nearest أو AutoSizeMode.Interpolation. |
| bar_color | لون الأشرطة.<br/>            القيمة الافتراضية: Color.Black. |
| padding | هوامش الباركود.<br/>            القيمة الافتراضية: 5pt 5pt 5pt 5pt. |
| checksum_always_show | عرض رقم التحقق دائمًا في النص القابل للقراءة للإنسان لباركودات Code128 و GS1Code128. |
| is_checksum_enabled |  |
| throw_exception_when_code_text_incorrect | فقط لباركودات أحادية الأبعاد.<br/>            إذا كان نص الرمز غير صحيح وتم تعيين القيمة إلى true - سيتم رمي استثناء. وإلا سيتم تصحيح نص الرمز ليتطابق مع مواصفات الباركود.<br/>            سيتم دائمًا رمي الاستثناء لـ: Databar إذا كان نص الرمز غير صحيح.<br/>            لن يتم رمي الاستثناء أبدًا لـ: AustraliaPost، SingapurePost، Code39FullASCII، Code93، Code16K، رموز Code128 إذا كان نص الرمز غير صحيح. |
| wide_narrow_ratio | نسبة الأشرطة العريضة إلى الأشرطة الضيقة.<br/>            القيمة الافتراضية: 3، أي أن الأشرطة العريضة أوسع بثلاث مرات من الأشرطة الضيقة.<br/>            تُستخدم لـ: ITF، PZN، PharmaCode، Standard2of5، Interleaved2of5، Matrix2of5، ItalianPost25، IATA2of5، VIN، DeutschePost، OPC، Code32، DataLogic2of5، PatchCode، Code39، Code39FullASCII. |
| code_text_parameters | معلمات Codetext. |
| filled_bars | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الأشرطة مملوءة.<br/>            فقط لباركودات أحادية الأبعاد.<br/>            القيمة الافتراضية: true. |
| bar_width_reduction | يحصل أو يعيّن قيمة تقليل عرض الأشرطة المستخدمة لتعويض انتشار الحبر أثناء الطباعة.<br/>            القيمة الافتراضية: 0 |
| postal | معلمات البريد. تُستخدم لـ Postnet و Planet. |
| patch_code | معلمات PatchCode. |
| australian_post | معلمات باركود AustralianPost. |
| data_bar | معلمات Databar. |
| gs1_composite_bar | معلمات شريط GS1 Composite Bar. |
| codablock | معلمات Codablock. |
| data_matrix | معلمات DataMatrix. |
| code_16k | معلمات Code16K. |
| dot_code | معلمات DotCode. |
| itf | معلمات ITF. |
| pdf417 | معلمات PDF417. |
| qr | معلمات QR، MicroQR و RectMicroQR. |
| supplement | معلمات الإضافة. تُستخدم لـ Interleaved2of5 و Standard2of5 و EAN13 و EAN8 و UPCA و UPCE و ISBN و ISSN و ISMN. |
| maxi_code | معلمات MaxiCode. |
| aztec | معلمات Aztec. |
| code128 | معلمات Code128. |
| codabar | معلمات Codabar. |
| coupon | معلمات القسيمة. تُستخدم لـ UpcaGs1DatabarCoupon، UpcaGs1Code128Coupon. |
| han_xin | معلمات HanXin. |
| gs1 | معلمات GS1. |

### انظر أيضًا

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

