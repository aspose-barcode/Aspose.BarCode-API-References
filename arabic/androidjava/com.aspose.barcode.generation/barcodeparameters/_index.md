---
title: BarcodeParameters
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: معلمات توليد الباركود.
type: docs
weight: 14
url: /ar/androidjava/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

معلمات توليد الباركود.
## Methods

| Method | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) |  |
| [getAustralianPost()](#getAustralianPost--) | معلمات باركود AustralianPost. |
| [getAztec()](#getAztec--) | معلمات Aztec. |
| [getBarColor()](#getBarColor--) | لون الأشرطة. |
| [getBarHeight()](#getBarHeight--) | ارتفاع أشرطة الباركودات أحادية الأبعاد في قيمة [Unit](../../com.aspose.barcode.generation/unit). |
| [getBarWidthReduction()](#getBarWidthReduction--) | احصل على قيمة تقليل الأشرطة المستخدمة لتعويض انتشار الحبر أثناء الطباعة. |
| [getBarcodeType()](#getBarcodeType--) |  |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes. |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | معلمات Codabar. |
| [getCodablock()](#getCodablock--) | معلمات Codablock. |
| [getCode128()](#getCode128--) | معلمات Code128. |
| [getCode16K()](#getCode16K--) | معلمات Code16K. |
| [getCodeText()](#getCodeText--) |  |
| [getCodeTextParameters()](#getCodeTextParameters--) | معلمات Codetext. |
| [getComplexBarcode()](#getComplexBarcode--) |  |
| [getCoupon()](#getCoupon--) | معلمات القسيمة. |
| [getDataBar()](#getDataBar--) | معلمات Databar. |
| [getDataMatrix()](#getDataMatrix--) | معلمات DataMatrix. |
| [getDotCode()](#getDotCode--) | معلمات DotCode. |
| [getEnableEscape()](#getEnableEscape--) | Indicates whether explains the character "\\" as an escape character in CodeText property. |
| [getFilledBars()](#getFilledBars--) | Gets a value indicating whether bars filled. |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | GS1 Composite Bar parameters. |
| [getHanXin()](#getHanXin--) | HanXin parameters. |
| [getITF()](#getITF--) | معلمات ITF. |
| [getMaxiCode()](#getMaxiCode--) | معلمات MaxiCode. |
| [getPadding()](#getPadding--) | Barcode paddings. |
| [getPatchCode()](#getPatchCode--) | معلمات PatchCode. |
| [getPdf417()](#getPdf417--) | معلمات PDF417. |
| [getPostal()](#getPostal--) | معلمات البريد. |
| [getQR()](#getQR--) | QR, MicroQR and RectMicroQR parameters. |
| [getSupplement()](#getSupplement--) | معلمات الإضافة. |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | Only for 1D barcodes. |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | Wide bars to Narrow bars ratio. |
| [getXDimension()](#getXDimension--) | x-dimension is the smallest width of the unit of BarCode bars or spaces. |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(int value)](#setBarColor-int-) | لون الأشرطة. |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | ارتفاع أشرطة الباركودات أحادية الأبعاد في قيمة [Unit](../../com.aspose.barcode.generation/unit). |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | Sets bars reduction value that is used to compensate ink spread while printing. |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes. |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setCodeText(String value)](#setCodeText-java.lang.String-) |  |
| [setEnableEscape(boolean value)](#setEnableEscape-boolean-) | Indicates whether explains the character "\\" as an escape character in CodeText property. |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | Sets a value indicating whether bars filled. |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | GS1 Composite Bar parameters. |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | Only for 1D barcodes. |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | Wide bars to Narrow bars ratio. |
| [setXDimension(Unit value)](#setXDimension-com.aspose.barcode.generation.Unit-) | x-dimension is the smallest width of the unit of BarCode bars or spaces. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```




**Returns:**
float
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
public final int getBarColor()
```


Bars color. Default value: Color.Black.

**Returns:**
int
### getBarHeight() {#getBarHeight--}
```
public final Unit getBarHeight()
```


Height of 1D barcodes' bars in [Unit](../../com.aspose.barcode.generation/unit) value. Ignored if  BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) property is set to AutoSizeMode.Nearest or AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


Get bars reduction value that is used to compensate ink spread while printing. Default value: 0

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - bars reduction value that is used to compensate ink spread while printing.
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```




**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
### getChecksumAlwaysShow() {#getChecksumAlwaysShow--}
```
public final boolean getChecksumAlwaysShow()
```


Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes.

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
### getCodeText() {#getCodeText--}
```
public final String getCodeText()
```




**Returns:**
java.lang.String
### getCodeTextParameters() {#getCodeTextParameters--}
```
public final CodetextParameters getCodeTextParameters()
```


معلمات Codetext.

**Returns:**
[CodetextParameters](../../com.aspose.barcode.generation/codetextparameters)
### getComplexBarcode() {#getComplexBarcode--}
```
public final ComplexBarcode getComplexBarcode()
```




**Returns:**
[ComplexBarcode](../../com.aspose.barcode.generation/complexbarcode)
### getCoupon() {#getCoupon--}
```
public final CouponParameters getCoupon()
```


Coupon parameters. Used for UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

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
### getEnableEscape() {#getEnableEscape--}
```
public final boolean getEnableEscape()
```


Indicates whether explains the character "\\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, Code128 only If the EnableEscape is true, "\\" will be explained as a special escape character. Otherwise, "\\" acts as normal characters.

Aspose.BarCode supports inputing decimal ascii code and mnemonic for ASCII control-code characters. For example, \\013 and \\\\CR stands for CR.

**Returns:**
boolean
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


Gets a value indicating whether bars filled. Only for 1D barcodes. Default value: true.

**Returns:**
boolean - a value indicating whether bars filled.
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


GS1 Composite Bar parameters.

This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D codetext are separated by symbol '|'

```

 [C#]
   var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 	  using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
 	  {
       generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
       generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
       // Aspect ratio of 2D component
       generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
       // X-Dimension of 1D and 2D components
       generator.Parameters.Barcode.XDimension.Pixels = 3;
       // Height of 1D component
       generator.Parameters.Barcode.BarHeight.Pixels = 100;
       generator.Save("test.png");
   }
 	
```

**Returns:**
[GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters)
### getHanXin() {#getHanXin--}
```
public final HanXinParameters getHanXin()
```


HanXin parameters.

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


Barcode paddings. Default value: 5pt 5pt 5pt 5pt.

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


معلمات البريد. تُستخدم لـ Postnet، Planet.

**Returns:**
[PostalParameters](../../com.aspose.barcode.generation/postalparameters)
### getQR() {#getQR--}
```
public final QrParameters getQR()
```


QR, MicroQR and RectMicroQR parameters.

**Returns:**
[QrParameters](../../com.aspose.barcode.generation/qrparameters)
### getSupplement() {#getSupplement--}
```
public final SupplementParameters getSupplement()
```


Supplement parameters. Used for Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

**Returns:**
[SupplementParameters](../../com.aspose.barcode.generation/supplementparameters)
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public final boolean getThrowExceptionWhenCodeTextIncorrect()
```


Only for 1D barcodes. If codetext is incorrect and value set to true - exception will be thrown. Otherwise codetext will be corrected to match barcode's specification. Exception always will be thrown for: Databar symbology if codetext is incorrect. Exception always will not be thrown for: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 symbology if codetext is incorrect.

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public final float getWideNarrowRatio()
```


Wide bars to Narrow bars ratio. Default value: 3, that is, wide bars are 3 times as wide as narrow bars. Used for ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public final Unit getXDimension()
```


البُعد-x هو أصغر عرض لوحدة خطوط أو فراغات الباركود. زيادة هذا سيزيد عرض صورة الباركود بالكامل. يتم تجاهله إذا تم تعيين خاصية BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) إلى AutoSizeMode.Nearest أو AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isChecksumEnabled() {#isChecksumEnabled--}
```
public final EnableChecksum isChecksumEnabled()
```


تمكين التحقق من المجموع الاختباري أثناء إنشاء باركودات 1D.

يُعامل الافتراضي كـ نعم للرموز التي يجب أن تحتوي على المجموع الاختباري، وكـ لا حيث يكون المجموع الاختباري ممكنًا فقط.

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




### setBarColor(int value) {#setBarColor-int-}
```
public final void setBarColor(int value)
```


Bars color. Default value: Color.Black.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


Height of 1D barcodes' bars in [Unit](../../com.aspose.barcode.generation/unit) value. Ignored if  BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) property is set to AutoSizeMode.Nearest or AutoSizeMode.Interpolation.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


يضبط قيمة تقليل الخطوط المستخدمة لتعويض انتشار الحبر أثناء الطباعة. القيمة الافتراضية: 0

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | قيمة تقليل الخطوط المستخدمة لتعويض انتشار الحبر أثناء الطباعة. |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


تمكين التحقق من المجموع الاختباري أثناء إنشاء باركودات 1D.

يُعامل الافتراضي كـ نعم للرموز التي يجب أن تحتوي على المجموع الاختباري، وكـ لا حيث يكون المجموع الاختباري ممكنًا فقط.

المجموع الاختباري ممكن: Code39 Standard/Extended، Standard2of5، Interleaved2of5، Matrix2of5، ItalianPost25، DeutschePostIdentcode، DeutschePostLeitcode، VIN، Codabar

المجموع الاختباري يُستخدم دائمًا: باقي الرموز

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public final void setCodeText(String value)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### setEnableEscape(boolean value) {#setEnableEscape-boolean-}
```
public final void setEnableEscape(boolean value)
```


Indicates whether explains the character "\\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, Code128 only If the EnableEscape is true, "\\" will be explained as a special escape character. Otherwise, "\\" acts as normal characters.

Aspose.BarCode supports inputing decimal ascii code and mnemonic for ASCII control-code characters. For example, \\013 and \\\\CR stands for CR.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


يضبط قيمة تشير إلى ما إذا كانت الخطوط مملوءة. يقتصر على باركودات 1D. القيمة الافتراضية: true.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | boolean | قيمة تشير إلى ما إذا كانت الخطوط مملوءة. |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


GS1 Composite Bar parameters.

This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D codetext are separated by symbol '|'

```

 [C#]
   var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 	  using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
 	  {
       generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
       generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
       // Aspect ratio of 2D component
       generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
       // X-Dimension of 1D and 2D components
       generator.Parameters.Barcode.XDimension.Pixels = 3;
       // Height of 1D component
       generator.Parameters.Barcode.BarHeight.Pixels = 100;
       generator.Save("test.png");
   }
 	
```

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


Only for 1D barcodes. If codetext is incorrect and value set to true - exception will be thrown. Otherwise codetext will be corrected to match barcode's specification. Exception always will be thrown for: Databar symbology if codetext is incorrect. Exception always will not be thrown for: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 symbology if codetext is incorrect.

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


Wide bars to Narrow bars ratio. Default value: 3, that is, wide bars are 3 times as wide as narrow bars. Used for ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| القيمة | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


البُعد-x هو أصغر عرض لوحدة خطوط أو فراغات الباركود. زيادة هذا سيزيد عرض صورة الباركود بالكامل. يتم تجاهله إذا تم تعيين خاصية BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) إلى AutoSizeMode.Nearest أو AutoSizeMode.Interpolation.

**Parameters:**
| Parameter | Type | الوصف |
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
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

