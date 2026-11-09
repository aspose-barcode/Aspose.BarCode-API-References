---
title: "BarcodeParameters"
second_title: "Aspose.BarCode for Java API-referentie"
description: "Barcode-generatieparameters."
type: docs
weight: 14
url: /nl/java/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

Barcode-generatieparameters.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAustralianPost()](#getAustralianPost--) | AustralianPost barcode-parameters. |
| [getAztec()](#getAztec--) | Aztec-parameters. |
| [getBarColor()](#getBarColor--) | Kleur van de staven. |
| [getBarHeight()](#getBarHeight--) | Hoogte van de balken van 1D-barcode's in [Unit](../../com.aspose.barcode.generation/unit) waarde. |
| [getBarWidthReduction()](#getBarWidthReduction--) | Haal de waarde voor balkreductie op die wordt gebruikt om inktverspreiding tijdens het afdrukken te compenseren. |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Toon altijd het controlecijfer in de menselijk leesbare tekst voor Code128- en GS1Code128-barcodes. |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Codabar-parameters. |
| [getCodablock()](#getCodablock--) | Codablock-parameters. |
| [getCode128()](#getCode128--) | Code128-parameters. |
| [getCode16K()](#getCode16K--) | Code16K parameters. |
| [getCodeTextParameters()](#getCodeTextParameters--) | Codetext parameters. |
| [getCoupon()](#getCoupon--) | Coupon parameters. |
| [getDataBar()](#getDataBar--) | Databar parameters. |
| [getDataMatrix()](#getDataMatrix--) | DataMatrix parameters. |
| [getDotCode()](#getDotCode--) | DotCode parameters. |
| [getFilledBars()](#getFilledBars--) | Haalt een waarde op die aangeeft of de staven gevuld zijn. |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | GS1 Composite Bar parameters. |
| [getHanXin()](#getHanXin--) | HanXin parameters. |
| [getITF()](#getITF--) | ITF parameters. |
| [getMaxiCode()](#getMaxiCode--) | MaxiCode parameters. |
| [getPadding()](#getPadding--) | Barcode opvullingen. |
| [getPatchCode()](#getPatchCode--) | PatchCode parameters. |
| [getPdf417()](#getPdf417--) | PDF417 parameters. |
| [getPostal()](#getPostal--) | Postparameters. |
| [getQR()](#getQR--) | QR-, MicroQR- en RectMicroQR-parameters. |
| [getSupplement()](#getSupplement--) | Aanvullende parameters. |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | Alleen voor 1D-barcodes. |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | Verhouding brede staven tot smalle staven. |
| [getXDimension()](#getXDimension--) | x-dimensie is de kleinste breedte van de eenheid van BarCode-balken of -ruimtes. |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(Color value)](#setBarColor-java.awt.Color-) | Kleur van de staven. |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | Hoogte van de balken van 1D-barcode's in [Unit](../../com.aspose.barcode.generation/unit) waarde. |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | Stelt de waarde voor balkreductie in die wordt gebruikt om inktverspreiding tijdens het afdrukken te compenseren. |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | Toon altijd het controlecijfer in de menselijk leesbare tekst voor Code128- en GS1Code128-barcodes. |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | Stelt een waarde in die aangeeft of de balken gevuld zijn. |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | GS1 Composite Bar parameters. |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | Alleen voor 1D-barcodes. |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | Verhouding brede staven tot smalle staven. |
| [setXDimension(Unit value)](#setXDimension-com.aspose.barcode.generation.Unit-) | x-dimensie is de kleinste breedte van de eenheid van BarCode-balken of -ruimtes. |
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
### getAustralianPost() {#getAustralianPost--}
```
public final AustralianPostParameters getAustralianPost()
```


AustralianPost barcode-parameters.

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
public final Color getBarColor()
```


Kleur van de balken. Standaardwaarde: Color.Black.

**Returns:**
java.awt.Color
### getBarHeight() {#getBarHeight--}
```
public final Unit getBarHeight()
```


Hoogte van de balken van 1D-barcode's in [Unit](../../com.aspose.barcode.generation/unit) waarde. Genegeerd als  BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) eigenschap is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


Haal de waarde voor balkreductie op die wordt gebruikt om inktverspreiding tijdens het afdrukken te compenseren. Standaardwaarde: 0

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - bars reduction value that is used to compensate ink spread while printing.
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


Code16K parameters.

**Returns:**
[Code16KParameters](../../com.aspose.barcode.generation/code16kparameters)
### getCodeTextParameters() {#getCodeTextParameters--}
```
public final CodetextParameters getCodeTextParameters()
```


Codetext parameters.

**Returns:**
[CodetextParameters](../../com.aspose.barcode.generation/codetextparameters)
### getCoupon() {#getCoupon--}
```
public final CouponParameters getCoupon()
```


Couponparameters. Gebruikt voor UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

**Returns:**
[CouponParameters](../../com.aspose.barcode.generation/couponparameters)
### getDataBar() {#getDataBar--}
```
public final DataBarParameters getDataBar()
```


Databar parameters.

**Returns:**
[DataBarParameters](../../com.aspose.barcode.generation/databarparameters)
### getDataMatrix() {#getDataMatrix--}
```
public final DataMatrixParameters getDataMatrix()
```


DataMatrix parameters.

**Returns:**
[DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)
### getDotCode() {#getDotCode--}
```
public final DotCodeParameters getDotCode()
```


DotCode parameters.

**Returns:**
[DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters)
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


Haalt een waarde op die aangeeft of de balken gevuld zijn. Alleen voor 1D-barcode's. Standaardwaarde: true.

**Returns:**
boolean - een waarde die aangeeft of de balken gevuld zijn.
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


GS1 Composite Bar parameters.

Dit voorbeeld toont hoe een GS1 Composite Bar-afbeelding te maken en op te slaan. Merk op dat 1D-codetext en 2D-codetext gescheiden zijn door het symbool '|'.

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


HanXin parameters.

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


Barcode opvullingen. Standaardwaarde: 5pt 5pt 5pt 5pt.

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


QR-, MicroQR- en RectMicroQR-parameters.

**Returns:**
[QrParameters](../../com.aspose.barcode.generation/qrparameters)
### getSupplement() {#getSupplement--}
```
public final SupplementParameters getSupplement()
```


Supplementaire parameters. Gebruikt voor Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

**Returns:**
[SupplementParameters](../../com.aspose.barcode.generation/supplementparameters)
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public final boolean getThrowExceptionWhenCodeTextIncorrect()
```


Alleen voor 1D-barcode's. Als de codetext onjuist is en de waarde is ingesteld op true, wordt een uitzondering gegooid. Anders wordt de codetext gecorrigeerd om te voldoen aan de specificatie van de barcode. Een uitzondering wordt altijd gegooid voor: Databar-symbologie als de codetext onjuist is. Een uitzondering wordt nooit gegooid voor: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128-symbologie als de codetext onjuist is.

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public final float getWideNarrowRatio()
```


Verhouding brede balken tot smalle balken. Standaardwaarde: 3, dat wil zeggen, brede balken zijn 3 keer zo breed als smalle balken. Gebruikt voor ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII.

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public final Unit getXDimension()
```


x-dimensie is de kleinste breedte van de eenheid van BarCode-balken of -ruimtes. Verhogen hiervan vergroot de totale breedte van de barcode-afbeelding. Genegeerd als  BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) eigenschap is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation.

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


Schakel controlecijfer in tijdens het genereren van 1D-barcodes.

Standaard wordt behandeld als Ja voor symbologie die een controlegetal moet bevatten, als Nee waar een controlegetal alleen mogelijk is.

Controlegetal is mogelijk: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Controlegetal altijd gebruikt: Rest symbologie

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


Kleur van de balken. Standaardwaarde: Color.Black.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.awt.Color |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


Hoogte van de balken van 1D-barcode's in [Unit](../../com.aspose.barcode.generation/unit) waarde. Genegeerd als  BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) eigenschap is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


Stelt de balkreductiewaarde in die wordt gebruikt om inktverspreiding tijdens het afdrukken te compenseren. Standaardwaarde: 0

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | balkreductiewaarde die wordt gebruikt om inktverspreiding tijdens het afdrukken te compenseren. |

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


Schakel controlecijfer in tijdens het genereren van 1D-barcodes.

Standaard wordt behandeld als Ja voor symbologie die een controlegetal moet bevatten, als Nee waar een controlegetal alleen mogelijk is.

Controlegetal is mogelijk: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Controlegetal altijd gebruikt: Rest symbologie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


Stelt een waarde in die aangeeft of balken gevuld zijn. Alleen voor 1D-streepjescodes. Standaardwaarde: true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | een waarde die aangeeft of balken gevuld zijn. |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


GS1 Composite Bar parameters.

Dit voorbeeld toont hoe een GS1 Composite Bar-afbeelding te maken en op te slaan. Merk op dat 1D-codetext en 2D-codetext gescheiden zijn door het symbool '|'.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


Alleen voor 1D-barcode's. Als de codetext onjuist is en de waarde is ingesteld op true, wordt een uitzondering gegooid. Anders wordt de codetext gecorrigeerd om te voldoen aan de specificatie van de barcode. Een uitzondering wordt altijd gegooid voor: Databar-symbologie als de codetext onjuist is. Een uitzondering wordt nooit gegooid voor: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128-symbologie als de codetext onjuist is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


Verhouding brede balken tot smalle balken. Standaardwaarde: 3, dat wil zeggen, brede balken zijn 3 keer zo breed als smalle balken. Gebruikt voor ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


x-dimensie is de kleinste breedte van de eenheid van BarCode-balken of -ruimtes. Verhogen hiervan vergroot de totale breedte van de barcode-afbeelding. Genegeerd als  BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) eigenschap is ingesteld op AutoSizeMode.Nearest of AutoSizeMode.Interpolation.

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
public final native void wait(long arg0)
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

