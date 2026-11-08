---
title: "BarcodeParameters"
second_title: "مرجع Aspose.BarCode لـ Java API"
description: "معلمات توليد الباركود."
type: docs
weight: 14
url: /ar/java/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

معلمات توليد الباركود.
## الدوال

| دالة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAustralianPost()](#getAustralianPost--) | معلمات باركود AustralianPost. |
| [getAztec()](#getAztec--) | معلمات Aztec. |
| [getBarColor()](#getBarColor--) | لون الأشرطة. |
| [getBarHeight()](#getBarHeight--) | ارتفاع أشرطة الباركود أحادي الأبعاد في قيمة [Unit](../../com.aspose.barcode.generation/unit). |
| [getBarWidthReduction()](#getBarWidthReduction--) | احصل على قيمة تقليل الأشرطة المستخدمة لتعويض انتشار الحبر أثناء الطباعة. |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | اعرض دائمًا رقم التحقق في النص القابل للقراءة للإنسان لباركودات Code128 وGS1Code128. |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | معلمات Codabar. |
| [getCodablock()](#getCodablock--) | معلمات Codablock. |
| [getCode128()](#getCode128--) | معلمات Code128. |
| [getCode16K()](#getCode16K--) | معلمات Code16K. |
| [getCodeTextParameters()](#getCodeTextParameters--) | معلمات Codetext. |
| [getCoupon()](#getCoupon--) | معلمات القسيمة. |
| [getDataBar()](#getDataBar--) | معلمات Databar. |
| [getDataMatrix()](#getDataMatrix--) | معلمات DataMatrix. |
| [getDotCode()](#getDotCode--) | معلمات DotCode. |
| [getFilledBars()](#getFilledBars--) | يحصل على قيمة تشير إلى ما إذا كانت الأشرطة مملوءة. |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | معلمات شريط GS1 المركب. |
| [getHanXin()](#getHanXin--) | معلمات HanXin. |
| [getITF()](#getITF--) | معلمات ITF. |
| [getMaxiCode()](#getMaxiCode--) | معلمات MaxiCode. |
| [getPadding()](#getPadding--) | هوامش الباركود. |
| [getPatchCode()](#getPatchCode--) | معلمات PatchCode. |
| [getPdf417()](#getPdf417--) | معلمات PDF417. |
| [getPostal()](#getPostal--) | معلمات البريد. |
| [getQR()](#getQR--) | معلمات QR، MicroQR و RectMicroQR. |
| [getSupplement()](#getSupplement--) | معلمات المكمل. |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | فقط لباركودات أحادية الأبعاد. |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | نسبة الأشرطة العريضة إلى الأشرطة الضيقة. |
| [getXDimension()](#getXDimension--) | البُعد x هو أصغر عرض لوحدة أشرطة أو فراغات الباركود. |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(Color value)](#setBarColor-java.awt.Color-) | لون الأشرطة. |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | ارتفاع أشرطة الباركود أحادي الأبعاد في قيمة [Unit](../../com.aspose.barcode.generation/unit). |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | يضبط قيمة تقليل الأشرطة المستخدمة لتعويض انتشار الحبر أثناء الطباعة. |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | اعرض دائمًا رقم التحقق في النص القابل للقراءة للإنسان لباركودات Code128 وGS1Code128. |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | يضبط قيمة تشير إلى ما إذا كانت الأشرطة مملوءة. |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | معلمات شريط GS1 المركب. |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | فقط لباركودات أحادية الأبعاد. |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | نسبة الأشرطة العريضة إلى الأشرطة الضيقة. |
| [setXDimension(Unit value)](#setXDimension-com.aspose.barcode.generation.Unit-) | البُعد x هو أصغر عرض لوحدة أشرطة أو فراغات الباركود. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAustralianPost() {#getAustralianPost--}
```
public final AustralianPostParameters getAustralianPost()
```


معلمات باركود AustralianPost.

**Returns:**
[AustralianPostParameters](../../com.aspose.barcode.generation/australianpostparameters)
### getAztec() {#getAztec--}
```
public final AztecParameters getAztec()
```


معلمات Aztec.

**Returns:**
[AztecParameters](../../com.aspose.barcode.generation/aztecparameters)
### getBarColor() {#getBarColor--}
```
public final Color getBarColor()
```


لون الأشرطة. القيمة الافتراضية: Color.Black.

**Returns:**
java.awt.Color
### getBarHeight() {#getBarHeight--}
```
public final Unit getBarHeight()
```


ارتفاع أشرطة الباركود أحادي الأبعاد في قيمة [Unit](../../com.aspose.barcode.generation/unit). يتم تجاهله إذا تم تعيين خاصية BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) إلى AutoSizeMode.Nearest أو AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


احصل على قيمة تقليل الأشرطة المستخدمة لتعويض انتشار الحبر أثناء الطباعة. القيمة الافتراضية: 0

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - bars reduction value that is used to compensate ink spread while printing.
### getChecksumAlwaysShow() {#getChecksumAlwaysShow--}
```
public final boolean getChecksumAlwaysShow()
```


اعرض دائمًا رقم التحقق في النص القابل للقراءة للإنسان لباركودات Code128 وGS1Code128.

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodabar() {#getCodabar--}
```
public final CodabarParameters getCodabar()
```


معلمات Codabar.

**Returns:**
[CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)
### getCodablock() {#getCodablock--}
```
public final CodablockParameters getCodablock()
```


معلمات Codablock.

**Returns:**
[CodablockParameters](../../com.aspose.barcode.generation/codablockparameters)
### getCode128() {#getCode128--}
```
public final Code128Parameters getCode128()
```


معلمات Code128.

**Returns:**
[Code128Parameters](../../com.aspose.barcode.generation/code128parameters)
### getCode16K() {#getCode16K--}
```
public final Code16KParameters getCode16K()
```


معلمات Code16K.

**Returns:**
[Code16KParameters](../../com.aspose.barcode.generation/code16kparameters)
### getCodeTextParameters() {#getCodeTextParameters--}
```
public final CodetextParameters getCodeTextParameters()
```


معلمات Codetext.

**Returns:**
[CodetextParameters](../../com.aspose.barcode.generation/codetextparameters)
### getCoupon() {#getCoupon--}
```
public final CouponParameters getCoupon()
```


معلمات القسيمة. تُستخدم لـ UpcaGs1DatabarCoupon، UpcaGs1Code128Coupon.

**Returns:**
[CouponParameters](../../com.aspose.barcode.generation/couponparameters)
### getDataBar() {#getDataBar--}
```
public final DataBarParameters getDataBar()
```


معلمات Databar.

**Returns:**
[DataBarParameters](../../com.aspose.barcode.generation/databarparameters)
### getDataMatrix() {#getDataMatrix--}
```
public final DataMatrixParameters getDataMatrix()
```


معلمات DataMatrix.

**Returns:**
[DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)
### getDotCode() {#getDotCode--}
```
public final DotCodeParameters getDotCode()
```


معلمات DotCode.

**Returns:**
[DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters)
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


يحصل على قيمة تشير إلى ما إذا كانت الأشرطة مملوءة. فقط للباركود أحادي الأبعاد. القيمة الافتراضية: true.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت الأشرطة مملوءة.
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


معلمات شريط GS1 المركب.

يعرض هذا المثال كيفية إنشاء وحفظ صورة شريط GS1 المركب. لاحظ أن نص الكود أحادي الأبعاد ونص الكود ثنائي الأبعاد مفصولان بالرمز '|'.

```

 String codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR,codetext);

 generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
 generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

 // Aspect ratio of 2D component
 generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

 // X-Dimension of 1D and 2D components
 generator.getParameters().getBarcode().getXDimension().setPixels(3);

 // Height of 1D component
 generator.getParameters().getBarcode().getBarHeight().setPixels(100);

 generator.save("test.png");
 
```

**Returns:**
[GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters)
### getHanXin() {#getHanXin--}
```
public final HanXinParameters getHanXin()
```


معلمات HanXin.

**Returns:**
[HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)
### getITF() {#getITF--}
```
public final ITFParameters getITF()
```


معلمات ITF.

**Returns:**
[ITFParameters](../../com.aspose.barcode.generation/itfparameters)
### getMaxiCode() {#getMaxiCode--}
```
public final MaxiCodeParameters getMaxiCode()
```


معلمات MaxiCode.

**Returns:**
[MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)
### getPadding() {#getPadding--}
```
public final Padding getPadding()
```


هوامش الباركود. القيمة الافتراضية: 5pt 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getPatchCode() {#getPatchCode--}
```
public final PatchCodeParameters getPatchCode()
```


معلمات PatchCode.

**Returns:**
[PatchCodeParameters](../../com.aspose.barcode.generation/patchcodeparameters)
### getPdf417() {#getPdf417--}
```
public final Pdf417Parameters getPdf417()
```


معلمات PDF417.

**Returns:**
[Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)
### getPostal() {#getPostal--}
```
public final PostalParameters getPostal()
```


معلمات البريد. تُستخدم لـ Postnet و Planet.

**Returns:**
[PostalParameters](../../com.aspose.barcode.generation/postalparameters)
### getQR() {#getQR--}
```
public final QrParameters getQR()
```


معلمات QR، MicroQR و RectMicroQR.

**Returns:**
[QrParameters](../../com.aspose.barcode.generation/qrparameters)
### getSupplement() {#getSupplement--}
```
public final SupplementParameters getSupplement()
```


معلمات المكمل. تُستخدم لـ Interleaved2of5، Standard2of5، EAN13، EAN8، UPCA، UPCE، ISBN، ISSN، ISMN.

**Returns:**
[SupplementParameters](../../com.aspose.barcode.generation/supplementparameters)
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public final boolean getThrowExceptionWhenCodeTextIncorrect()
```


فقط للباركود أحادي الأبعاد. إذا كان نص الكود غير صحيح وتم تعيين القيمة إلى true - سيتم رمي استثناء. وإلا سيتم تصحيح نص الكود ليتوافق مع مواصفات الباركود. سيُرمى الاستثناء دائمًا في حالة: رموز Databar إذا كان نص الكود غير صحيح. ولن يُرمى الاستثناء أبدًا في حالة: AustraliaPost، SingapurePost، Code39FullASCII، Code93، Code16K، رموز Code128 إذا كان نص الكود غير صحيح.

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public final float getWideNarrowRatio()
```


نسبة الأشرطة العريضة إلى الأشرطة الضيقة. القيمة الافتراضية: 3، أي أن الأشرطة العريضة أوسع بثلاث مرات من الأشرطة الضيقة. تُستخدم لـ ITF، PZN، PharmaCode، Standard2of5، Interleaved2of5، Matrix2of5، ItalianPost25، IATA2of5، VIN، DeutschePost، OPC، Code32، DataLogic2of5، PatchCode، Code39، Code39FullASCII.

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public final Unit getXDimension()
```


البُعد x هو أصغر عرض لوحدة أشرطة أو فراغات الباركود. زيادة هذا سيزيد من عرض صورة الباركود بالكامل. يتم تجاهله إذا تم تعيين خاصية BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) إلى AutoSizeMode.Nearest أو AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isChecksumEnabled() {#isChecksumEnabled--}
```
public final EnableChecksum isChecksumEnabled()
```


تمكين رقم التحقق أثناء إنشاء باركودات أحادية الأبعاد.

يُعامل الافتراضي على أنه نعم للرموز التي يجب أن تحتوي على المجموع الاختباري، وعلى أنه لا حيث يكون المجموع الاختباري ممكنًا فقط.

المجموع الاختباري ممكن: Code39 Standard/Extended، Standard2of5، Interleaved2of5، Matrix2of5، ItalianPost25، DeutschePostIdentcode، DeutschePostLeitcode، VIN، Codabar

المجموع الاختباري يُستخدم دائمًا: باقي الرموز

**Returns:**
[EnableChecksum](../../com.aspose.barcode.generation/enablechecksum)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarColor(Color value) {#setBarColor-java.awt.Color-}
```
public final void setBarColor(Color value)
```


لون الأشرطة. القيمة الافتراضية: Color.Black.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | java.awt.Color |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


ارتفاع أشرطة الباركود أحادي الأبعاد في قيمة [Unit](../../com.aspose.barcode.generation/unit). يتم تجاهله إذا تم تعيين خاصية BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) إلى AutoSizeMode.Nearest أو AutoSizeMode.Interpolation.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


يضبط قيمة تقليل الخطوط التي تُستخدم لتعويض انتشار الحبر أثناء الطباعة. القيمة الافتراضية: 0

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | قيمة تقليل الخطوط التي تُستخدم لتعويض انتشار الحبر أثناء الطباعة. |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


اعرض دائمًا رقم التحقق في النص القابل للقراءة للإنسان لباركودات Code128 وGS1Code128.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


تمكين رقم التحقق أثناء إنشاء باركودات أحادية الأبعاد.

يُعامل الافتراضي على أنه نعم للرموز التي يجب أن تحتوي على المجموع الاختباري، وعلى أنه لا حيث يكون المجموع الاختباري ممكنًا فقط.

المجموع الاختباري ممكن: Code39 Standard/Extended، Standard2of5، Interleaved2of5، Matrix2of5، ItalianPost25، DeutschePostIdentcode، DeutschePostLeitcode، VIN، Codabar

المجموع الاختباري يُستخدم دائمًا: باقي الرموز

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


يضبط قيمة تشير إلى ما إذا كانت الخطوط مملوءة. فقط لأكواد الباركود أحادية البعد. القيمة الافتراضية: true.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كانت الخطوط مملوءة. |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


معلمات شريط GS1 المركب.

يعرض هذا المثال كيفية إنشاء وحفظ صورة شريط GS1 المركب. لاحظ أن نص الكود أحادي الأبعاد ونص الكود ثنائي الأبعاد مفصولان بالرمز '|'.

```

 String codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR,codetext);

 generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
 generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

 // Aspect ratio of 2D component
 generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

 // X-Dimension of 1D and 2D components
 generator.getParameters().getBarcode().getXDimension().setPixels(3);

 // Height of 1D component
 generator.getParameters().getBarcode().getBarHeight().setPixels(100);

 generator.save("test.png");
 
```

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


فقط للباركود أحادي الأبعاد. إذا كان نص الكود غير صحيح وتم تعيين القيمة إلى true - سيتم رمي استثناء. وإلا سيتم تصحيح نص الكود ليتوافق مع مواصفات الباركود. سيُرمى الاستثناء دائمًا في حالة: رموز Databar إذا كان نص الكود غير صحيح. ولن يُرمى الاستثناء أبدًا في حالة: AustraliaPost، SingapurePost، Code39FullASCII، Code93، Code16K، رموز Code128 إذا كان نص الكود غير صحيح.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


نسبة الأشرطة العريضة إلى الأشرطة الضيقة. القيمة الافتراضية: 3، أي أن الأشرطة العريضة أوسع بثلاث مرات من الأشرطة الضيقة. تُستخدم لـ ITF، PZN، PharmaCode، Standard2of5، Interleaved2of5، Matrix2of5، ItalianPost25، IATA2of5، VIN، DeutschePost، OPC، Code32، DataLogic2of5، PatchCode، Code39، Code39FullASCII.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


البُعد x هو أصغر عرض لوحدة أشرطة أو فراغات الباركود. زيادة هذا سيزيد من عرض صورة الباركود بالكامل. يتم تجاهله إذا تم تعيين خاصية BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) إلى AutoSizeMode.Nearest أو AutoSizeMode.Interpolation.

**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

