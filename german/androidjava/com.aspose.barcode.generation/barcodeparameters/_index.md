---
title: BarcodeParameters
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Parameter zur Barcode-Erzeugung.
type: docs
weight: 14
url: /de/androidjava/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

Parameter zur Barcode-Erzeugung.
## Methods

| Method | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) |  |
| [getAustralianPost()](#getAustralianPost--) | AustralianPost-Barcode-Parameter. |
| [getAztec()](#getAztec--) | Aztec-Parameter. |
| [getBarColor()](#getBarColor--) | Farbe der Balken. |
| [getBarHeight()](#getBarHeight--) | Höhe der Balken von 1D‑Barcodes im [Unit](../../com.aspose.barcode.generation/unit)-Wert. |
| [getBarWidthReduction()](#getBarWidthReduction--) | Erhalte den Reduktionswert der Balken, der verwendet wird, um die Tintenausbreitung beim Drucken auszugleichen. |
| [getBarcodeType()](#getBarcodeType--) |  |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes. |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Codabar-Parameter. |
| [getCodablock()](#getCodablock--) | Codablock-Parameter. |
| [getCode128()](#getCode128--) | Code128-Parameter. |
| [getCode16K()](#getCode16K--) | Code16K-Parameter. |
| [getCodeText()](#getCodeText--) |  |
| [getCodeTextParameters()](#getCodeTextParameters--) | Codetext-Parameter. |
| [getComplexBarcode()](#getComplexBarcode--) |  |
| [getCoupon()](#getCoupon--) | Gutschein-Parameter. |
| [getDataBar()](#getDataBar--) | Databar-Parameter. |
| [getDataMatrix()](#getDataMatrix--) | DataMatrix-Parameter. |
| [getDotCode()](#getDotCode--) | DotCode-Parameter. |
| [getEnableEscape()](#getEnableEscape--) | Indicates whether explains the character "\\" as an escape character in CodeText property. |
| [getFilledBars()](#getFilledBars--) | Gets a value indicating whether bars filled. |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | GS1 Composite Bar parameters. |
| [getHanXin()](#getHanXin--) | HanXin parameters. |
| [getITF()](#getITF--) | ITF-Parameter. |
| [getMaxiCode()](#getMaxiCode--) | MaxiCode-Parameter. |
| [getPadding()](#getPadding--) | Barcode paddings. |
| [getPatchCode()](#getPatchCode--) | PatchCode-Parameter. |
| [getPdf417()](#getPdf417--) | PDF417-Parameter. |
| [getPostal()](#getPostal--) | Post-Parameter. |
| [getQR()](#getQR--) | QR, MicroQR and RectMicroQR parameters. |
| [getSupplement()](#getSupplement--) | Ergänzungsparameter. |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | Only for 1D barcodes. |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | Wide bars to Narrow bars ratio. |
| [getXDimension()](#getXDimension--) | x-dimension is the smallest width of the unit of BarCode bars or spaces. |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(int value)](#setBarColor-int-) | Farbe der Balken. |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | Höhe der Balken von 1D‑Barcodes im [Unit](../../com.aspose.barcode.generation/unit)-Wert. |
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
| Parameter | Type | Beschreibung |
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


AustralianPost-Barcode-Parameter.

**Returns:**
[AustralianPostParameters](../../com.aspose.barcode.generation/australianpostparameters)
### getAztec() {#getAztec--}
```
public final AztecParameters getAztec()
```


Aztec-Parameter.

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


Codabar-Parameter.

**Returns:**
[CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)
### getCodablock() {#getCodablock--}
```
public final CodablockParameters getCodablock()
```


Codablock-Parameter.

**Returns:**
[CodablockParameters](../../com.aspose.barcode.generation/codablockparameters)
### getCode128() {#getCode128--}
```
public final Code128Parameters getCode128()
```


Code128-Parameter.

**Returns:**
[Code128Parameters](../../com.aspose.barcode.generation/code128parameters)
### getCode16K() {#getCode16K--}
```
public final Code16KParameters getCode16K()
```


Code16K-Parameter.

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


Codetext-Parameter.

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


Databar-Parameter.

**Returns:**
[DataBarParameters](../../com.aspose.barcode.generation/databarparameters)
### getDataMatrix() {#getDataMatrix--}
```
public final DataMatrixParameters getDataMatrix()
```


DataMatrix-Parameter.

**Returns:**
[DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)
### getDotCode() {#getDotCode--}
```
public final DotCodeParameters getDotCode()
```


DotCode-Parameter.

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


ITF-Parameter.

**Returns:**
[ITFParameters](../../com.aspose.barcode.generation/itfparameters)
### getMaxiCode() {#getMaxiCode--}
```
public final MaxiCodeParameters getMaxiCode()
```


MaxiCode-Parameter.

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


PatchCode-Parameter.

**Returns:**
[PatchCodeParameters](../../com.aspose.barcode.generation/patchcodeparameters)
### getPdf417() {#getPdf417--}
```
public final Pdf417Parameters getPdf417()
```


PDF417-Parameter.

**Returns:**
[Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)
### getPostal() {#getPostal--}
```
public final PostalParameters getPostal()
```


Postparameter. Verwendet für Postnet, Planet.

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


x-Dimension ist die kleinste Breite der Einheit von Barcode‑Balken oder -Lücken. Eine Erhöhung davon vergrößert die gesamte Barcode‑Bildbreite. Ignoriert, wenn die Eigenschaft BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist.

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


Prüfsumme während der Erzeugung von 1D‑Barcodes aktivieren.

Standard wird als Ja behandelt für Symbologien, die eine Prüfsumme enthalten müssen, und als Nein, wo eine Prüfsumme nur möglich ist.

Prüfsumme ist möglich: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Prüfsumme wird immer verwendet: übrige Symbologien

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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


Height of 1D barcodes' bars in [Unit](../../com.aspose.barcode.generation/unit) value. Ignored if  BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) property is set to AutoSizeMode.Nearest or AutoSizeMode.Interpolation.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


Legt den Reduktionswert für Balken fest, der zum Ausgleich der Tintenausbreitung beim Drucken verwendet wird. Standardwert: 0

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | Reduktionswert für Balken, der zum Ausgleich der Tintenausbreitung beim Drucken verwendet wird. |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


Always display checksum digit in the human readable text for Code128 and GS1Code128 barcodes.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


Prüfsumme während der Erzeugung von 1D‑Barcodes aktivieren.

Standard wird als Ja behandelt für Symbologien, die eine Prüfsumme enthalten müssen, und als Nein, wo eine Prüfsumme nur möglich ist.

Prüfsumme ist möglich: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Prüfsumme wird immer verwendet: übrige Symbologien

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public final void setCodeText(String value)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### setEnableEscape(boolean value) {#setEnableEscape-boolean-}
```
public final void setEnableEscape(boolean value)
```


Indicates whether explains the character "\\" as an escape character in CodeText property. Used for Pdf417, DataMatrix, Code128 only If the EnableEscape is true, "\\" will be explained as a special escape character. Otherwise, "\\" acts as normal characters.

Aspose.BarCode supports inputing decimal ascii code and mnemonic for ASCII control-code characters. For example, \\013 and \\\\CR stands for CR.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


Legt einen Wert fest, der angibt, ob Balken gefüllt sind. Nur für 1D‑Barcodes. Standardwert: true.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob Balken gefüllt sind. |

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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


Only for 1D barcodes. If codetext is incorrect and value set to true - exception will be thrown. Otherwise codetext will be corrected to match barcode's specification. Exception always will be thrown for: Databar symbology if codetext is incorrect. Exception always will not be thrown for: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 symbology if codetext is incorrect.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


Wide bars to Narrow bars ratio. Default value: 3, that is, wide bars are 3 times as wide as narrow bars. Used for ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


x-Dimension ist die kleinste Breite der Einheit von Barcode‑Balken oder -Lücken. Eine Erhöhung davon vergrößert die gesamte Barcode‑Bildbreite. Ignoriert, wenn die Eigenschaft BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist.

**Parameters:**
| Parameter | Type | Beschreibung |
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

