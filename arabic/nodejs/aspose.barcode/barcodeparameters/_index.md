---
title: "BarcodeParameters"
linktitle: "BarcodeParameters"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "معلمات إنشاء الباركود."
type: docs
weight: 140
url: /ar/nodejs/aspose.barcode/barcodeparameters/
---

## BarcodeParameters class

معلمات إنشاء الباركود.

```js
new BarcodeParameters()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [getAustralianPost()](#getaustralianpost) | معلمات الباركود AustralianPost. |
| [getAztec()](#getaztec) | معلمات Aztec. |
| [getBarColor()](#getbarcolor) | لون الشرائط. |
| [getBarHeight()](#getbarheight) | ارتفاع أشرطة الباركود أحادي الأبعاد بوحدة القيمة. يتم تجاهله إذا تم تعيين خاصية AutoSizeMode إلى AutoSizeMode.NEAREST أو AutoSizeMo |
| [getBarWidthReduction()](#getbarwidthreduction) | احصل على قيمة تقليل الأشرطة المستخدمة لتعويض انتشار الحبر أثناء الطباعة. |
| [getChecksumAlwaysShow()](#getchecksumalwaysshow) | اعرض دائمًا رقم التحقق في النص القابل للقراءة البشرية لباركودات Code128 و GS1Code128. |
| [getCodabar()](#getcodabar) | معلمات Codabar. |
| [getCodablock()](#getcodablock) | معلمات Codablock. |
| [getCode16K()](#getcode16k) | معلمات Code16K. |
| [getCode128()](#getcode128) | معلمات Code128. |
| [getCodeTextParameters()](#getcodetextparameters) | معلمات Codetext. |
| [getCoupon()](#getcoupon) | معلمات القسيمة. تُستخدم لـ UpcaGs1DatabarCoupon و UpcaGs1Code128Coupon. |
| [getDataBar()](#getdatabar) | معلمات Databar. |
| [getDataMatrix()](#getdatamatrix) | معلمات DataMatrix. |
| [getDotCode()](#getdotcode) | معلمات DotCode. |
| [getEnableEscape()](#getenableescape) | يشير إلى ما إذا كان يفسر الحرف "\" كحرف هروب في خاصية CodeText. يستخدم لـ Pdf417 و DataMatrix و C |
| [getFilledBars()](#getfilledbars) | يحصل على قيمة تشير إلى ما إذا كانت الأشرطة مملوءة. فقط لباركودات 1D. القيمة الافتراضية: true. |
| [getGS1CompositeBar()](#getgs1compositebar) | معلمات GS1 Composite Bar. يوضح هذا المثال كيفية إنشاء وحفظ صورة GS1 Composite Bar. لاحظ أن نص الكود 1D |
| [getHanXin()](#gethanxin) | معلمات HanXin. |
| [getITF()](#getitf) | معلمات ITF. |
| [getMaxiCode()](#getmaxicode) | معلمات MaxiCode. |
| [getPadding()](#getpadding) | هوامش الباركود. القيمة الافتراضية: 5pt 5pt 5pt 5pt. |
| [getPatchCode()](#getpatchcode) | معلمات PatchCode. |
| [getPdf417()](#getpdf417) | معلمات PDF417. |
| [getPostal()](#getpostal) | معلمات البريد. تُستخدم لـ Postnet وPlanet. |
| [getQR()](#getqr) | معلمات QR. |
| [getSupplement()](#getsupplement) | معلمات المكمل. تُستخدم لـ Interleaved2of5 وStandard2of5 وEAN13 وEAN8 وUPCA وUPCE وISBN وISSN وISMN. |
| [getWideNarrowRatio()](#getwidenarrowratio) | نسبة الشرائط العريضة إلى الشرائط الضيقة. القيمة الافتراضية: 3، أي أن الشرائط العريضة أوسع بثلاث مرات من الضيقة. يستخدم لـ ITF، |
| [getXDimension()](#getxdimension) | x‑dimension هو أصغر عرض لوحدة أشرطة أو فراغات BarCode. زيادة هذا سيزيد عرض الباركود بالكامل |
| [isChecksumEnabled()](#ischecksumenabled) | تمكين التحقق أثناء إنشاء باركودات 1D. يُعامل الافتراضي على أنه نعم للرموز التي يجب أن تحتوي على التحقق، كـ N |
| [setBarColor(value)](#setbarcolor) | لون الشرائط. |
| [setBarHeight()](#setbarheight) | ارتفاع أشرطة الباركود أحادي الأبعاد بوحدة القيمة. يتم تجاهله إذا تم تعيين خاصية AutoSizeMode إلى AutoSizeMode.NEAREST أو AutoSizeMo |
| [setBarWidthReduction()](#setbarwidthreduction) | يضبط قيمة تقليل الأشرطة المستخدمة لتعويض انتشار الحبر أثناء الطباعة. |
| [setChecksumAlwaysShow()](#setchecksumalwaysshow) | اعرض دائمًا رقم التحقق في النص القابل للقراءة البشرية لباركودات Code128 و GS1Code128. |
| [setChecksumEnabled()](#setchecksumenabled) | تمكين التحقق أثناء إنشاء باركودات 1D. يُعامل الافتراضي على أنه نعم للرموز التي يجب أن تحتوي على التحقق، كـ N |
| [setEnableEscape()](#setenableescape) | يشير إلى ما إذا كان يفسر الحرف "\" كحرف هروب في خاصية CodeText. يستخدم لـ Pdf417 و DataMatrix و C |
| [setFilledBars()](#setfilledbars) | يضبط قيمة تشير إلى ما إذا كانت الأشرطة مملوءة. فقط لباركودات 1D. القيمة الافتراضية: true. |
| [setGS1CompositeBar()](#setgs1compositebar) | معلمات GS1 Composite Bar. يوضح هذا المثال كيفية إنشاء وحفظ صورة GS1 Composite Bar. لاحظ أن نص الكود 1D |
| [setPadding()](#setpadding) | هوامش الباركود. القيمة الافتراضية: 5pt 5pt 5pt 5pt. |
| [setWideNarrowRatio()](#setwidenarrowratio) | نسبة الشرائط العريضة إلى الشرائط الضيقة. القيمة الافتراضية: 3، أي أن الشرائط العريضة أوسع بثلاث مرات من الضيقة. يستخدم لـ ITF، P |
| [setXDimension()](#setxdimension) | x‑dimension هو أصغر عرض لوحدة أشرطة أو فراغات BarCode. زيادة هذا سيزيد عرض الباركود بالكامل |

### getAustralianPost() {#getaustralianpost}

معلمات الباركود AustralianPost.

### getAztec() {#getaztec}

معلمات Aztec.

### getBarColor() {#getbarcolor}

لون الشرائط.

**Returns:** value of Bar color Default value: #000000

### getBarHeight() {#getbarheight}

ارتفاع أشرطة باركودات 1D بوحدة القيمة. يتم تجاهله إذا تم تعيين خاصية AutoSizeMode إلى AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### getBarWidthReduction() {#getbarwidthreduction}

احصل على قيمة تقليل الأشرطة المستخدمة لتعويض انتشار الحبر أثناء الطباعة.

**Returns:** Unit value of BarWidthReduction

### getChecksumAlwaysShow() {#getchecksumalwaysshow}

اعرض دائمًا رقم التحقق في النص القابل للقراءة البشرية لباركودات Code128 و GS1Code128.

### getCodabar() {#getcodabar}

معلمات Codabar.

### getCodablock() {#getcodablock}

معلمات Codablock.

### getCode16K() {#getcode16k}

معلمات Code16K.

### getCode128() {#getcode128}

معلمات Code128.

### getCodeTextParameters() {#getcodetextparameters}

معلمات Codetext.

### getCoupon() {#getcoupon}

معلمات القسيمة. تُستخدم لـ UpcaGs1DatabarCoupon و UpcaGs1Code128Coupon.

### getDataBar() {#getdatabar}

معلمات Databar.

### getDataMatrix() {#getdatamatrix}

معلمات DataMatrix.

### getDotCode() {#getdotcode}

معلمات DotCode.

### getEnableEscape() {#getenableescape}

يشير إلى ما إذا كان يفسر الحرف "\" كحرف هروب في خاصية CodeText. يستخدم لـ Pdf417 و DataMatrix و Code128 فقط. إذا كان EnableEscape صحيحًا، سيتم تفسير "\" كحرف هروب خاص. وإلا، سيعمل "\" كحروف عادية. يدعم Aspose.BarCode إدخال رمز ASCII عشري واختصار لأحرف التحكم في ASCII. على سبيل المثال، \\013 و \\\\CR يمثلان CR.

### getFilledBars() {#getfilledbars}

يحصل على قيمة تشير إلى ما إذا كانت الأشرطة مملوءة. فقط لباركودات 1D. القيمة الافتراضية: true.

### getGS1CompositeBar() {#getgs1compositebar}

معلمات GS1 Composite Bar. يوضح هذا المثال كيفية إنشاء وحفظ صورة GS1 Composite Bar. لاحظ أن نص الكود 1D ونص الكود 2D مفصولان بالرمز '/'

**Returns:** GS1CompositeBarParameters GS1 Composite Bar parameters.

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);
///
// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);
///
generator.save("test.png", BarcodeImageFormat.PNG);
```

### getHanXin() {#gethanxin}

معلمات HanXin.

### getITF() {#getitf}

معلمات ITF.

### getMaxiCode() {#getmaxicode}

معلمات MaxiCode.

### getPadding() {#getpadding}

هوامش الباركود. القيمة الافتراضية: 5pt 5pt 5pt 5pt.

### getPatchCode() {#getpatchcode}

معلمات PatchCode.

### getPdf417() {#getpdf417}

معلمات PDF417.

### getPostal() {#getpostal}

معلمات البريد. تُستخدم لـ Postnet وPlanet.

### getQR() {#getqr}

معلمات QR.

### getSupplement() {#getsupplement}

معلمات المكمل. تُستخدم لـ Interleaved2of5 وStandard2of5 وEAN13 وEAN8 وUPCA وUPCE وISBN وISSN وISMN.

### getWideNarrowRatio() {#getwidenarrowratio}

نسبة الشرائط العريضة إلى الشرائط الضيقة. القيمة الافتراضية: 3، أي أن الشرائط العريضة أوسع بثلاث مرات من الضيقة. يستخدم لـ ITF، PZN، PharmaCode، Standard2of5، Interleaved2of5، Matrix2of5، ItalianPost25، IATA2of5، VIN، DeutschePost، OPC، Code32، DataLogic2of5، PatchCode، Code39Extended، Code39Standard. قيمة المعامل WideNarrowRatio أقل من أو تساوي 0.

### getXDimension() {#getxdimension}

x‑dimension هو أصغر عرض لوحدة أشرطة أو فراغات BarCode. زيادة هذا سيزيد عرض صورة الباركود بالكامل. يتم تجاهله إذا تم تعيين خاصية AutoSizeMode إلى AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION.

### isChecksumEnabled() {#ischecksumenabled}

تمكين التحقق من المجموع الاختباري أثناء إنشاء الباركود أحادي الأبعاد. يُعامل الافتراضي كـ نعم للرموز التي يجب أن تحتوي على التحقق من المجموع الاختباري، وكـ لا حيث يكون التحقق من المجموع الاختباري ممكنًا فقط. التحقق من المجموع الاختباري ممكن: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. التحقق من المجموع الاختباري يُستخدم دائمًا: باقي الرموز

### setBarColor(value) {#setbarcolor}

لون الشرائط.

| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | String | لللون Bar القيمة الافتراضية: #000000. |

### setBarHeight() {#setbarheight}

ارتفاع أشرطة باركودات 1D بوحدة القيمة. يتم تجاهله إذا تم تعيين خاصية AutoSizeMode إلى AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### setBarWidthReduction() {#setbarwidthreduction}

يضبط قيمة تقليل الأشرطة المستخدمة لتعويض انتشار الحبر أثناء الطباعة.

### setChecksumAlwaysShow() {#setchecksumalwaysshow}

اعرض دائمًا رقم التحقق في النص القابل للقراءة البشرية لباركودات Code128 و GS1Code128.

### setChecksumEnabled() {#setchecksumenabled}

تمكين التحقق من المجموع الاختباري أثناء إنشاء الباركود أحادي الأبعاد. يُعامل الافتراضي كـ نعم للرموز التي يجب أن تحتوي على التحقق من المجموع الاختباري، وكـ لا حيث يكون التحقق من المجموع الاختباري ممكنًا فقط. التحقق من المجموع الاختباري ممكن: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. التحقق من المجموع الاختباري يُستخدم دائمًا: باقي الرموز

### setEnableEscape() {#setenableescape}

يشير إلى ما إذا كان يفسر الحرف "\" كحرف هروب في خاصية CodeText. يُستخدم لـ Pdf417, DataMatrix, Code128 فقط. إذا كان EnableEscape صحيحًا، سيتم تفسير "\" كحرف هروب خاص. وإلا، سيعمل "\" كحروف عادية. يدعم Aspose.BarCode رمز ASCII العشري والاختصار لأحرف التحكم في ASCII. على سبيل المثال، \013 و \\CR يمثلان CR.

### setFilledBars() {#setfilledbars}

يضبط قيمة تشير إلى ما إذا كانت الأشرطة مملوءة. فقط لباركودات 1D. القيمة الافتراضية: true.

### setGS1CompositeBar() {#setgs1compositebar}

معلمات GS1 Composite Bar. يوضح هذا المثال كيفية إنشاء وحفظ صورة GS1 Composite Bar. لاحظ أن نص الكود 1D ونص الكود 2D مفصولان بالرمز '/'

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);

// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);

generator.save("test.png", BarcodeImageFormat.PNG);
```

### setPadding() {#setpadding}

هوامش الباركود. القيمة الافتراضية: 5pt 5pt 5pt 5pt.

### setWideNarrowRatio() {#setwidenarrowratio}

نسبة الأشرطة العريضة إلى الأشرطة الضيقة. القيمة الافتراضية: 3، أي أن الأشرطة العريضة أوسع بثلاث مرات من الأشرطة الضيقة. يُستخدم لـ ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. قيمة المعامل WideNarrowRatio أقل من أو تساوي 0.

### setXDimension() {#setxdimension}

x‑dimension هو أصغر عرض لوحدة أشرطة أو فراغات BarCode. زيادة هذا سيزيد عرض صورة الباركود بالكامل. يتم تجاهله إذا تم تعيين خاصية AutoSizeMode إلى AutoSizeMode.NEAREST أو AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException
