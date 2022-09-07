---
title: BarCodeGeneratorControl
second_title: Aspose.BarCode لمرجع .NET API
description: BarCode Windows Control  انتقل إلى لوحة مربع الأدوات وأضف Aspose.BarCode.dll وسترى ظهور BarcodeGeneratorControl . فقط اسحبه وأفلته في نموذج Windows. انظر
type: docs
weight: 1050
url: /ar/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Control ، انتقل إلى لوحة مربع الأدوات وأضف Aspose.BarCode.dll، وسترى ظهور BarcodeGeneratorControl . فقط اسحبه وأفلته في نموذج Windows. انظر

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode) { get; set; } | الحصول على أو تحديد الوضع الذي يتم من خلاله تغيير حجم الباركود تلقائيًا. القيمة الافتراضية هي AutoSizeMode. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor) { get; set; } | لون الخلفية لصورة الباركود. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight) { get; } | ارتفاع صورة الرمز الشريطي عندما[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) تم تعيين الخاصية إلى AutoSizeMode.Nearest أو AutoSizeMode.Interpolation. |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings) { get; } | الحصول على أو تعيين معلمات حشوة الباركود[`Padding`](../../aspose.barcode.generation/padding) . |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype) { get; set; } | نوع ترميز BarCode (الترميز) . Use[`EncodeTypes`](../../aspose.barcode.generation/encodetypes) للحصول على الرموز الحالية. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth) { get; } | عرض صورة الرمز الشريطي عندما[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) تم تعيين الخاصية إلى AutoSizeMode.Nearest أو AutoSizeMode.Interpolation. |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor) { get; set; } | لون الأشرطة . |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight) { get; } | ارتفاع أشرطة الباركود 1D . تم التجاهل إذا[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) تم تعيين الخاصية إلى AutoSizeMode.Nearest أو AutoSizeMode.Interpolation. |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border) { get; } | الحصول على أو تعيين معلمات الحدود[`BorderParameters`](../../aspose.barcode.generation/borderparameters) . |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove) { get; } | تسمية توضيحية فوق صورة الرمز الشريطي. نرى[`CaptionParameters`](../../aspose.barcode.generation/captionparameters) . |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow) { get; } | تسمية توضيحية أسفل صورة الرمز الشريطي. نرى[`CaptionParameters`](../../aspose.barcode.generation/captionparameters) . |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow) { get; set; } | اعرض رقم المجموع الاختباري دائمًا في النص الذي يمكن للبشر قراءته للرموز الشريطية Code128 و GS1Code128. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext) { get; set; } | البيانات المراد تشفيرها ، قد يكون للأنواع المختلفة من الرموز الشريطية قيود طول نص CodeText مختلفة. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters) { get; } | الحصول على أو تعيين معلمات CodeText[`CodetextParameters`](../../aspose.barcode.generation/codetextparameters) . |
| [EnableEscape](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/enableescape) { get; set; } | يشير إلى ما إذا كان يشرح الحرف "\" كحرف هروب في خاصية CodeText. يُستخدم لـ Pdf417 ، DataMatrix ، Code128 only إذا كان EnableEscape صحيحًا ، فسيتم شرح "\" كحرف هروب خاص. وبخلاف ذلك ، يعمل "\" كأحرف عادية . Aspose.BarCode يدعم إدخال رمز ASCII العشري والذاكرة لأحرف رمز التحكم ASCII. على سبيل المثال ، يرمز \ 013 و \\ CR إلى CR. |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype) { get; set; } | نوع ترميز BarCode (الترميز) . Use[`EncodeTypes`](../../aspose.barcode.generation/encodetypes) للحصول على الرموز الحالية. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كانت الأشرطة مملوءة . فقط للرموز الشريطية أحادية الأبعاد . |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled) { get; set; } | تفعيل المجموع الاختباري أثناء إنشاء الرموز الشريطية 1D. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution) { get; set; } | الحصول على دقة وضوح صورة BarCode أو تعيينها. قيمة واحدة لكلا البعدين. القيمة الافتراضية: 96 نقطة في البوصة . |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle) { get; set; } | زاوية دوران صورة الرمز الشريطي ، مقاسة بالدرجة ، على سبيل المثال ، RotationAngle = 0 أو RotationAngle = 360 تعني عدم وجود دوران. إذا لم يكن RotationAngle يساوي 90 أو 180 أو 270 أو 0 ، فقد يؤدي ذلك إلى زيادة صعوبة قراءة الماسح الضوئي للصورة . |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific) { get; } | معلمات محددة |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect) { get; set; } | فقط للرموز الشريطية 1D . إذا كان نص الكود غير صحيح وتم تعيين القيمة على "صحيح" - فسيتم طرح استثناء. وإلا فسيتم تصحيح نص الكود ليطابق مواصفات الباركود . سيتم طرح استثناء دائمًا لـ: رموز قاعدة البيانات إذا كان نص الكود غير صحيح. . |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio) { get; set; } | نسبة الأشرطة العريضة إلى الأشرطة الضيقة. القيمة الافتراضية: 3 ، أي أن الأشرطة العريضة 3 أضعاف عرض الأشرطة الضيقة. تستخدم لـ ITF و PZN و PharmaCode و Standard2of5 و Interleaved2of5 و Matrix2of5 و ItalianPost25 و IATA2of5 و VIN و DeutschePost ، OPC ، Code32 ، DataLogic2of5 ، PatchCode ، Code39Extended ، Code39Standard |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension) { get; } | البعد X هو أصغر عرض لوحدة أشرطة أو مسافات شريط الباركود. ستؤدي زيادة هذا إلى زيادة عرض صورة الباركود بالكامل.[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) تم تعيين الخاصية إلى AutoSizeMode.Nearest أو AutoSizeMode.Interpolation. |

### أنظر أيضا

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol)
* مساحة الاسم [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms)
* المجسم [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
