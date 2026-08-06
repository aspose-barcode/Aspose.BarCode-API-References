---
title: BarcodeParameters
second_title: Aspose.BarCode for Android via Java API-referens
description: Parametrar för streckkodsgenerering.
type: docs
weight: 14
url: /sv/androidjava/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

Parametrar för streckkodsgenerering.
## Methods

| Method | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) |  |
| [getAustralianPost()](#getAustralianPost--) | AustralianPost-streckkodparametrar. |
| [getAztec()](#getAztec--) | Aztec-parametrar. |
| [getBarColor()](#getBarColor--) | Streckfärg. |
| [getBarHeight()](#getBarHeight--) | Höjd på staplar i 1D-streckkoder i [Unit](../../com.aspose.barcode.generation/unit)-värde. |
| [getBarWidthReduction()](#getBarWidthReduction--) | Hämta reduktionsvärde för staplar som används för att kompensera bläckspridning vid utskrift. |
| [getBarcodeType()](#getBarcodeType--) |  |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Visa alltid kontrollsiffra i den mänskligt läsbara texten för Code128- och GS1Code128-streckkoder. |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Codabar-parametrar. |
| [getCodablock()](#getCodablock--) | Codablock-parametrar. |
| [getCode128()](#getCode128--) | Code128-parametrar. |
| [getCode16K()](#getCode16K--) | Code16K-parametrar. |
| [getCodeText()](#getCodeText--) |  |
| [getCodeTextParameters()](#getCodeTextParameters--) | Kodtextparametrar. |
| [getComplexBarcode()](#getComplexBarcode--) |  |
| [getCoupon()](#getCoupon--) | Kupongparametrar. |
| [getDataBar()](#getDataBar--) | Databar-parametrar. |
| [getDataMatrix()](#getDataMatrix--) | DataMatrix-parametrar. |
| [getDotCode()](#getDotCode--) | DotCode-parametrar. |
| [getEnableEscape()](#getEnableEscape--) | Anger om tecknet "\" förklaras som ett escape‑tecken i egenskapen CodeText. |
| [getFilledBars()](#getFilledBars--) | Hämtar ett värde som indikerar om staplarna är fyllda. |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | GS1 Composite Bar‑parametrar. |
| [getHanXin()](#getHanXin--) | HanXin‑parametrar. |
| [getITF()](#getITF--) | ITF-parametrar. |
| [getMaxiCode()](#getMaxiCode--) | MaxiCode‑parametrar. |
| [getPadding()](#getPadding--) | Streckkodspaddningar. |
| [getPatchCode()](#getPatchCode--) | PatchCode‑parametrar. |
| [getPdf417()](#getPdf417--) | PDF417‑parametrar. |
| [getPostal()](#getPostal--) | Post‑parametrar. |
| [getQR()](#getQR--) | QR-, MicroQR- och RectMicroQR‑parametrar. |
| [getSupplement()](#getSupplement--) | Tilläggs‑parametrar. |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | Endast för 1D-streckkoder. |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | Förhållande mellan breda och smala staplar. |
| [getXDimension()](#getXDimension--) | x-dimensionen är den minsta bredden på enheten för BarCode‑staplar eller mellanslag. |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(int value)](#setBarColor-int-) | Streckfärg. |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | Höjd på staplar i 1D-streckkoder i [Unit](../../com.aspose.barcode.generation/unit)-värde. |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | Ställer in värdet för stapelreduktion som används för att kompensera bläckspridning vid utskrift. |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | Visa alltid kontrollsiffra i den mänskligt läsbara texten för Code128- och GS1Code128-streckkoder. |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setCodeText(String value)](#setCodeText-java.lang.String-) |  |
| [setEnableEscape(boolean value)](#setEnableEscape-boolean-) | Anger om tecknet "\" förklaras som ett escape‑tecken i egenskapen CodeText. |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | Ställer in ett värde som indikerar om staplarna är fyllda. |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | GS1 Composite Bar‑parametrar. |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | Endast för 1D-streckkoder. |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | Förhållande mellan breda och smala staplar. |
| [setXDimension(Unit value)](#setXDimension-com.aspose.barcode.generation.Unit-) | x-dimensionen är den minsta bredden på enheten för BarCode‑staplar eller mellanslag. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beskrivning |
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
public final int getBarColor()
```


Stapelfärg. Standardvärde: Color.Black.

**Returns:**
int
### getBarHeight() {#getBarHeight--}
```
public final Unit getBarHeight()
```


Höjden på 1D-streckkodernas staplar i [Unit](../../com.aspose.barcode.generation/unit) värde. Ignoreras om egenskapen BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) är inställd på AutoSizeMode.Nearest eller AutoSizeMode.Interpolation.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


Hämta stapelreduceringsvärdet som används för att kompensera bläckspridning vid utskrift. Standardvärde: 0

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


Visa alltid kontrollsiffra i den mänskligt läsbara texten för Code128- och GS1Code128-streckkoder.

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


Kodtextparametrar.

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


Kupongparametrar. Används för UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

**Returns:**
[CouponParameters](../../com.aspose.barcode.generation/couponparameters)
### getDataBar() {#getDataBar--}
```
public final DataBarParameters getDataBar()
```


Databar-parametrar.

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
### getEnableEscape() {#getEnableEscape--}
```
public final boolean getEnableEscape()
```


Anger om tecknet "\" förklaras som ett escape‑tecken i egenskapen CodeText. Används för Pdf417, DataMatrix, Code128 endast. Om EnableEscape är true kommer "\" att förklaras som ett speciellt escape‑tecken. Annars fungerar "\" som vanliga tecken.

Aspose.BarCode stödjer inmatning av decimala ascii‑koder och mnemonics för ASCII‑kontrollkodstecken. Till exempel, \\013 och \\\\CR står för CR.

**Returns:**
boolean
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


Hämtar ett värde som indikerar om staplarna är fyllda. Endast för 1D-streckkoder. Standardvärde: true.

**Returns:**
boolean – ett värde som indikerar om staplarna är fyllda.
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


GS1 Composite Bar‑parametrar.

Detta exempel visar hur man skapar och sparar en GS1 Composite Bar‑bild. Observera att 1D‑kodtext och 2D‑kodtext separeras med symbolen '|'

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


HanXin‑parametrar.

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


MaxiCode‑parametrar.

**Returns:**
[MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)
### getPadding() {#getPadding--}
```
public final Padding getPadding()
```


Streckkodspaddningar. Standardvärde: 5pt 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getPatchCode() {#getPatchCode--}
```
public final PatchCodeParameters getPatchCode()
```


PatchCode‑parametrar.

**Returns:**
[PatchCodeParameters](../../com.aspose.barcode.generation/patchcodeparameters)
### getPdf417() {#getPdf417--}
```
public final Pdf417Parameters getPdf417()
```


PDF417‑parametrar.

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


QR-, MicroQR- och RectMicroQR‑parametrar.

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


Endast för 1D-streckkoder. Om kodtexten är felaktig och värdet är satt till true kastas ett undantag. Annars korrigeras kodtexten för att matcha streckkodens specifikation. Undantag kastas alltid för: Databar‑symbolik om kodtexten är felaktig. Undantag kastas aldrig för: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128‑symbolik om kodtexten är felaktig.

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public final float getWideNarrowRatio()
```


Förhållande mellan breda och smala staplar. Standardvärde: 3, det vill säga att breda staplar är tre gånger så breda som smala staplar. Används för ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII.

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public final Unit getXDimension()
```


x-dimension är den minsta bredden på enheten för BarCode-staplar eller -mellanrum. Att öka detta kommer att öka hela streckkodens bildbredd. Ignoreras om BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) egenskapen är satt till AutoSizeMode.Nearest eller AutoSizeMode.Interpolation.

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


Aktivera kontrollsumma under generering av 1D-streckkoder.

Standardvärdet behandlas som Ja för symbologi som måste innehålla kontrollsumma, och som Nej där kontrollsumma bara är möjlig.

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




### setBarColor(int value) {#setBarColor-int-}
```
public final void setBarColor(int value)
```


Stapelfärg. Standardvärde: Color.Black.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


Höjden på 1D-streckkodernas staplar i [Unit](../../com.aspose.barcode.generation/unit) värde. Ignoreras om egenskapen BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) är inställd på AutoSizeMode.Nearest eller AutoSizeMode.Interpolation.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


Ställer in stapelreduceringsvärde som används för att kompensera bläckspridning vid utskrift. Standardvärde: 0

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | stapelreduceringsvärde som används för att kompensera bläckspridning vid utskrift. |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


Visa alltid kontrollsiffra i den mänskligt läsbara texten för Code128- och GS1Code128-streckkoder.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


Aktivera kontrollsumma under generering av 1D-streckkoder.

Standardvärdet behandlas som Ja för symbologi som måste innehålla kontrollsumma, och som Nej där kontrollsumma bara är möjlig.

Kontrollsumma är möjlig: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

Kontrollsumma används alltid: Övrig symbologi

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public final void setCodeText(String value)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setEnableEscape(boolean value) {#setEnableEscape-boolean-}
```
public final void setEnableEscape(boolean value)
```


Anger om tecknet "\" förklaras som ett escape‑tecken i egenskapen CodeText. Används för Pdf417, DataMatrix, Code128 endast. Om EnableEscape är true kommer "\" att förklaras som ett speciellt escape‑tecken. Annars fungerar "\" som vanliga tecken.

Aspose.BarCode stödjer inmatning av decimala ascii‑koder och mnemonics för ASCII‑kontrollkodstecken. Till exempel, \\013 och \\\\CR står för CR.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


Ställer in ett värde som indikerar om staplar är fyllda. Endast för 1D-streckkoder. Standardvärde: true.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om staplar är fyllda. |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


GS1 Composite Bar‑parametrar.

Detta exempel visar hur man skapar och sparar en GS1 Composite Bar‑bild. Observera att 1D‑kodtext och 2D‑kodtext separeras med symbolen '|'

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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


Endast för 1D-streckkoder. Om kodtexten är felaktig och värdet är satt till true kastas ett undantag. Annars korrigeras kodtexten för att matcha streckkodens specifikation. Undantag kastas alltid för: Databar‑symbolik om kodtexten är felaktig. Undantag kastas aldrig för: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128‑symbolik om kodtexten är felaktig.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


Förhållande mellan breda och smala staplar. Standardvärde: 3, det vill säga att breda staplar är tre gånger så breda som smala staplar. Används för ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII.

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


x-dimension är den minsta bredden på enheten för BarCode-staplar eller -mellanrum. Att öka detta kommer att öka hela streckkodens bildbredd. Ignoreras om BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) egenskapen är satt till AutoSizeMode.Nearest eller AutoSizeMode.Interpolation.

**Parameters:**
| Parameter | Type | Beskrivning |
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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

