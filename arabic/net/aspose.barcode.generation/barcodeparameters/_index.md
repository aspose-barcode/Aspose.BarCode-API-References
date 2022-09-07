---
title: BarcodeParameters
second_title: Aspose.BarCode لمرجع .NET API
description: معلمات إنشاء الباركود .
type: docs
weight: 500
url: /ar/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

معلمات إنشاء الباركود .

```csharp
public class BarcodeParameters
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost) { get; } | معلمات الباركود الأسترالي. |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec) { get; } | معلمات Aztec . |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor) { get; set; } | لون الأشرطة . القيمة الافتراضية: اللون. أسود . |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight) { get; set; } | ارتفاع أشرطة الباركود 1D في[`Unit`](../unit) value. تجاهل إذاAutoSizeMode تم تعيين الخاصية إلى AutoSizeMode.Nearest أو AutoSizeMode.Interpolation. |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction) { get; set; } | الحصول على أو تعيين قيمة تقليل الأشرطة المستخدمة لتعويض انتشار الحبر أثناء الطباعة. القيمة الافتراضية: 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow) { get; set; } | اعرض رقم المجموع الاختباري دائمًا في النص الذي يمكن للبشر قراءته للرموز الشريطية Code128 و GS1Code128. |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar) { get; } | معلمات Codabar . |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock) { get; } | معلمات Codablock . |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k) { get; } | كود 16K معلمات . |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters) { get; } | معلمات النص البرمجي . |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon) { get; } | معلمات القسيمة. تستخدم لـ UpcaGs1DatabarCoupon ، UpcaGs1Code128Coupon. |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar) { get; } | معلمات قاعدة البيانات. |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix) { get; } | معلمات DataMatrix . |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode) { get; } | معلمات DotCode . |
| [EnableEscape](../../aspose.barcode.generation/barcodeparameters/enableescape) { get; set; } | يشير إلى ما إذا كان يشرح الحرف "\" كحرف هروب في خاصية CodeText. يُستخدم لـ Pdf417 ، DataMatrix ، Code128 only إذا كان EnableEscape صحيحًا ، فسيتم شرح "\" كحرف هروب خاص. وبخلاف ذلك ، يعمل "\" كأحرف عادية . Aspose.BarCode يدعم إدخال رمز ASCII العشري والذاكرة لأحرف رمز التحكم ASCII. على سبيل المثال ، يرمز \ 013 و \\ CR إلى CR. |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الأشرطة مملوءة . فقط للرموز الشريطية أحادية الأبعاد. |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar) { get; set; } | معلمات شريط GS1 المركب . |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled) { get; set; } | تفعيل المجموع الاختباري أثناء إنشاء الرموز الشريطية 1D. |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf) { get; } | معلمات ITF . |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode) { get; } | معلمات MaxiCode . |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding) { get; } | حشوة الباركود . القيمة الافتراضية: 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode) { get; } | معلمات رمز التصحيح . |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417) { get; } | معلمات PDF417. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal) { get; } | المعلمات البريدية. تستخدم لـ Postnet ، Planet . |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr) { get; } | معلمات QR . |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement) { get; } | معلمات الملحق. تستخدم في Interleaved2of5 و Standard2of5 و EAN13 و EAN8 و UPCA و UPCE و ISBN و ISSN و ISMN. |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect) { get; set; } | فقط للرموز الشريطية 1D . إذا كان نص الكود غير صحيح وتم تعيين القيمة على "صحيح" - فسيتم طرح استثناء. وإلا فسيتم تصحيح نص الكود ليطابق مواصفات الباركود . سيتم طرح استثناء دائمًا لـ: رموز قاعدة البيانات إذا كان نص الكود غير صحيح. . |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio) { get; set; } | نسبة الأشرطة العريضة إلى الأشرطة الضيقة. القيمة الافتراضية: 3 ، أي أن الأشرطة العريضة 3 أضعاف عرض الأشرطة الضيقة. تستخدم لـ ITF و PZN و PharmaCode و Standard2of5 و Interleaved2of5 و Matrix2of5 و ItalianPost25 و IATA2of5 و VIN و DeutschePost ، OPC ، Code32 ، DataLogic2of5 ، PatchCode ، Code39Extended ، Code39Standard |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension) { get; set; } | البعد x هو أصغر عرض لوحدة أشرطة أو مسافات شريط الباركود. ستؤدي زيادة هذا إلى زيادة عرض صورة الباركود بالكامل.AutoSizeMode تم تعيين الخاصية إلى AutoSizeMode.Nearest أو AutoSizeMode.Interpolation. |

### أنظر أيضا

* مساحة الاسم [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* المجسم [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
