---
title: BarcodeParameters
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 条形码生成参数。
type: docs
weight: 14
url: /zh/androidjava/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

条形码生成参数。
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) |  |
| [getAustralianPost()](#getAustralianPost--) | AustralianPost 条码参数。 |
| [getAztec()](#getAztec--) | Aztec 参数。 |
| [getBarColor()](#getBarColor--) | 条形颜色。 |
| [getBarHeight()](#getBarHeight--) | 1D 条形码条的高度，以 [Unit](../../com.aspose.barcode.generation/unit) 为单位。 |
| [getBarWidthReduction()](#getBarWidthReduction--) | 获取用于在打印时补偿墨水扩散的条形减小值。 |
| [getBarcodeType()](#getBarcodeType--) |  |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | 始终在 Code128 和 GS1Code128 条形码的人类可读文本中显示校验位。 |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Codabar 参数。 |
| [getCodablock()](#getCodablock--) | Codablock 参数。 |
| [getCode128()](#getCode128--) | Code128 参数。 |
| [getCode16K()](#getCode16K--) | Code16K 参数。 |
| [getCodeText()](#getCodeText--) |  |
| [getCodeTextParameters()](#getCodeTextParameters--) | 编码文本参数。 |
| [getComplexBarcode()](#getComplexBarcode--) |  |
| [getCoupon()](#getCoupon--) | 优惠券参数。 |
| [getDataBar()](#getDataBar--) | Databar 参数。 |
| [getDataMatrix()](#getDataMatrix--) | DataMatrix 参数。 |
| [getDotCode()](#getDotCode--) | DotCode 参数。 |
| [getEnableEscape()](#getEnableEscape--) | 指示是否将字符 "\\" 解释为 CodeText 属性中的转义字符。 |
| [getFilledBars()](#getFilledBars--) | 获取指示条形是否填充的值。 |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | GS1 复合条码参数。 |
| [getHanXin()](#getHanXin--) | 汉信参数。 |
| [getITF()](#getITF--) | ITF 参数。 |
| [getMaxiCode()](#getMaxiCode--) | MaxiCode 参数。 |
| [getPadding()](#getPadding--) | 条形码填充。 |
| [getPatchCode()](#getPatchCode--) | PatchCode 参数。 |
| [getPdf417()](#getPdf417--) | PDF417 参数。 |
| [getPostal()](#getPostal--) | 邮政参数。 |
| [getQR()](#getQR--) | QR、MicroQR 和 RectMicroQR 参数。 |
| [getSupplement()](#getSupplement--) | 补充参数。 |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | 仅适用于一维条码。 |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | 宽条与窄条的比例。 |
| [getXDimension()](#getXDimension--) | x 维度是条形码条或空白单元的最小宽度。 |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(int value)](#setBarColor-int-) | 条形颜色。 |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | 1D 条形码条的高度，以 [Unit](../../com.aspose.barcode.generation/unit) 为单位。 |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | 设置用于在打印时补偿墨水扩散的条形减小值。 |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | 始终在 Code128 和 GS1Code128 条形码的人类可读文本中显示校验位。 |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setCodeText(String value)](#setCodeText-java.lang.String-) |  |
| [setEnableEscape(boolean value)](#setEnableEscape-boolean-) | 指示是否将字符 "\\" 解释为 CodeText 属性中的转义字符。 |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | 设置指示条形是否填充的值。 |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | GS1 复合条码参数。 |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | 仅适用于一维条码。 |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | 宽条与窄条的比例。 |
| [setXDimension(Unit value)](#setXDimension-com.aspose.barcode.generation.Unit-) | x 维度是条形码条或空白单元的最小宽度。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
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


AustralianPost 条码参数。

**Returns:**
[AustralianPostParameters](../../com.aspose.barcode.generation/australianpostparameters)
### getAztec() {#getAztec--}
```
public final AztecParameters getAztec()
```


Aztec 参数。

**Returns:**
[AztecParameters](../../com.aspose.barcode.generation/aztecparameters)
### getBarColor() {#getBarColor--}
```
public final int getBarColor()
```


条形颜色。默认值：Color.Black。

**Returns:**
int
### getBarHeight() {#getBarHeight--}
```
public final Unit getBarHeight()
```


1D 条码条的高度，以 [Unit](../../com.aspose.barcode.generation/unit) 为单位。如果 BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) 属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation，则此设置被忽略。

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


获取用于在打印时补偿墨水扩散的条形减小值。默认值：0

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


始终在 Code128 和 GS1Code128 条形码的人类可读文本中显示校验位。

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


Codabar 参数。

**Returns:**
[CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)
### getCodablock() {#getCodablock--}
```
public final CodablockParameters getCodablock()
```


Codablock 参数。

**Returns:**
[CodablockParameters](../../com.aspose.barcode.generation/codablockparameters)
### getCode128() {#getCode128--}
```
public final Code128Parameters getCode128()
```


Code128 参数。

**Returns:**
[Code128Parameters](../../com.aspose.barcode.generation/code128parameters)
### getCode16K() {#getCode16K--}
```
public final Code16KParameters getCode16K()
```


Code16K 参数。

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


编码文本参数。

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


优惠券参数。用于 UpcaGs1DatabarCoupon、UpcaGs1Code128Coupon。

**Returns:**
[CouponParameters](../../com.aspose.barcode.generation/couponparameters)
### getDataBar() {#getDataBar--}
```
public final DataBarParameters getDataBar()
```


Databar 参数。

**Returns:**
[DataBarParameters](../../com.aspose.barcode.generation/databarparameters)
### getDataMatrix() {#getDataMatrix--}
```
public final DataMatrixParameters getDataMatrix()
```


DataMatrix 参数。

**Returns:**
[DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)
### getDotCode() {#getDotCode--}
```
public final DotCodeParameters getDotCode()
```


DotCode 参数。

**Returns:**
[DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters)
### getEnableEscape() {#getEnableEscape--}
```
public final boolean getEnableEscape()
```


指示是否将字符 "\\" 解释为 CodeText 属性中的转义字符。仅用于 Pdf417、DataMatrix、Code128。如果 EnableEscape 为 true，"\\" 将被解释为特殊转义字符。否则，"\\" 将作为普通字符。

Aspose.BarCode 支持输入十进制 ASCII 码和 ASCII 控制码字符的助记符。例如，\\013 和 \\\\CR 代表 CR。

**Returns:**
boolean
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


获取指示条形是否填充的值。仅适用于一维条码。默认值：true。

**Returns:**
boolean - 指示条形是否填充的值。
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


GS1 复合条码参数。

此示例展示了如何创建并保存 GS1 复合条码图像。请注意，1D 编码文本和 2D 编码文本之间使用符号 '|' 分隔。

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


汉信参数。

**Returns:**
[HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)
### getITF() {#getITF--}
```
public final ITFParameters getITF()
```


ITF 参数。

**Returns:**
[ITFParameters](../../com.aspose.barcode.generation/itfparameters)
### getMaxiCode() {#getMaxiCode--}
```
public final MaxiCodeParameters getMaxiCode()
```


MaxiCode 参数。

**Returns:**
[MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)
### getPadding() {#getPadding--}
```
public final Padding getPadding()
```


条形码填充。默认值：5pt 5pt 5pt 5pt。

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getPatchCode() {#getPatchCode--}
```
public final PatchCodeParameters getPatchCode()
```


PatchCode 参数。

**Returns:**
[PatchCodeParameters](../../com.aspose.barcode.generation/patchcodeparameters)
### getPdf417() {#getPdf417--}
```
public final Pdf417Parameters getPdf417()
```


PDF417 参数。

**Returns:**
[Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)
### getPostal() {#getPostal--}
```
public final PostalParameters getPostal()
```


邮政参数。适用于 Postnet、Planet。

**Returns:**
[PostalParameters](../../com.aspose.barcode.generation/postalparameters)
### getQR() {#getQR--}
```
public final QrParameters getQR()
```


QR、MicroQR 和 RectMicroQR 参数。

**Returns:**
[QrParameters](../../com.aspose.barcode.generation/qrparameters)
### getSupplement() {#getSupplement--}
```
public final SupplementParameters getSupplement()
```


补充参数。用于 Interleaved2of5、Standard2of5、EAN13、EAN8、UPCA、UPCE、ISBN、ISSN、ISMN。

**Returns:**
[SupplementParameters](../../com.aspose.barcode.generation/supplementparameters)
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public final boolean getThrowExceptionWhenCodeTextIncorrect()
```


仅适用于一维条码。如果编码文本不正确且值设为 true，则会抛出异常。否则，编码文本将被纠正以符合条码规范。以下情况始终会抛出异常：Databar 符号如果编码文本不正确。以下情况始终不会抛出异常：AustraliaPost、SingapurePost、Code39FullASCII、Code93、Code16K、Code128 符号如果编码文本不正确。

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public final float getWideNarrowRatio()
```


宽条与窄条的比例。默认值：3，即宽条是窄条的 3 倍。用于 ITF、PZN、PharmaCode、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、IATA2of5、VIN、DeutschePost、OPC、Code32、DataLogic2of5、PatchCode、Code39、Code39FullASCII。

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public final Unit getXDimension()
```


x-dimension 是条形码条或空格单元的最小宽度。增加此值将增加整个条形码图像的宽度。如果 BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) 属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation，则会被忽略。

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


在生成 1D 条码时启用校验和。

默认情况下，对于必须包含校验和的符号视为 Yes，而在仅可能包含校验和的情况下视为 No。

可以使用校验和的符号包括：Code39 Standard/Extended、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN、Codabar

始终使用校验和的符号：其余符号

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


条形颜色。默认值：Color.Black。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


1D 条码条的高度，以 [Unit](../../com.aspose.barcode.generation/unit) 为单位。如果 BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) 属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation，则此设置被忽略。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


设置用于在打印时补偿油墨扩散的条宽缩减值。默认值：0

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | 用于在打印时补偿油墨扩散的条宽缩减值。 |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


始终在 Code128 和 GS1Code128 条形码的人类可读文本中显示校验位。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


在生成 1D 条码时启用校验和。

默认情况下，对于必须包含校验和的符号视为 Yes，而在仅可能包含校验和的情况下视为 No。

可以使用校验和的符号包括：Code39 Standard/Extended、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN、Codabar

始终使用校验和的符号：其余符号

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public final void setCodeText(String value)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setEnableEscape(boolean value) {#setEnableEscape-boolean-}
```
public final void setEnableEscape(boolean value)
```


指示是否将字符 "\\" 解释为 CodeText 属性中的转义字符。仅用于 Pdf417、DataMatrix、Code128。如果 EnableEscape 为 true，"\\" 将被解释为特殊转义字符。否则，"\\" 将作为普通字符。

Aspose.BarCode 支持输入十进制 ASCII 码和 ASCII 控制码字符的助记符。例如，\\013 和 \\\\CR 代表 CR。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


设置一个指示条是否填充的值。仅适用于 1D 条码。默认值：true。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean | 指示条是否填充的值。 |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


GS1 复合条码参数。

此示例展示了如何创建并保存 GS1 复合条码图像。请注意，1D 编码文本和 2D 编码文本之间使用符号 '|' 分隔。

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


仅适用于一维条码。如果编码文本不正确且值设为 true，则会抛出异常。否则，编码文本将被纠正以符合条码规范。以下情况始终会抛出异常：Databar 符号如果编码文本不正确。以下情况始终不会抛出异常：AustraliaPost、SingapurePost、Code39FullASCII、Code93、Code16K、Code128 符号如果编码文本不正确。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


宽条与窄条的比例。默认值：3，即宽条是窄条的 3 倍。用于 ITF、PZN、PharmaCode、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、IATA2of5、VIN、DeutschePost、OPC、Code32、DataLogic2of5、PatchCode、Code39、Code39FullASCII。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


x-dimension 是条形码条或空格单元的最小宽度。增加此值将增加整个条形码图像的宽度。如果 BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) 属性设置为 AutoSizeMode.Nearest 或 AutoSizeMode.Interpolation，则会被忽略。

**Parameters:**
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

