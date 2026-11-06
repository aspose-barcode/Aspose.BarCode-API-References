---
title: "BarcodeParameters"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "バーコード生成パラメータ。"
type: docs
weight: 14
url: /ja/androidjava/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

バーコード生成パラメータ。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAustralianPost()](#getAustralianPost--) | AustralianPost バーコードパラメータ。 |
| [getAztec()](#getAztec--) | Aztec パラメータ。 |
| [getBarColor()](#getBarColor--) | バーの色。 |
| [getBarHeight()](#getBarHeight--) | 1D バーコードのバーの高さ（[Unit](../../com.aspose.barcode.generation/unit) の値）です。 |
| [getBarWidthReduction()](#getBarWidthReduction--) | 印刷時のインク拡散を補正するために使用されるバーの縮小値を取得します。 |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Code128 および GS1Code128 バーコードの人が読めるテキストにチェックサム桁を常に表示します。 |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Codabar パラメータ。 |
| [getCodablock()](#getCodablock--) | Codablock パラメータ。 |
| [getCode128()](#getCode128--) | Code128 パラメータ。 |
| [getCode16K()](#getCode16K--) | Code16K パラメータ。 |
| [getCodeTextParameters()](#getCodeTextParameters--) | Codetext パラメータ。 |
| [getCoupon()](#getCoupon--) | クーポンパラメータ。 |
| [getDataBar()](#getDataBar--) | Databar パラメータ。 |
| [getDataMatrix()](#getDataMatrix--) | DataMatrix パラメータ。 |
| [getDotCode()](#getDotCode--) | DotCode パラメータ。 |
| [getFilledBars()](#getFilledBars--) | バーが塗りつぶされているかどうかを示す値を取得します。 |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | GS1 Composite Bar パラメータ。 |
| [getHanXin()](#getHanXin--) | HanXin パラメータ。 |
| [getITF()](#getITF--) | ITF パラメータ。 |
| [getMaxiCode()](#getMaxiCode--) | MaxiCode パラメータ。 |
| [getPadding()](#getPadding--) | バーコードの余白。 |
| [getPatchCode()](#getPatchCode--) | PatchCode パラメータ。 |
| [getPdf417()](#getPdf417--) | PDF417 パラメータ。 |
| [getPostal()](#getPostal--) | 郵便パラメータ。 |
| [getQR()](#getQR--) | QR、MicroQR、RectMicroQR のパラメータ。 |
| [getSupplement()](#getSupplement--) | サプリメント パラメータ。 |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | 1D バーコード専用です。 |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | 太いバーと細いバーの比率。 |
| [getXDimension()](#getXDimension--) | x-ディメンションは、バーコードのバーまたはスペースの単位の最小幅です。 |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(int value)](#setBarColor-int-) | バーの色。 |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | 1D バーコードのバーの高さ（[Unit](../../com.aspose.barcode.generation/unit) の値）です。 |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | 印刷時のインク拡散を補正するために使用されるバーの縮小値を設定します。 |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | Code128 および GS1Code128 バーコードの人が読めるテキストにチェックサム桁を常に表示します。 |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | バーが塗りつぶされているかどうかを示す値を設定します。 |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | GS1 Composite Bar パラメータ。 |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | 1D バーコード専用です。 |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | 太いバーと細いバーの比率。 |
| [setXDimension(Unit value)](#setXDimension-com.aspose.barcode.generation.Unit-) | x-ディメンションは、バーコードのバーまたはスペースの単位の最小幅です。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAustralianPost() {#getAustralianPost--}
```
public final AustralianPostParameters getAustralianPost()
```


AustralianPost バーコードパラメータ。

**Returns:**
[AustralianPostParameters](../../com.aspose.barcode.generation/australianpostparameters)
### getAztec() {#getAztec--}
```
public final AztecParameters getAztec()
```


Aztec パラメータ。

**Returns:**
[AztecParameters](../../com.aspose.barcode.generation/aztecparameters)
### getBarColor() {#getBarColor--}
```
public final int getBarColor()
```


バーの色。デフォルト値: Color.Black。

**Returns:**
int
### getBarHeight() {#getBarHeight--}
```
public final Unit getBarHeight()
```


1D バーコードのバーの高さを [Unit](../../com.aspose.barcode.generation/unit) の値で指定します。BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) プロパティが AutoSizeMode.Nearest または AutoSizeMode.Interpolation に設定されている場合は無視されます。

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


印刷時のインク拡散を補正するために使用されるバーの縮小値を取得します。デフォルト値: 0

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - bars reduction value that is used to compensate ink spread while printing.
### getChecksumAlwaysShow() {#getChecksumAlwaysShow--}
```
public final boolean getChecksumAlwaysShow()
```


Code128 および GS1Code128 バーコードの人が読めるテキストにチェックサム桁を常に表示します。

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


Codabar パラメータ。

**Returns:**
[CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)
### getCodablock() {#getCodablock--}
```
public final CodablockParameters getCodablock()
```


Codablock パラメータ。

**Returns:**
[CodablockParameters](../../com.aspose.barcode.generation/codablockparameters)
### getCode128() {#getCode128--}
```
public final Code128Parameters getCode128()
```


Code128 パラメータ。

**Returns:**
[Code128Parameters](../../com.aspose.barcode.generation/code128parameters)
### getCode16K() {#getCode16K--}
```
public final Code16KParameters getCode16K()
```


Code16K パラメータ。

**Returns:**
[Code16KParameters](../../com.aspose.barcode.generation/code16kparameters)
### getCodeTextParameters() {#getCodeTextParameters--}
```
public final CodetextParameters getCodeTextParameters()
```


Codetext パラメータ。

**Returns:**
[CodetextParameters](../../com.aspose.barcode.generation/codetextparameters)
### getCoupon() {#getCoupon--}
```
public final CouponParameters getCoupon()
```


クーポンパラメータ。UpcaGs1DatabarCoupon、UpcaGs1Code128Coupon 用です。

**Returns:**
[CouponParameters](../../com.aspose.barcode.generation/couponparameters)
### getDataBar() {#getDataBar--}
```
public final DataBarParameters getDataBar()
```


Databar パラメータ。

**Returns:**
[DataBarParameters](../../com.aspose.barcode.generation/databarparameters)
### getDataMatrix() {#getDataMatrix--}
```
public final DataMatrixParameters getDataMatrix()
```


DataMatrix パラメータ。

**Returns:**
[DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)
### getDotCode() {#getDotCode--}
```
public final DotCodeParameters getDotCode()
```


DotCode パラメータ。

**Returns:**
[DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters)
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


バーが塗りつぶされているかどうかを示す値を取得します。1D バーコードのみ対象です。デフォルト値: true。

**Returns:**
boolean - バーが塗りつぶされているかどうかを示す値。
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


GS1 Composite Bar パラメータ。

このサンプルは GS1 Composite Bar 画像の作成と保存方法を示します。1D のコードテキストと 2D のコードテキストは記号 '|' で区切られていることに注意してください。

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


HanXin パラメータ。

**Returns:**
[HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)
### getITF() {#getITF--}
```
public final ITFParameters getITF()
```


ITF パラメータ。

**Returns:**
[ITFParameters](../../com.aspose.barcode.generation/itfparameters)
### getMaxiCode() {#getMaxiCode--}
```
public final MaxiCodeParameters getMaxiCode()
```


MaxiCode パラメータ。

**Returns:**
[MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)
### getPadding() {#getPadding--}
```
public final Padding getPadding()
```


バーコードの余白。デフォルト値: 5pt 5pt 5pt 5pt。

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getPatchCode() {#getPatchCode--}
```
public final PatchCodeParameters getPatchCode()
```


PatchCode パラメータ。

**Returns:**
[PatchCodeParameters](../../com.aspose.barcode.generation/patchcodeparameters)
### getPdf417() {#getPdf417--}
```
public final Pdf417Parameters getPdf417()
```


PDF417 パラメータ。

**Returns:**
[Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)
### getPostal() {#getPostal--}
```
public final PostalParameters getPostal()
```


郵便パラメータです。Postnet、Planet に使用されます。

**Returns:**
[PostalParameters](../../com.aspose.barcode.generation/postalparameters)
### getQR() {#getQR--}
```
public final QrParameters getQR()
```


QR、MicroQR、RectMicroQR のパラメータ。

**Returns:**
[QrParameters](../../com.aspose.barcode.generation/qrparameters)
### getSupplement() {#getSupplement--}
```
public final SupplementParameters getSupplement()
```


補足パラメータ。Interleaved2of5、Standard2of5、EAN13、EAN8、UPCA、UPCE、ISBN、ISSN、ISMN 用です。

**Returns:**
[SupplementParameters](../../com.aspose.barcode.generation/supplementparameters)
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public final boolean getThrowExceptionWhenCodeTextIncorrect()
```


1D バーコード専用です。codetext が正しくなく、値が true に設定されている場合は例外がスローされます。そうでない場合は、codetext がバーコードの仕様に合わせて修正されます。例外が常にスローされるのは: codetext が正しくない場合の Databar シンボロジー。例外が常にスローされないのは: AustraliaPost、SingapurePost、Code39FullASCII、Code93、Code16K、Code128 シンボロジーで codetext が正しくない場合。

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public final float getWideNarrowRatio()
```


太いバーと細いバーの比率。デフォルト値: 3、つまり太いバーは細いバーの 3 倍の幅です。ITF、PZN、PharmaCode、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、IATA2of5、VIN、DeutschePost、OPC、Code32、DataLogic2of5、PatchCode、Code39、Code39FullASCII 用です。

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public final Unit getXDimension()
```


x-ディメンションはバーコードのバーまたはスペースの単位の最小幅です。これを増やすと全体のバーコード画像の幅が広がります。BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) プロパティが AutoSizeMode.Nearest または AutoSizeMode.Interpolation に設定されている場合は無視されます。

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


1D バーコード生成時にチェックサムを有効にします。

デフォルトは、チェックサムが必須のシンボロジーでは Yes とみなされ、チェックサムが任意の場合は No とみなされます。

チェックサムが可能なシンボロジー: Code39 Standard/Extended、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN、Codabar

チェックサムが常に使用されるシンボロジー: その他のシンボロジー

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


バーの色。デフォルト値: Color.Black。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


1D バーコードのバーの高さを [Unit](../../com.aspose.barcode.generation/unit) の値で指定します。BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) プロパティが AutoSizeMode.Nearest または AutoSizeMode.Interpolation に設定されている場合は無視されます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


印刷時のインク拡散を補正するために使用されるバーの縮小値を設定します。デフォルト値: 0

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | 印刷時のインク拡散を補正するために使用されるバーの縮小値。 |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


Code128 および GS1Code128 バーコードの人が読めるテキストにチェックサム桁を常に表示します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


1D バーコード生成時にチェックサムを有効にします。

デフォルトは、チェックサムが必須のシンボロジーでは Yes とみなされ、チェックサムが任意の場合は No とみなされます。

チェックサムが可能なシンボロジー: Code39 Standard/Extended、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN、Codabar

チェックサムが常に使用されるシンボロジー: その他のシンボロジー

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


バーが塗りつぶされているかどうかを示す値を設定します。1D バーコードのみ対象です。デフォルト値: true。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | バーが塗りつぶされているかどうかを示す値。 |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


GS1 Composite Bar パラメータ。

このサンプルは GS1 Composite Bar 画像の作成と保存方法を示します。1D のコードテキストと 2D のコードテキストは記号 '|' で区切られていることに注意してください。

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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


1D バーコード専用です。codetext が正しくなく、値が true に設定されている場合は例外がスローされます。そうでない場合は、codetext がバーコードの仕様に合わせて修正されます。例外が常にスローされるのは: codetext が正しくない場合の Databar シンボロジー。例外が常にスローされないのは: AustraliaPost、SingapurePost、Code39FullASCII、Code93、Code16K、Code128 シンボロジーで codetext が正しくない場合。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


太いバーと細いバーの比率。デフォルト値: 3、つまり太いバーは細いバーの 3 倍の幅です。ITF、PZN、PharmaCode、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、IATA2of5、VIN、DeutschePost、OPC、Code32、DataLogic2of5、PatchCode、Code39、Code39FullASCII 用です。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


x-ディメンションはバーコードのバーまたはスペースの単位の最小幅です。これを増やすと全体のバーコード画像の幅が広がります。BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) プロパティが AutoSizeMode.Nearest または AutoSizeMode.Interpolation に設定されている場合は無視されます。

**Parameters:**
| パラメータ | 型 | 説明 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

