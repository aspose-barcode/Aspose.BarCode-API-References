---
title: BarcodeParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: Barcode generation parameters.
type: docs
weight: 14
url: /androidjava/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

Barcode generation parameters.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAustralianPost()](#getAustralianPost--) | AustralianPost barcode parameters. |
| [getAztec()](#getAztec--) | Aztec parameters. |
| [getBarColor()](#getBarColor--) | Bars color. |
| [getBarHeight()](#getBarHeight--) | Height of 1D barcodes' bars in  Unit  value. |
| [getBarWidthReduction()](#getBarWidthReduction--) | Get bars reduction value that is used to compensate ink spread while printing. |
| [getBarcodeType()](#getBarcodeType--) |  |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes. |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Codabar parameters. |
| [getCodablock()](#getCodablock--) | Codablock parameters. |
| [getCode128()](#getCode128--) | Code128 parameters. |
| [getCode16K()](#getCode16K--) | Code16K parameters. |
| [getCodeText()](#getCodeText--) |  |
| [getCodeTextParameters()](#getCodeTextParameters--) | Codetext parameters. |
| [getCoupon()](#getCoupon--) | Coupon parameters. |
| [getDataBar()](#getDataBar--) | Databar parameters. |
| [getDataMatrix()](#getDataMatrix--) | DataMatrix parameters. |
| [getDotCode()](#getDotCode--) | DotCode parameters. |
| [getEnableEscape()](#getEnableEscape--) | Indicates whether explains the character "\\" as an escape character in CodeText property. |
| [getFilledBars()](#getFilledBars--) | Gets a value indicating whether bars filled. |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | GS1 Composite Bar parameters. |
| [getHanXin()](#getHanXin--) | HanXin parameters. |
| [getITF()](#getITF--) | ITF parameters. |
| [getMaxiCode()](#getMaxiCode--) | MaxiCode parameters. |
| [getPadding()](#getPadding--) | Barcode paddings. |
| [getPatchCode()](#getPatchCode--) | PatchCode parameters. |
| [getPdf417()](#getPdf417--) | PDF417 parameters. |
| [getPostal()](#getPostal--) | Postal parameters. |
| [getQR()](#getQR--) | QR, MicroQR and RectMicroQR parameters. |
| [getSupplement()](#getSupplement--) | Supplement parameters. |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | Only for 1D barcodes. |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | Wide bars to Narrow bars ratio. |
| [getXDimension()](#getXDimension--) | x-dimension is the smallest width of the unit of BarCode bars or spaces. |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(int value)](#setBarColor-int-) | Bars color. |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | Height of 1D barcodes' bars in  Unit  value. |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAustralianPost() {#getAustralianPost--}
```
public AustralianPostParameters getAustralianPost()
```


AustralianPost barcode parameters.

**Returns:**
[AustralianPostParameters](../../com.aspose.barcode.generation/australianpostparameters)
### getAztec() {#getAztec--}
```
public AztecParameters getAztec()
```


Aztec parameters.

**Returns:**
[AztecParameters](../../com.aspose.barcode.generation/aztecparameters)
### getBarColor() {#getBarColor--}
```
public int getBarColor()
```


Bars color. Default value: Color.Black.

**Returns:**
int
### getBarHeight() {#getBarHeight--}
```
public Unit getBarHeight()
```


Height of 1D barcodes' bars in  Unit  value. Ignored if  AutoSizeMode  property is set to AutoSizeMode.Nearest or AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public Unit getBarWidthReduction()
```


Get bars reduction value that is used to compensate ink spread while printing.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```




**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
### getChecksumAlwaysShow() {#getChecksumAlwaysShow--}
```
public boolean getChecksumAlwaysShow()
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
public CodabarParameters getCodabar()
```


Codabar parameters.

**Returns:**
[CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)
### getCodablock() {#getCodablock--}
```
public CodablockParameters getCodablock()
```


Codablock parameters.

**Returns:**
[CodablockParameters](../../com.aspose.barcode.generation/codablockparameters)
### getCode128() {#getCode128--}
```
public Code128Parameters getCode128()
```


Code128 parameters.

**Returns:**
[Code128Parameters](../../com.aspose.barcode.generation/code128parameters)
### getCode16K() {#getCode16K--}
```
public Code16KParameters getCode16K()
```


Code16K parameters.

**Returns:**
[Code16KParameters](../../com.aspose.barcode.generation/code16kparameters)
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```




**Returns:**
java.lang.String
### getCodeTextParameters() {#getCodeTextParameters--}
```
public CodetextParameters getCodeTextParameters()
```


Codetext parameters.

**Returns:**
[CodetextParameters](../../com.aspose.barcode.generation/codetextparameters)
### getCoupon() {#getCoupon--}
```
public CouponParameters getCoupon()
```


Coupon parameters. Used for UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

**Returns:**
[CouponParameters](../../com.aspose.barcode.generation/couponparameters)
### getDataBar() {#getDataBar--}
```
public DataBarParameters getDataBar()
```


Databar parameters.

**Returns:**
[DataBarParameters](../../com.aspose.barcode.generation/databarparameters)
### getDataMatrix() {#getDataMatrix--}
```
public DataMatrixParameters getDataMatrix()
```


DataMatrix parameters.

**Returns:**
[DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)
### getDotCode() {#getDotCode--}
```
public DotCodeParameters getDotCode()
```


DotCode parameters.

**Returns:**
[DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters)
### getEnableEscape() {#getEnableEscape--}
```
public boolean getEnableEscape()
```


Indicates whether explains the character "\\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, Code128 only If the EnableEscape is true, "\\" will be explained as a special escape character. Otherwise, "\\" acts as normal characters.

--------------------

Aspose.BarCode supports inputing decimal ascii code and mnemonic for ASCII control-code characters. For example, \\013 and \\\\CR stands for CR.

**Returns:**
boolean
### getFilledBars() {#getFilledBars--}
```
public boolean getFilledBars()
```


Gets a value indicating whether bars filled. Only for 1D barcodes. Default value: true.

**Returns:**
boolean
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public GS1CompositeBarParameters getGS1CompositeBar()
```


GS1 Composite Bar parameters. This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D codetext are separated by symbol '|' String codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8"; BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS\_1\_COMPOSITE\_BAR, codetext); generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS\_1\_CODE\_128); generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC\_A); // Aspect ratio of 2D component generator.getParameters().getBarcode().getPdf417().setAspectRatio(3); // X-Dimension of 1D and 2D components generator.getParameters().getBarcode().getXDimension().setPixels(3); /// // Height of 1D component generator.getParameters().getBarcode().getBarHeight().setPixels(100); /// generator.save("test.png");

**Returns:**
[GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) - GS1 Composite Bar parameters.
### getHanXin() {#getHanXin--}
```
public HanXinParameters getHanXin()
```


HanXin parameters.

**Returns:**
[HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)
### getITF() {#getITF--}
```
public ITFParameters getITF()
```


ITF parameters.

**Returns:**
[ITFParameters](../../com.aspose.barcode.generation/itfparameters)
### getMaxiCode() {#getMaxiCode--}
```
public MaxiCodeParameters getMaxiCode()
```


MaxiCode parameters.

**Returns:**
[MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)
### getPadding() {#getPadding--}
```
public Padding getPadding()
```


Barcode paddings. Default value: 5pt 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getPatchCode() {#getPatchCode--}
```
public PatchCodeParameters getPatchCode()
```


PatchCode parameters.

**Returns:**
[PatchCodeParameters](../../com.aspose.barcode.generation/patchcodeparameters)
### getPdf417() {#getPdf417--}
```
public Pdf417Parameters getPdf417()
```


PDF417 parameters.

**Returns:**
[Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)
### getPostal() {#getPostal--}
```
public PostalParameters getPostal()
```


Postal parameters. Used for Postnet, Planet.

**Returns:**
[PostalParameters](../../com.aspose.barcode.generation/postalparameters)
### getQR() {#getQR--}
```
public QrParameters getQR()
```


QR, MicroQR and RectMicroQR parameters.

**Returns:**
[QrParameters](../../com.aspose.barcode.generation/qrparameters)
### getSupplement() {#getSupplement--}
```
public SupplementParameters getSupplement()
```


Supplement parameters. Used for Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

**Returns:**
[SupplementParameters](../../com.aspose.barcode.generation/supplementparameters)
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public boolean getThrowExceptionWhenCodeTextIncorrect()
```


Only for 1D barcodes. If codetext is incorrect and value set to true - exception will be thrown. Otherwise codetext will be corrected to match barcode's specification. Exception always will be thrown for: Databar symbology if codetext is incorrect. Exception always will not be thrown for: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 symbology if codetext is incorrect.

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public float getWideNarrowRatio()
```


Wide bars to Narrow bars ratio. Default value: 3, that is, wide bars are 3 times as wide as narrow bars. Used for ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public Unit getXDimension()
```


x-dimension is the smallest width of the unit of BarCode bars or spaces. Increase this will increase the whole barcode image width. Ignored if  BaseGenerationParameters.AutoSizeMode  property is set to AutoSizeMode.Nearest or AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isChecksumEnabled() {#isChecksumEnabled--}
```
public EnableChecksum isChecksumEnabled()
```


Enable checksum during generation 1D barcodes.

Default is treated as Yes for symbology which must contain checksum, as No where checksum only possible.

Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Checksum always used: Rest symbology

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
public void setBarColor(int value)
```


Bars color. Default value: Color.Black.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public void setBarHeight(Unit value)
```


Height of 1D barcodes' bars in  Unit  value. Ignored if  AutoSizeMode  property is set to AutoSizeMode.Nearest or AutoSizeMode.Interpolation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public void setBarWidthReduction(Unit value)
```


Sets bars reduction value that is used to compensate ink spread while printing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public void setChecksumAlwaysShow(boolean value)
```


Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public void setChecksumEnabled(EnableChecksum value)
```


Enable checksum during generation 1D barcodes.

Default is treated as Yes for symbology which must contain checksum, as No where checksum only possible.

Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Checksum always used: Rest symbology

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public void setCodeText(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setEnableEscape(boolean value) {#setEnableEscape-boolean-}
```
public void setEnableEscape(boolean value)
```


Indicates whether explains the character "\\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, Code128 only If the EnableEscape is true, "\\" will be explained as a special escape character. Otherwise, "\\" acts as normal characters.

--------------------

Aspose.BarCode supports inputing decimal ascii code and mnemonic for ASCII control-code characters. For example, \\013 and \\\\CR stands for CR.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public void setFilledBars(boolean value)
```


Sets a value indicating whether bars filled. Only for 1D barcodes. Default value: true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public void setGS1CompositeBar(GS1CompositeBarParameters value)
```


GS1 Composite Bar parameters. This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D codetext are separated by symbol '/' String codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8"; BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS\_1\_COMPOSITE\_BAR, codetext); generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS\_1\_CODE\_128); generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC\_A); // Aspect ratio of 2D component generator.getParameters().getBarcode().getPdf417().setAspectRatio(3); // X-Dimension of 1D and 2D components generator.getParameters().getBarcode().getXDimension().setPixels(3); /// // Height of 1D component generator.getParameters().getBarcode().getBarHeight().setPixels(100); /// generator.save("test.png");

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


Only for 1D barcodes. If codetext is incorrect and value set to true - exception will be thrown. Otherwise codetext will be corrected to match barcode's specification. Exception always will be thrown for: Databar symbology if codetext is incorrect. Exception always will not be thrown for: AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128 symbology if codetext is incorrect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public void setWideNarrowRatio(float value)
```


Wide bars to Narrow bars ratio. Default value: 3, that is, wide bars are 3 times as wide as narrow bars. Used for ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public void setXDimension(Unit value)
```


x-dimension is the smallest width of the unit of BarCode bars or spaces. Increase this will increase the whole barcode image width. Ignored if  BaseGenerationParameters.AutoSizeMode  property is set to AutoSizeMode.Nearest or AutoSizeMode.Interpolation.

**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

