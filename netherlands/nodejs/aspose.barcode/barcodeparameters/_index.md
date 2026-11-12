---
title: "BarcodeParameters"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Barcode-generatieparameters."
type: docs
weight: 140
url: /nl/nodejs/aspose.barcode/barcodeparameters/
---

## BarcodeParameters class

Barcode-generatieparameters.

```js
new BarcodeParameters()
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getAustralianPost()](#getaustralianpost) | AustralianPost‑barcode‑parameters. |
| [getAztec()](#getaztec) | Aztec‑parameters. |
| [getBarColor()](#getbarcolor) | Kleur van de staven. |
| [getBarHeight()](#getbarheight) | Hoogte van de staven van 1D-barcodes in eenheidwaarde. Genegeerd als de AutoSizeMode-eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMo |
| [getBarWidthReduction()](#getbarwidthreduction) | Haalt de reductiewaarde van de staven op die wordt gebruikt om inktverspreiding tijdens het afdrukken te compenseren. |
| [getChecksumAlwaysShow()](#getchecksumalwaysshow) | Toon altijd het controlecijfer in de menselijk leesbare tekst voor Code128- en GS1Code128-barcodes. |
| [getCodabar()](#getcodabar) | Codabar-parameters. |
| [getCodablock()](#getcodablock) | Codablock-parameters. |
| [getCode16K()](#getcode16k) | Code16K-parameters. |
| [getCode128()](#getcode128) | Code128-parameters. |
| [getCodeTextParameters()](#getcodetextparameters) | Codetekst‑parameters. |
| [getCoupon()](#getcoupon) | Coupon‑parameters. Gebruikt voor UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [getDataBar()](#getdatabar) | Databar-parameters. |
| [getDataMatrix()](#getdatamatrix) | DataMatrix-parameters. |
| [getDotCode()](#getdotcode) | DotCode parameters. |
| [getEnableEscape()](#getenableescape) | Geeft aan of het teken "\\" wordt uitgelegd als een escape‑teken in de CodeText‑eigenschap. Gebruikt voor Pdf417, DataMatrix, C |
| [getFilledBars()](#getfilledbars) | Haalt een waarde op die aangeeft of de staven gevuld zijn. Alleen voor 1D-barcodes. Standaardwaarde: true. |
| [getGS1CompositeBar()](#getgs1compositebar) | GS1 Composite Bar parameters. Dit voorbeeld toont hoe een GS1 Composite Bar‑afbeelding te maken en op te slaan. Merk op dat 1D-codetext |
| [getHanXin()](#gethanxin) | HanXin parameters. |
| [getITF()](#getitf) | ITF parameters. |
| [getMaxiCode()](#getmaxicode) | MaxiCode parameters. |
| [getPadding()](#getpadding) | Barcode‑opvulling. Standaardwaarde: 5pt 5pt 5pt 5pt. |
| [getPatchCode()](#getpatchcode) | PatchCode-parameters. |
| [getPdf417()](#getpdf417) | PDF417-parameters. |
| [getPostal()](#getpostal) | Postale parameters. Gebruikt voor Postnet, Planet. |
| [getQR()](#getqr) | QR-parameters. |
| [getSupplement()](#getsupplement) | Supplement-parameters. Gebruikt voor Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [getWideNarrowRatio()](#getwidenarrowratio) | Verhouding brede staven tot smalle staven. Standaardwaarde: 3, dat wil zeggen, brede staven zijn 3 keer zo breed als smalle staven. Gebruikt voor ITF, |
| [getXDimension()](#getxdimension) | x-dimensie is de kleinste breedte van de eenheid van BarCode-staven of -spaties. Verhogen hiervan zal de volledige barcode i |
| [isChecksumEnabled()](#ischecksumenabled) | Schakel controlecijfer in tijdens het genereren van 1D-barcodes. Standaard wordt dit behandeld als Ja voor symbologie die een controlecijfer moet bevatten, als N |
| [setBarColor(value)](#setbarcolor) | Kleur van de staven. |
| [setBarHeight()](#setbarheight) | Hoogte van de staven van 1D-barcodes in eenheidwaarde. Genegeerd als de AutoSizeMode-eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMo |
| [setBarWidthReduction()](#setbarwidthreduction) | Stelt de reductiewaarde van de staven in die wordt gebruikt om inktverspreiding tijdens het afdrukken te compenseren. |
| [setChecksumAlwaysShow()](#setchecksumalwaysshow) | Toon altijd het controlecijfer in de menselijk leesbare tekst voor Code128- en GS1Code128-barcodes. |
| [setChecksumEnabled()](#setchecksumenabled) | Schakel controlecijfer in tijdens het genereren van 1D-barcodes. Standaard wordt dit behandeld als Ja voor symbologie die een controlecijfer moet bevatten, als N |
| [setEnableEscape()](#setenableescape) | Geeft aan of het teken "\\" wordt uitgelegd als een escape‑teken in de CodeText‑eigenschap. Gebruikt voor Pdf417, DataMatrix, C |
| [setFilledBars()](#setfilledbars) | Stelt een waarde in die aangeeft of de staven gevuld zijn. Alleen voor 1D-barcodes. Standaardwaarde: true. |
| [setGS1CompositeBar()](#setgs1compositebar) | GS1 Composite Bar parameters. Dit voorbeeld toont hoe een GS1 Composite Bar‑afbeelding te maken en op te slaan. Merk op dat 1D-codetext |
| [setPadding()](#setpadding) | Barcode‑opvulling. Standaardwaarde: 5pt 5pt 5pt 5pt. |
| [setWideNarrowRatio()](#setwidenarrowratio) | Verhouding brede staven tot smalle staven. Standaardwaarde: 3, dat wil zeggen, brede staven zijn 3 keer zo breed als smalle staven. Gebruikt voor ITF, P |
| [setXDimension()](#setxdimension) | x-dimensie is de kleinste breedte van de eenheid van BarCode-staven of -spaties. Verhogen hiervan zal de volledige barcode i |

### getAustralianPost() {#getaustralianpost}

AustralianPost‑barcode‑parameters.

### getAztec() {#getaztec}

Aztec‑parameters.

### getBarColor() {#getbarcolor}

Kleur van de staven.

**Returns:** value of Bar color Default value: #000000

### getBarHeight() {#getbarheight}

Hoogte van de staven van 1D-barcodes in eenheidwaarde. Genegeerd als de AutoSizeMode‑eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### getBarWidthReduction() {#getbarwidthreduction}

Haalt de reductiewaarde van de staven op die wordt gebruikt om inktverspreiding tijdens het afdrukken te compenseren.

**Returns:** Unit value of BarWidthReduction

### getChecksumAlwaysShow() {#getchecksumalwaysshow}

Toon altijd het controlecijfer in de menselijk leesbare tekst voor Code128- en GS1Code128-barcodes.

### getCodabar() {#getcodabar}

Codabar-parameters.

### getCodablock() {#getcodablock}

Codablock-parameters.

### getCode16K() {#getcode16k}

Code16K-parameters.

### getCode128() {#getcode128}

Code128-parameters.

### getCodeTextParameters() {#getcodetextparameters}

Codetekst‑parameters.

### getCoupon() {#getcoupon}

Coupon‑parameters. Gebruikt voor UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

### getDataBar() {#getdatabar}

Databar-parameters.

### getDataMatrix() {#getdatamatrix}

DataMatrix-parameters.

### getDotCode() {#getdotcode}

DotCode parameters.

### getEnableEscape() {#getenableescape}

Geeft aan of het teken "\\" wordt uitgelegd als een escape‑teken in de CodeText‑eigenschap. Gebruikt voor Pdf417, DataMatrix, Code128 alleen. Als EnableEscape true is, zal "\\" worden uitgelegd als een speciaal escape‑teken. Anders functioneert "\\" als normale tekens. Aspose.BarCode ondersteunt het invoeren van decimale ascii‑code en mnemonic voor ASCII‑besturingscode‑tekens. Bijvoorbeeld, \013 en \\CR staan voor CR.

### getFilledBars() {#getfilledbars}

Haalt een waarde op die aangeeft of de staven gevuld zijn. Alleen voor 1D-barcodes. Standaardwaarde: true.

### getGS1CompositeBar() {#getgs1compositebar}

GS1 Composite Bar parameters. Dit voorbeeld toont hoe een GS1 Composite Bar‑afbeelding te maken en op te slaan. Merk op dat 1D-codetext en 2D-codetext gescheiden worden door het symbool '/'

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

HanXin parameters.

### getITF() {#getitf}

ITF parameters.

### getMaxiCode() {#getmaxicode}

MaxiCode parameters.

### getPadding() {#getpadding}

Barcode‑opvulling. Standaardwaarde: 5pt 5pt 5pt 5pt.

### getPatchCode() {#getpatchcode}

PatchCode-parameters.

### getPdf417() {#getpdf417}

PDF417-parameters.

### getPostal() {#getpostal}

Postale parameters. Gebruikt voor Postnet, Planet.

### getQR() {#getqr}

QR-parameters.

### getSupplement() {#getsupplement}

Supplement-parameters. Gebruikt voor Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

### getWideNarrowRatio() {#getwidenarrowratio}

Verhouding brede staven tot smalle staven. Standaardwaarde: 3, dat wil zeggen, brede staven zijn 3 keer zo breed als smalle staven. Gebruikt voor ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. De WideNarrowRatio‑parameterwaarde is kleiner dan of gelijk aan 0.

### getXDimension() {#getxdimension}

x-dimensie is de kleinste breedte van de eenheid van BarCode-staven of -spaties. Verhogen hiervan zal de volledige barcode‑afbeeldingsbreedte vergroten. Genegeerd als de AutoSizeMode‑eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION.

### isChecksumEnabled() {#ischecksumenabled}

Schakel controlegetal in tijdens het genereren van 1D-barcodes. Standaard wordt dit behandeld als Ja voor symbologieën die een controlegetal moeten bevatten, en als Nee waar een controlegetal alleen mogelijk is. Controlegetal is mogelijk: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. Controlegetal wordt altijd gebruikt: overige symbologieën

### setBarColor(value) {#setbarcolor}

Kleur van de staven.

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | String | voor de balkkleur Standaardwaarde: #000000. |

### setBarHeight() {#setbarheight}

Hoogte van de staven van 1D-barcodes in eenheidwaarde. Genegeerd als de AutoSizeMode‑eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException

### setBarWidthReduction() {#setbarwidthreduction}

Stelt de reductiewaarde van de staven in die wordt gebruikt om inktverspreiding tijdens het afdrukken te compenseren.

### setChecksumAlwaysShow() {#setchecksumalwaysshow}

Toon altijd het controlecijfer in de menselijk leesbare tekst voor Code128- en GS1Code128-barcodes.

### setChecksumEnabled() {#setchecksumenabled}

Schakel controlegetal in tijdens het genereren van 1D-barcodes. Standaard wordt dit behandeld als Ja voor symbologieën die een controlegetal moeten bevatten, en als Nee waar een controlegetal alleen mogelijk is. Controlegetal is mogelijk: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. Controlegetal wordt altijd gebruikt: overige symbologieën

### setEnableEscape() {#setenableescape}

Geeft aan of het teken "\" wordt uitgelegd als een escape‑teken in de CodeText‑eigenschap. Alleen gebruikt voor Pdf417, DataMatrix, Code128. Als EnableEscape waar is, wordt "\" uitgelegd als een speciaal escape‑teken. Anders functioneert "\" als gewone tekens. Aspose.BarCode ondersteunt de decimale ascii‑code en mnemonic voor ASCII‑besturingscode‑tekens. Bijvoorbeeld, \013 en \\CR staan voor CR.

### setFilledBars() {#setfilledbars}

Stelt een waarde in die aangeeft of de staven gevuld zijn. Alleen voor 1D-barcodes. Standaardwaarde: true.

### setGS1CompositeBar() {#setgs1compositebar}

GS1 Composite Bar parameters. Dit voorbeeld toont hoe een GS1 Composite Bar‑afbeelding te maken en op te slaan. Merk op dat 1D-codetext en 2D-codetext gescheiden worden door het symbool '/'

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

Barcode‑opvulling. Standaardwaarde: 5pt 5pt 5pt 5pt.

### setWideNarrowRatio() {#setwidenarrowratio}

Verhouding brede strepen tot smalle strepen. Standaardwaarde: 3, dat wil zeggen, brede strepen zijn 3 keer zo breed als smalle strepen. Gebruikt voor ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. De parameterwaarde WideNarrowRatio is kleiner dan of gelijk aan 0.

### setXDimension() {#setxdimension}

x-dimensie is de kleinste breedte van de eenheid van BarCode-staven of -spaties. Verhogen hiervan zal de volledige barcode‑afbeeldingsbreedte vergroten. Genegeerd als de AutoSizeMode‑eigenschap is ingesteld op AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION.

**Throws:** BarcodeException
