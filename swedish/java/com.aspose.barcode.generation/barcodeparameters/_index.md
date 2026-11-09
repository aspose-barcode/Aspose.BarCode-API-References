---
title: "BarcodeParameters"
second_title: "Aspose.BarCode för Java API-referens"
description: "Parametrar för streckkodsgenerering."
type: docs
weight: 14
url: /sv/java/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

Parametrar för streckkodsgenerering.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAustralianPost()](#getAustralianPost--) | AustralianPost-streckkodparametrar. |
| [getAztec()](#getAztec--) | Aztec-parametrar. |
| [getBarColor()](#getBarColor--) | Streckfärg. |
| [getBarHeight()](#getBarHeight--) | Höjd på 1D-streckkods staplar i [Unit](../../com.aspose.barcode.generation/unit) värde. |
| [getBarWidthReduction()](#getBarWidthReduction--) | Hämta stapelns reduktionsvärde som används för att kompensera bläckspridning vid utskrift. |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Visa alltid kontrollsiffran i den människoläsbara texten för Code128‑ och GS1Code128‑streckkoder. |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Codabar-parametrar. |
| [getCodablock()](#getCodablock--) | Codablock-parametrar. |
| [getCode128()](#getCode128--) | Code128-parametrar. |
| [getCode16K()](#getCode16K--) | Code16K-parametrar. |
| [getCodeTextParameters()](#getCodeTextParameters--) | Codetextparametrar. |
| [getCoupon()](#getCoupon--) | Kupongparametrar. |
| [getDataBar()](#getDataBar--) | Databarparametrar. |
| [getDataMatrix()](#getDataMatrix--) | DataMatrix-parametrar. |
| [getDotCode()](#getDotCode--) | DotCode-parametrar. |
| [getFilledBars()](#getFilledBars--) | Hämtar ett värde som indikerar om staplar är fyllda. |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | GS1 Composite Bar-parametrar. |
| [getHanXin()](#getHanXin--) | HanXin-parametrar. |
| [getITF()](#getITF--) | ITF-parametrar. |
| [getMaxiCode()](#getMaxiCode--) | MaxiCode-parametrar. |
| [getPadding()](#getPadding--) | Streckkodspaddningar. |
| [getPatchCode()](#getPatchCode--) | PatchCode-parametrar. |
| [getPdf417()](#getPdf417--) | PDF417-parametrar. |
| [getPostal()](#getPostal--) | Postparametrar. |
| [getQR()](#getQR--) | QR-, MicroQR- och RectMicroQR-parametrar. |
| [getSupplement()](#getSupplement--) | Tilläggsparametrar. |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | Endast för 1D-streckkoder. |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | Förhållande mellan breda staplar och smala staplar. |
| [getXDimension()](#getXDimension--) | x-dimension är den minsta bredden på enheten för BarCode-staplar eller mellanslag. |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(Color value)](#setBarColor-java.awt.Color-) | Streckfärg. |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | Höjd på 1D-streckkods staplar i [Unit](../../com.aspose.barcode.generation/unit) värde. |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | Ställer in stapelns reduktionsvärde som används för att kompensera bläckspridning vid utskrift. |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | Visa alltid kontrollsiffran i den människoläsbara texten för Code128‑ och GS1Code128‑streckkoder. |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | Ställer in ett värde som indikerar om staplarna är fyllda. |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | GS1 Composite Bar-parametrar. |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | Endast för 1D-streckkoder. |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | Förhållande mellan breda staplar och smala staplar. |
| [setXDimension(Unit value)](#setXDimension-com.aspose.barcode.generation.Unit-) | x-dimension är den minsta bredden på enheten för BarCode-staplar eller mellanslag. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAustralianPost() {#getAustralianPost--}
```
public final AustralianPostParameters getAustralianPost()
```


AustralianPost-streckkodparametrar.

**Returns:**
[AustralianPostParameters](../../com.aspose.barcode.generation/australianpostparameters)
### getAztec() {#getAztec--}
```
public final AztecParameters getAztec()
```


Aztec-parametrar.

**Returns:**
[AztecParameters](../../com.aspose.barcode.generation/aztecparameters)
### getBarColor() {#getBarColor--}
```
public final Color getBarColor()
```


Stapelfärg. Standardvärde: Color.Black.

**Returns:**
java.awt.Color
### getBarHeight() {#getBarHeight--}
```
public final Unit getBarHeight()
```


Höjden på 1D-streckkods staplar i [Unit](../../com.aspose.barcode.generation/unit) värde. Ignoreras om  BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) egenskap är inställd på AutoSizeMode.Nearest eller AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


Hämta stapelns reduktionsvärde som används för att kompensera bläckspridning vid utskrift. Standardvärde: 0

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - bars reduction value that is used to compensate ink spread while printing.
### getChecksumAlwaysShow() {#getChecksumAlwaysShow--}
```
public final boolean getChecksumAlwaysShow()
```


Visa alltid kontrollsiffran i den människoläsbara texten för Code128‑ och GS1Code128‑streckkoder.

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


Codabar-parametrar.

**Returns:**
[CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)
### getCodablock() {#getCodablock--}
```
public final CodablockParameters getCodablock()
```


Codablock-parametrar.

**Returns:**
[CodablockParameters](../../com.aspose.barcode.generation/codablockparameters)
### getCode128() {#getCode128--}
```
public final Code128Parameters getCode128()
```


Code128-parametrar.

**Returns:**
[Code128Parameters](../../com.aspose.barcode.generation/code128parameters)
### getCode16K() {#getCode16K--}
```
public final Code16KParameters getCode16K()
```


Code16K-parametrar.

**Returns:**
[Code16KParameters](../../com.aspose.barcode.generation/code16kparameters)
### getCodeTextParameters() {#getCodeTextParameters--}
```
public final CodetextParameters getCodeTextParameters()
```


Codetextparametrar.

**Returns:**
[CodetextParameters](../../com.aspose.barcode.generation/codetextparameters)
### getCoupon() {#getCoupon--}
```
public final CouponParameters getCoupon()
```


Kupongparametrar. Används för UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

**Returns:**
[CouponParameters](../../com.aspose.barcode.generation/couponparameters)
### getDataBar() {#getDataBar--}
```
public final DataBarParameters getDataBar()
```


Databarparametrar.

**Returns:**
[DataBarParameters](../../com.aspose.barcode.generation/databarparameters)
### getDataMatrix() {#getDataMatrix--}
```
public final DataMatrixParameters getDataMatrix()
```


DataMatrix-parametrar.

**Returns:**
[DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)
### getDotCode() {#getDotCode--}
```
public final DotCodeParameters getDotCode()
```


DotCode-parametrar.

**Returns:**
[DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters)
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


Hämtar ett värde som indikerar om staplarna är fyllda. Endast för 1D-streckkoder. Standardvärde: true.

**Returns:**
boolean - ett värde som indikerar om staplarna är fyllda.
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


GS1 Composite Bar-parametrar.

Detta exempel visar hur man skapar och sparar en GS1 Composite Bar-bild. Observera att 1D-kodtext och 2D-kodtext separeras av symbolen '|'.

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


HanXin-parametrar.

**Returns:**
[HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)
### getITF() {#getITF--}
```
public final ITFParameters getITF()
```


ITF-parametrar.

**Returns:**
[ITFParameters](../../com.aspose.barcode.generation/itfparameters)
### getMaxiCode() {#getMaxiCode--}
```
public final MaxiCodeParameters getMaxiCode()
```


MaxiCode-parametrar.

**Returns:**
[MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)
### getPadding() {#getPadding--}
```
public final Padding getPadding()
```


Streckkodspaddning. Standardvärde: 5pt 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getPatchCode() {#getPatchCode--}
```
public final PatchCodeParameters getPatchCode()
```


PatchCode-parametrar.

**Returns:**
[PatchCodeParameters](../../com.aspose.barcode.generation/patchcodeparameters)
### getPdf417() {#getPdf417--}
```
public final Pdf417Parameters getPdf417()
```


PDF417-parametrar.

**Returns:**
[Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)
### getPostal() {#getPostal--}
```
public final PostalParameters getPostal()
```


Postparametrar. Används för Postnet, Planet.

**Returns:**
[PostalParameters](../../com.aspose.barcode.generation/postalparameters)
### getQR() {#getQR--}
```
public final QrParameters getQR()
```


QR-, MicroQR- och RectMicroQR-parametrar.

**Returns:**
[QrParameters](../../com.aspose.barcode.generation/qrparameters)
### getSupplement() {#getSupplement--}
```
public final SupplementParameters getSupplement()
```


Tilläggsparametrar. Används för Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

**Returns:**
[SupplementParameters](../../com.aspose.barcode.generation/supplementparameters)
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public final boolean getThrowExceptionWhenCodeTextIncorrect()
```


Endast för 1D-streckkoder. Om kodtexten är felaktig och värdet är satt till true - kastas ett undantag. Annars korrigeras kodtexten för att matcha streckkodens specifikation. Undantag kastas alltid för: Databar-symbologi om kodtexten är felaktig. Undantag kastas aldrig för: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128-symbologi om kodtexten är felaktig.

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public final float getWideNarrowRatio()
```


Förhållandet mellan breda och smala staplar. Standardvärde: 3, det vill säga att breda staplar är 3 gånger så breda som smala staplar. Används för ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public final Unit getXDimension()
```


x-dimension är den minsta bredden på enheten för BarCode-staplar eller mellanslag. Att öka detta kommer att öka hela streckkodsbildens bredd. Ignoreras om  BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) egenskap är inställd på AutoSizeMode.Nearest eller AutoSizeMode.Interpolation.

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


Aktivera kontrollsumma vid generering av 1D-streckkoder.

Standard behandlas som Ja för symbologi som måste innehålla kontrollsumma, och som Nej där kontrollsumma endast är möjlig.

Kontrollsumma är möjlig: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Kontrollsumma används alltid: Övrig symbologi

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


Stapelfärg. Standardvärde: Color.Black.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.awt.Color |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


Höjden på 1D-streckkods staplar i [Unit](../../com.aspose.barcode.generation/unit) värde. Ignoreras om  BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) egenskap är inställd på AutoSizeMode.Nearest eller AutoSizeMode.Interpolation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


Ställer in stapelns reduktionsvärde som används för att kompensera bläckspridning vid utskrift. Standardvärde: 0

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | stapelns reduktionsvärde som används för att kompensera bläckspridning vid utskrift. |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


Visa alltid kontrollsiffran i den människoläsbara texten för Code128‑ och GS1Code128‑streckkoder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


Aktivera kontrollsumma vid generering av 1D-streckkoder.

Standard behandlas som Ja för symbologi som måste innehålla kontrollsumma, och som Nej där kontrollsumma endast är möjlig.

Kontrollsumma är möjlig: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Kontrollsumma används alltid: Övrig symbologi

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


Ställer in ett värde som indikerar om staplarna är fyllda. Endast för 1D-streckkoder. Standardvärde: true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om staplarna är fyllda. |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


GS1 Composite Bar-parametrar.

Detta exempel visar hur man skapar och sparar en GS1 Composite Bar-bild. Observera att 1D-kodtext och 2D-kodtext separeras av symbolen '|'.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


Endast för 1D-streckkoder. Om kodtexten är felaktig och värdet är satt till true - kastas ett undantag. Annars korrigeras kodtexten för att matcha streckkodens specifikation. Undantag kastas alltid för: Databar-symbologi om kodtexten är felaktig. Undantag kastas aldrig för: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128-symbologi om kodtexten är felaktig.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


Förhållandet mellan breda och smala staplar. Standardvärde: 3, det vill säga att breda staplar är 3 gånger så breda som smala staplar. Används för ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


x-dimension är den minsta bredden på enheten för BarCode-staplar eller mellanslag. Att öka detta kommer att öka hela streckkodsbildens bredd. Ignoreras om  BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) egenskap är inställd på AutoSizeMode.Nearest eller AutoSizeMode.Interpolation.

**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

