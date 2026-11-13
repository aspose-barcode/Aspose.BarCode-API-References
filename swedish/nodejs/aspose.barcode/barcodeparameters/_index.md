---
title: "BarcodeParameters"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Parametrar för streckkodsgenerering."
type: docs
weight: 140
url: /sv/nodejs/aspose.barcode/barcodeparameters/
---

## BarcodeParameters class

Parametrar för streckkodsgenerering.

```js
new BarcodeParameters()
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getAustralianPost()](#getaustralianpost) | AustralianPost streckkodparametrar. |
| [getAztec()](#getaztec) | Aztec‑parametrar. |
| [getBarColor()](#getbarcolor) | Streckfärgen. |
| [getBarHeight()](#getbarheight) | Höjden på 1D-streckkodernas streck i enhetsvärde. Ignoreras om egenskapen AutoSizeMode är satt till AutoSizeMode.NEAREST eller AutoSizeMo |
| [getBarWidthReduction()](#getbarwidthreduction) | Hämta reduktionsvärdet för strecken som används för att kompensera bläckspridning vid utskrift. |
| [getChecksumAlwaysShow()](#getchecksumalwaysshow) | Visa alltid kontrollsiffran i den människoläsbara texten för Code128‑ och GS1Code128‑streckkoder. |
| [getCodabar()](#getcodabar) | Codabar-parametrar. |
| [getCodablock()](#getcodablock) | Codablock-parametrar. |
| [getCode16K()](#getcode16k) | Code16K-parametrar. |
| [getCode128()](#getcode128) | Code128-parametrar. |
| [getCodeTextParameters()](#getcodetextparameters) | Kodtext‑parametrar. |
| [getCoupon()](#getcoupon) | Kupongparametrar. Används för UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [getDataBar()](#getdatabar) | Databar-parametrar. |
| [getDataMatrix()](#getdatamatrix) | DataMatrix-parametrar. |
| [getDotCode()](#getdotcode) | DotCode-parametrar. |
| [getEnableEscape()](#getenableescape) | Indikerar om tecknet \"\\\" förklaras som ett escape‑tecken i egenskapen CodeText. Används för Pdf417, DataMatrix, C |
| [getFilledBars()](#getfilledbars) | Hämtar ett värde som indikerar om strecken är fyllda. Endast för 1D‑streckkoder. Standardvärde: true. |
| [getGS1CompositeBar()](#getgs1compositebar) | GS1 Composite Bar‑parametrar. Detta exempel visar hur man skapar och sparar en GS1 Composite Bar‑bild. Observera att 1D‑kodtext |
| [getHanXin()](#gethanxin) | HanXin‑parametrar. |
| [getITF()](#getitf) | ITF-parametrar. |
| [getMaxiCode()](#getmaxicode) | MaxiCode-parametrar. |
| [getPadding()](#getpadding) | Streckkodspaddning. Standardvärde: 5pt 5pt 5pt 5pt. |
| [getPatchCode()](#getpatchcode) | PatchCode-parametrar. |
| [getPdf417()](#getpdf417) | PDF417‑parametrar. |
| [getPostal()](#getpostal) | Postparametrar. Används för Postnet, Planet. |
| [getQR()](#getqr) | QR-parametrar. |
| [getSupplement()](#getsupplement) | Kompletterande parametrar. Används för Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [getWideNarrowRatio()](#getwidenarrowratio) | Förhållandet mellan breda och smala streck. Standardvärde: 3, det vill säga att breda streck är 3 gånger så breda som smala streck. Används för ITF, |
| [getXDimension()](#getxdimension) | x-dimension är den minsta bredden på enheten för BarCode‑streck eller -mellanrum. Att öka detta kommer att öka hela streckkoden i |
| [isChecksumEnabled()](#ischecksumenabled) | Aktivera kontrollsumma vid generering av 1D‑streckkoder. Standard behandlas som Ja för symboler som måste innehålla kontrollsumma, som N |
| [setBarColor(value)](#setbarcolor) | Streckfärgen. |
| [setBarHeight()](#setbarheight) | Höjden på 1D-streckkodernas streck i enhetsvärde. Ignoreras om egenskapen AutoSizeMode är satt till AutoSizeMode.NEAREST eller AutoSizeMo |
| [setBarWidthReduction()](#setbarwidthreduction) | Ställer in reduktionsvärdet för strecken som används för att kompensera bläckspridning vid utskrift. |
| [setChecksumAlwaysShow()](#setchecksumalwaysshow) | Visa alltid kontrollsiffran i den människoläsbara texten för Code128‑ och GS1Code128‑streckkoder. |
| [setChecksumEnabled()](#setchecksumenabled) | Aktivera kontrollsumma vid generering av 1D‑streckkoder. Standard behandlas som Ja för symboler som måste innehålla kontrollsumma, som N |
| [setEnableEscape()](#setenableescape) | Indikerar om tecknet \"\\\" förklaras som ett escape‑tecken i egenskapen CodeText. Används för Pdf417, DataMatrix, C |
| [setFilledBars()](#setfilledbars) | Ställer in ett värde som indikerar om strecken är fyllda. Endast för 1D‑streckkoder. Standardvärde: true. |
| [setGS1CompositeBar()](#setgs1compositebar) | GS1 Composite Bar‑parametrar. Detta exempel visar hur man skapar och sparar en GS1 Composite Bar‑bild. Observera att 1D‑kodtext |
| [setPadding()](#setpadding) | Streckkodspaddning. Standardvärde: 5pt 5pt 5pt 5pt. |
| [setWideNarrowRatio()](#setwidenarrowratio) | Förhållandet mellan breda och smala streck. Standardvärde: 3, det vill säga att breda streck är 3 gånger så breda som smala streck. Används för ITF, P |
| [setXDimension()](#setxdimension) | x-dimension är den minsta bredden på enheten för BarCode‑streck eller -mellanrum. Att öka detta kommer att öka hela streckkoden i |

### getAustralianPost() {#getaustralianpost}

AustralianPost streckkodparametrar.

### getAztec() {#getaztec}

Aztec‑parametrar.

### getBarColor() {#getbarcolor}

Streckfärgen.

**Returns:** value of Bar color Default value: #000000

### getBarHeight() {#getbarheight}

Höjden på 1D‑streckkodernas streck i enhetsvärde. Ignoreras om egenskapen AutoSizeMode är satt till AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### getBarWidthReduction() {#getbarwidthreduction}

Hämta reduktionsvärdet för strecken som används för att kompensera bläckspridning vid utskrift.

**Returns:** Unit value of BarWidthReduction

### getChecksumAlwaysShow() {#getchecksumalwaysshow}

Visa alltid kontrollsiffran i den människoläsbara texten för Code128‑ och GS1Code128‑streckkoder.

### getCodabar() {#getcodabar}

Codabar-parametrar.

### getCodablock() {#getcodablock}

Codablock-parametrar.

### getCode16K() {#getcode16k}

Code16K-parametrar.

### getCode128() {#getcode128}

Code128-parametrar.

### getCodeTextParameters() {#getcodetextparameters}

Kodtext‑parametrar.

### getCoupon() {#getcoupon}

Kupongparametrar. Används för UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

### getDataBar() {#getdatabar}

Databar-parametrar.

### getDataMatrix() {#getdatamatrix}

DataMatrix-parametrar.

### getDotCode() {#getdotcode}

DotCode-parametrar.

### getEnableEscape() {#getenableescape}

Indikerar om tecknet \"\\\" förklaras som ett escape‑tecken i egenskapen CodeText. Används för Pdf417, DataMatrix, Code128 endast. Om EnableEscape är true kommer \"\\\" att förklaras som ett speciellt escape‑tecken. Annars fungerar \"\\\" som vanliga tecken. Aspose.BarCode stöder inmatning av decimala ascii‑koder och mnemonics för ASCII‑kontrollkodstecken. Till exempel, \\013 och \\CR står för CR.

### getFilledBars() {#getfilledbars}

Hämtar ett värde som indikerar om strecken är fyllda. Endast för 1D‑streckkoder. Standardvärde: true.

### getGS1CompositeBar() {#getgs1compositebar}

GS1 Composite Bar-parametrar. Detta exempel visar hur man skapar och sparar en GS1 Composite Bar-bild. Observera att 1D-kodtext och 2D-kodtext separeras av symbolen '/'

**Returns:** GS1CompositeBarParameters GS1 Composite Bar parameters.

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);
///
// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);
///
generator.save("test.png", BarcodeImageFormat.PNG);
```

### getHanXin() {#gethanxin}

HanXin‑parametrar.

### getITF() {#getitf}

ITF-parametrar.

### getMaxiCode() {#getmaxicode}

MaxiCode-parametrar.

### getPadding() {#getpadding}

Streckkodspaddning. Standardvärde: 5pt 5pt 5pt 5pt.

### getPatchCode() {#getpatchcode}

PatchCode-parametrar.

### getPdf417() {#getpdf417}

PDF417‑parametrar.

### getPostal() {#getpostal}

Postparametrar. Används för Postnet, Planet.

### getQR() {#getqr}

QR-parametrar.

### getSupplement() {#getsupplement}

Kompletterande parametrar. Används för Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

### getWideNarrowRatio() {#getwidenarrowratio}

Förhållandet mellan breda staplar och smala staplar. Standardvärde: 3, det vill säga att breda staplar är 3 gånger så breda som smala staplar. Används för ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. Parametervärdet WideNarrowRatio får inte vara mindre än eller lika med 0.

### getXDimension() {#getxdimension}

x-dimension är den minsta bredden på enheten för BarCode-staplar eller mellanslag. Att öka detta kommer att öka hela streckkodens bildbredd. Ignoreras om egenskapen AutoSizeMode är inställd på AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION.

### isChecksumEnabled() {#ischecksumenabled}

Aktivera kontrollsumma vid generering av 1D-streckkoder. Standard behandlas som Ja för symboler som måste innehålla kontrollsumma, och som Nej där kontrollsumma bara är möjlig. Kontrollsumma är möjlig för: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. Kontrollsumma används alltid för: övriga symboler.

### setBarColor(value) {#setbarcolor}

Streckfärgen.

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | String | för stapelfärg. Standardvärde: #000000. |

### setBarHeight() {#setbarheight}

Höjden på 1D‑streckkodernas streck i enhetsvärde. Ignoreras om egenskapen AutoSizeMode är satt till AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### setBarWidthReduction() {#setbarwidthreduction}

Ställer in reduktionsvärdet för strecken som används för att kompensera bläckspridning vid utskrift.

### setChecksumAlwaysShow() {#setchecksumalwaysshow}

Visa alltid kontrollsiffran i den människoläsbara texten för Code128‑ och GS1Code128‑streckkoder.

### setChecksumEnabled() {#setchecksumenabled}

Aktivera kontrollsumma vid generering av 1D-streckkoder. Standard behandlas som Ja för symboler som måste innehålla kontrollsumma, och som Nej där kontrollsumma bara är möjlig. Kontrollsumma är möjlig för: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. Kontrollsumma används alltid för: övriga symboler.

### setEnableEscape() {#setenableescape}

Anger om tecknet "\" ska tolkas som ett escape‑tecken i egenskapen CodeText. Används endast för Pdf417, DataMatrix, Code128. Om EnableEscape är true kommer "\" att tolkas som ett speciellt escape‑tecken. Annars fungerar "\" som vanliga tecken. Aspose.BarCode stödjer decimal‑ascii‑kod och mnemonik för ASCII‑kontrolltecken. Till exempel står \013 och \\CR för CR.

### setFilledBars() {#setfilledbars}

Ställer in ett värde som indikerar om strecken är fyllda. Endast för 1D‑streckkoder. Standardvärde: true.

### setGS1CompositeBar() {#setgs1compositebar}

GS1 Composite Bar-parametrar. Detta exempel visar hur man skapar och sparar en GS1 Composite Bar-bild. Observera att 1D-kodtext och 2D-kodtext separeras av symbolen '/'

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);

// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);

generator.save("test.png", BarcodeImageFormat.PNG);
```

### setPadding() {#setpadding}

Streckkodspaddning. Standardvärde: 5pt 5pt 5pt 5pt.

### setWideNarrowRatio() {#setwidenarrowratio}

Förhållandet mellan breda staplar och smala staplar. Standardvärde: 3, det vill säga att breda staplar är 3 gånger så breda som smala staplar. Används för ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. Parametervärdet WideNarrowRatio får inte vara mindre än eller lika med 0.

### setXDimension() {#setxdimension}

x-dimension är den minsta bredden på enheten för BarCode-staplar eller mellanslag. Att öka detta kommer att öka hela streckkodens bildbredd. Ignoreras om egenskapen AutoSizeMode är inställd på AutoSizeMode.NEAREST eller AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException
