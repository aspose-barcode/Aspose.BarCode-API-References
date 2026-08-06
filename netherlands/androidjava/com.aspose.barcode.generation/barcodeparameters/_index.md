---
title: BarcodeParameters
second_title: Aspose.BarCode for Android via Java API-referentie
description: Barcode-generatieparameters.
type: docs
weight: 14
url: /nl/androidjava/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

Barcode-generatieparameters.
## Methods

| Method | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) |  |
| [getAustralianPost()](#getAustralianPost--) | AustralianPost barcode parameters. |
| [getAztec()](#getAztec--) | Aztec-parameters. |
| [getBarColor()](#getBarColor--) | Kleur van de balken. |
| [getBarHeight()](#getBarHeight--) | Hoogte van de balken van 1D-barcode in [Unit](../../com.aspose.barcode.generation/unit) waarde. |
| [getBarWidthReduction()](#getBarWidthReduction--) | Haal de reductiewaarde van de balken op die wordt gebruikt om inktverspreiding tijdens het afdrukken te compenseren. |
| [getBarcodeType()](#getBarcodeType--) |  |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Toon altijd het controlecijfer in de menselijk leesbare tekst voor Code128- en GS1Code128-barcodes. |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Codabar-parameters. |
| [getCodablock()](#getCodablock--) | Codablock-parameters. |
| [getCode128()](#getCode128--) | Code128-parameters. |
| [getCode16K()](#getCode16K--) | Code16K-parameters. |
| [getCodeText()](#getCodeText--) |  |
| [getCodeTextParameters()](#getCodeTextParameters--) | Codetekstparameters. |
| [getComplexBarcode()](#getComplexBarcode--) |  |
| [getCoupon()](#getCoupon--) | Coupon-parameters. |
| [getDataBar()](#getDataBar--) | Databar-parameters. |
| [getDataMatrix()](#getDataMatrix--) | DataMatrix-parameters. |
| [getDotCode()](#getDotCode--) | DotCode-parameters. |
| [getEnableEscape()](#getEnableEscape--) | Geeft aan of het teken "\\" wordt uitgelegd als een escape‑teken in de CodeText‑eigenschap. |
| [getFilledBars()](#getFilledBars--) | Haalt een waarde op die aangeeft of de strepen gevuld zijn. |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | GS1 Composite Bar‑parameters. |
| [getHanXin()](#getHanXin--) | HanXin‑parameters. |
| [getITF()](#getITF--) | ITF parameters. |
| [getMaxiCode()](#getMaxiCode--) | MaxiCode parameters. |
| [getPadding()](#getPadding--) | Barcode‑opvulling. |
| [getPatchCode()](#getPatchCode--) | PatchCode parameters. |
| [getPdf417()](#getPdf417--) | PDF417 parameters. |
| [getPostal()](#getPostal--) | Postale parameters. |
| [getQR()](#getQR--) | QR-, MicroQR- en RectMicroQR‑parameters. |
| [getSupplement()](#getSupplement--) | Supplementaire parameters. |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | Alleen voor 1D‑barcodes. |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | Verhouding brede strepen tot smalle strepen. |
| [getXDimension()](#getXDimension--) | De x-dimensie is de kleinste breedte van de eenheid van BarCode‑strepen of -spaties. |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(int value)](#setBarColor-int-) | Kleur van de balken. |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | Hoogte van de balken van 1D-barcode in [Unit](../../com.aspose.barcode.generation/unit) waarde. |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | Stelt de reductiewaarde van strepen in die wordt gebruikt om inktverspreiding tijdens het afdrukken te compenseren. |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | Toon altijd het controlecijfer in de menselijk leesbare tekst voor Code128- en GS1Code128-barcodes. |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setCodeText(String value)](#setCodeText-java.lang.String-) |  |
| [setEnableEscape(boolean value)](#setEnableEscape-boolean-) | Geeft aan of het teken "\\" wordt uitgelegd als een escape‑teken in de CodeText‑eigenschap. |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | Stelt een waarde in die aangeeft of de strepen gevuld zijn. |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | GS1 Composite Bar‑parameters. |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | Alleen voor 1D‑barcodes. |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | Verhouding brede strepen tot smalle strepen. |
| [setXDimension(Unit value)](#setXDimension-com.aspose.barcode.generation.Unit-) | De x-dimensie is de kleinste breedte van de eenheid van BarCode‑strepen of -spaties. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


AustralianPost barcode parameters.

**Returns:**
[AustralianPostParameters](../../com.aspose.barcode.generation/australianpostparameters)
### getAztec() {#getAztec--}
```
public final AztecParameters getAztec()
```


Aztec-parameters.

**Returns:**
[AztecParameters](../../com.aspose.barcode.generation/aztecparameters)
### getBarColor() {#getBarColor--}
```
public final int getBarColor()
```


Kleur van de strepen. Standaardwaarde: Color.Black.

**Returns:**
int
### getBarHeight() {#getBarHeight--}
```
public final Unit getBarHeight()
```


Hoogte van de strepen van 1D‑barcodes in [Unit](../../com.aspose.barcode.generation/unit)-waarde. Genegeerd als de eigenschap BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


Haal de reductiewaarde van strepen op die wordt gebruikt om inktverspreiding tijdens het afdrukken te compenseren. Standaardwaarde: 0

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


Toon altijd het controlecijfer in de menselijk leesbare tekst voor Code128- en GS1Code128-barcodes.

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


Codabar-parameters.

**Returns:**
[CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)
### getCodablock() {#getCodablock--}
```
public final CodablockParameters getCodablock()
```


Codablock-parameters.

**Returns:**
[CodablockParameters](../../com.aspose.barcode.generation/codablockparameters)
### getCode128() {#getCode128--}
```
public final Code128Parameters getCode128()
```


Code128-parameters.

**Returns:**
[Code128Parameters](../../com.aspose.barcode.generation/code128parameters)
### getCode16K() {#getCode16K--}
```
public final Code16KParameters getCode16K()
```


Code16K-parameters.

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


Codetekstparameters.

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


Coupon‑parameters. Gebruikt voor UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

**Returns:**
[CouponParameters](../../com.aspose.barcode.generation/couponparameters)
### getDataBar() {#getDataBar--}
```
public final DataBarParameters getDataBar()
```


Databar-parameters.

**Returns:**
[DataBarParameters](../../com.aspose.barcode.generation/databarparameters)
### getDataMatrix() {#getDataMatrix--}
```
public final DataMatrixParameters getDataMatrix()
```


DataMatrix-parameters.

**Returns:**
[DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)
### getDotCode() {#getDotCode--}
```
public final DotCodeParameters getDotCode()
```


DotCode-parameters.

**Returns:**
[DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters)
### getEnableEscape() {#getEnableEscape--}
```
public final boolean getEnableEscape()
```


Geeft aan of het teken "\\" wordt uitgelegd als een escape‑teken in de CodeText‑eigenschap. Alleen gebruikt voor Pdf417, DataMatrix, Code128. Als EnableEscape true is, wordt "\\" uitgelegd als een speciaal escape‑teken. Anders functioneert "\\" als normale tekens.

Aspose.BarCode ondersteunt het invoeren van decimale ASCII‑codes en mnemonic voor ASCII‑besturingscode‑tekens. Bijvoorbeeld, \\013 en \\\\CR staan voor CR.

**Returns:**
boolean
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


Haalt een waarde op die aangeeft of de strepen gevuld zijn. Alleen voor 1D‑barcodes. Standaardwaarde: true.

**Returns:**
boolean - een waarde die aangeeft of de strepen gevuld zijn.
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


GS1 Composite Bar‑parameters.

Dit voorbeeld toont hoe een GS1 Composite Bar‑afbeelding te maken en op te slaan. Let op dat 1D‑codetext en 2D‑codetext gescheiden worden door het symbool '|'

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


HanXin‑parameters.

**Returns:**
[HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)
### getITF() {#getITF--}
```
public final ITFParameters getITF()
```


ITF parameters.

**Returns:**
[ITFParameters](../../com.aspose.barcode.generation/itfparameters)
### getMaxiCode() {#getMaxiCode--}
```
public final MaxiCodeParameters getMaxiCode()
```


MaxiCode parameters.

**Returns:**
[MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)
### getPadding() {#getPadding--}
```
public final Padding getPadding()
```


Barcode‑opvulling. Standaardwaarde: 5pt 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getPatchCode() {#getPatchCode--}
```
public final PatchCodeParameters getPatchCode()
```


PatchCode parameters.

**Returns:**
[PatchCodeParameters](../../com.aspose.barcode.generation/patchcodeparameters)
### getPdf417() {#getPdf417--}
```
public final Pdf417Parameters getPdf417()
```


PDF417 parameters.

**Returns:**
[Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)
### getPostal() {#getPostal--}
```
public final PostalParameters getPostal()
```


Postale parameters. Gebruikt voor Postnet, Planet.

**Returns:**
[PostalParameters](../../com.aspose.barcode.generation/postalparameters)
### getQR() {#getQR--}
```
public final QrParameters getQR()
```


QR-, MicroQR- en RectMicroQR‑parameters.

**Returns:**
[QrParameters](../../com.aspose.barcode.generation/qrparameters)
### getSupplement() {#getSupplement--}
```
public final SupplementParameters getSupplement()
```


Supplement‑parameters. Gebruikt voor Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

**Returns:**
[SupplementParameters](../../com.aspose.barcode.generation/supplementparameters)
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public final boolean getThrowExceptionWhenCodeTextIncorrect()
```


Alleen voor 1D‑barcodes. Als de codetext onjuist is en de waarde true is ingesteld, wordt een uitzondering gegooid. Anders wordt de codetext gecorrigeerd om te voldoen aan de specificatie van de barcode. Een uitzondering wordt altijd gegooid voor: Databar‑symbologie als de codetext onjuist is. Een uitzondering wordt nooit gegooid voor: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128‑symbologie als de codetext onjuist is.

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public final float getWideNarrowRatio()
```


Verhouding brede strepen tot smalle strepen. Standaardwaarde: 3, dat wil zeggen, brede strepen zijn 3 keer zo breed als smalle strepen. Gebruikt voor ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public final Unit getXDimension()
```


x-dimension is de kleinste breedte van de eenheid van BarCode-strepen of -spaties. Het verhogen hiervan vergroot de totale breedte van de barcode-afbeelding. Genegeerd als de eigenschap BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation.

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


Schakel controlegetal in tijdens het genereren van 1D-barcodes.

Standaard wordt behandeld als Ja voor symbologie die een controlegetal moet bevatten, en als Nee waar een controlegetal alleen mogelijk is.

Controlegetal is mogelijk: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Controlegetal altijd gebruikt: overige symbologie

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


Kleur van de strepen. Standaardwaarde: Color.Black.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


Hoogte van de strepen van 1D‑barcodes in [Unit](../../com.aspose.barcode.generation/unit)-waarde. Genegeerd als de eigenschap BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


Stelt de reductiewaarde van strepen in die wordt gebruikt om inktverspreiding tijdens het afdrukken te compenseren. Standaardwaarde: 0

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | reductiewaarde van strepen die wordt gebruikt om inktverspreiding tijdens het afdrukken te compenseren. |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


Toon altijd het controlecijfer in de menselijk leesbare tekst voor Code128- en GS1Code128-barcodes.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


Schakel controlegetal in tijdens het genereren van 1D-barcodes.

Standaard wordt behandeld als Ja voor symbologie die een controlegetal moet bevatten, en als Nee waar een controlegetal alleen mogelijk is.

Controlegetal is mogelijk: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Controlegetal altijd gebruikt: overige symbologie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public final void setCodeText(String value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setEnableEscape(boolean value) {#setEnableEscape-boolean-}
```
public final void setEnableEscape(boolean value)
```


Geeft aan of het teken "\\" wordt uitgelegd als een escape‑teken in de CodeText‑eigenschap. Alleen gebruikt voor Pdf417, DataMatrix, Code128. Als EnableEscape true is, wordt "\\" uitgelegd als een speciaal escape‑teken. Anders functioneert "\\" als normale tekens.

Aspose.BarCode ondersteunt het invoeren van decimale ASCII‑codes en mnemonic voor ASCII‑besturingscode‑tekens. Bijvoorbeeld, \\013 en \\\\CR staan voor CR.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


Stelt een waarde in die aangeeft of strepen gevuld zijn. Alleen voor 1D-barcodes. Standaardwaarde: true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | een waarde die aangeeft of strepen gevuld zijn. |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


GS1 Composite Bar‑parameters.

Dit voorbeeld toont hoe een GS1 Composite Bar‑afbeelding te maken en op te slaan. Let op dat 1D‑codetext en 2D‑codetext gescheiden worden door het symbool '|'

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


Alleen voor 1D‑barcodes. Als de codetext onjuist is en de waarde true is ingesteld, wordt een uitzondering gegooid. Anders wordt de codetext gecorrigeerd om te voldoen aan de specificatie van de barcode. Een uitzondering wordt altijd gegooid voor: Databar‑symbologie als de codetext onjuist is. Een uitzondering wordt nooit gegooid voor: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128‑symbologie als de codetext onjuist is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


Verhouding brede strepen tot smalle strepen. Standaardwaarde: 3, dat wil zeggen, brede strepen zijn 3 keer zo breed als smalle strepen. Gebruikt voor ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


x-dimension is de kleinste breedte van de eenheid van BarCode-strepen of -spaties. Het verhogen hiervan vergroot de totale breedte van de barcode-afbeelding. Genegeerd als de eigenschap BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation.

**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

