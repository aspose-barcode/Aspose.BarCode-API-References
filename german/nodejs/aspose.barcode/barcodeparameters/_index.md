---
title: "BarcodeParameters"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Barcode-Generierungsparameter."
type: docs
weight: 140
url: /de/nodejs/aspose.barcode/barcodeparameters/
---

## BarcodeParameters class

Barcode-Generierungsparameter.

```js
new BarcodeParameters()
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getAustralianPost()](#getaustralianpost) | AustralianPost‑Barcode‑Parameter. |
| [getAztec()](#getaztec) | Aztec‑Parameter. |
| [getBarColor()](#getbarcolor) | Farbe der Balken. |
| [getBarHeight()](#getbarheight) | Höhe der Balken von 1D-Barcodes in Einheit. Ignoriert, wenn die Eigenschaft AutoSizeMode auf AutoSizeMode.NEAREST oder AutoSizeMo gesetzt ist. |
| [getBarWidthReduction()](#getbarwidthreduction) | Ermittelt den Reduktionswert der Balken, der verwendet wird, um die Tintenverbreitung beim Drucken auszugleichen. |
| [getChecksumAlwaysShow()](#getchecksumalwaysshow) | Zeigt immer die Prüfziffer im menschenlesbaren Text für Code128- und GS1Code128-Barcodes an. |
| [getCodabar()](#getcodabar) | Codabar-Parameter. |
| [getCodablock()](#getcodablock) | Codablock-Parameter. |
| [getCode16K()](#getcode16k) | Code16K-Parameter. |
| [getCode128()](#getcode128) | Code128-Parameter. |
| [getCodeTextParameters()](#getcodetextparameters) | Codetext-Parameter. |
| [getCoupon()](#getcoupon) | Coupon-Parameter. Verwendet für UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [getDataBar()](#getdatabar) | Databar-Parameter. |
| [getDataMatrix()](#getdatamatrix) | DataMatrix-Parameter. |
| [getDotCode()](#getdotcode) | DotCode-Parameter. |
| [getEnableEscape()](#getenableescape) | Gibt an, ob das Zeichen "\\" als Escape-Zeichen in der CodeText-Eigenschaft interpretiert wird. Wird für Pdf417, DataMatrix, C verwendet. |
| [getFilledBars()](#getfilledbars) | Liefert einen Wert, der angibt, ob Balken gefüllt sind. Nur für 1D-Barcodes. Standardwert: true. |
| [getGS1CompositeBar()](#getgs1compositebar) | GS1 Composite Bar-Parameter. Dieses Beispiel zeigt, wie man ein GS1 Composite Bar-Bild erstellt und speichert. Hinweis: Der 1D-Codetext |
| [getHanXin()](#gethanxin) | HanXin-Parameter. |
| [getITF()](#getitf) | ITF-Parameter. |
| [getMaxiCode()](#getmaxicode) | MaxiCode-Parameter. |
| [getPadding()](#getpadding) | Barcode-Abstände. Standardwert: 5pt 5pt 5pt 5pt. |
| [getPatchCode()](#getpatchcode) | PatchCode-Parameter. |
| [getPdf417()](#getpdf417) | PDF417-Parameter. |
| [getPostal()](#getpostal) | Postale Parameter. Verwendet für Postnet, Planet. |
| [getQR()](#getqr) | QR-Parameter. |
| [getSupplement()](#getsupplement) | Ergänzende Parameter. Verwendet für Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [getWideNarrowRatio()](#getwidenarrowratio) | Verhältnis von breiten zu schmalen Balken. Standardwert: 3, das heißt, breite Balken sind 3‑mal so breit wie schmale Balken. Wird für ITF verwendet, |
| [getXDimension()](#getxdimension) | x-Dimension ist die kleinste Breite der Einheit von BarCode-Balken oder -Lücken. Eine Erhöhung davon vergrößert den gesamten Barcode i |
| [isChecksumEnabled()](#ischecksumenabled) | Aktiviere Prüfsumme bei der Erzeugung von 1D-Barcodes. Standardmäßig wird dies als Ja behandelt für Symbologien, die eine Prüfsumme enthalten müssen, als N |
| [setBarColor(value)](#setbarcolor) | Farbe der Balken. |
| [setBarHeight()](#setbarheight) | Höhe der Balken von 1D-Barcodes in Einheit. Ignoriert, wenn die Eigenschaft AutoSizeMode auf AutoSizeMode.NEAREST oder AutoSizeMo gesetzt ist. |
| [setBarWidthReduction()](#setbarwidthreduction) | Setzt den Reduktionswert der Balken, der verwendet wird, um die Tintenverbreitung beim Drucken auszugleichen. |
| [setChecksumAlwaysShow()](#setchecksumalwaysshow) | Zeigt immer die Prüfziffer im menschenlesbaren Text für Code128- und GS1Code128-Barcodes an. |
| [setChecksumEnabled()](#setchecksumenabled) | Aktiviere Prüfsumme bei der Erzeugung von 1D-Barcodes. Standardmäßig wird dies als Ja behandelt für Symbologien, die eine Prüfsumme enthalten müssen, als N |
| [setEnableEscape()](#setenableescape) | Gibt an, ob das Zeichen "\\" als Escape-Zeichen in der CodeText-Eigenschaft interpretiert wird. Wird für Pdf417, DataMatrix, C verwendet. |
| [setFilledBars()](#setfilledbars) | Legt einen Wert fest, der angibt, ob Balken gefüllt sind. Nur für 1D-Strichcodes. Standardwert: true. |
| [setGS1CompositeBar()](#setgs1compositebar) | GS1 Composite Bar-Parameter. Dieses Beispiel zeigt, wie man ein GS1 Composite Bar-Bild erstellt und speichert. Hinweis: Der 1D-Codetext |
| [setPadding()](#setpadding) | Barcode-Abstände. Standardwert: 5pt 5pt 5pt 5pt. |
| [setWideNarrowRatio()](#setwidenarrowratio) | Verhältnis von breiten zu schmalen Balken. Standardwert: 3, das heißt, breite Balken sind dreimal so breit wie schmale Balken. Verwendet für ITF, P |
| [setXDimension()](#setxdimension) | x-Dimension ist die kleinste Breite der Einheit von BarCode-Balken oder -Lücken. Eine Erhöhung davon vergrößert den gesamten Barcode i |

### getAustralianPost() {#getaustralianpost}

AustralianPost‑Barcode‑Parameter.

### getAztec() {#getaztec}

Aztec‑Parameter.

### getBarColor() {#getbarcolor}

Farbe der Balken.

**Returns:** value of Bar color Default value: #000000

### getBarHeight() {#getbarheight}

Höhe der Balken von 1D-Strichcodes in Einheit. Ignoriert, wenn die Eigenschaft AutoSizeMode auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist.

**Throws:** BarcodeException

### getBarWidthReduction() {#getbarwidthreduction}

Ermittelt den Reduktionswert der Balken, der verwendet wird, um die Tintenverbreitung beim Drucken auszugleichen.

**Returns:** Unit value of BarWidthReduction

### getChecksumAlwaysShow() {#getchecksumalwaysshow}

Zeigt immer die Prüfziffer im menschenlesbaren Text für Code128- und GS1Code128-Barcodes an.

### getCodabar() {#getcodabar}

Codabar-Parameter.

### getCodablock() {#getcodablock}

Codablock-Parameter.

### getCode16K() {#getcode16k}

Code16K-Parameter.

### getCode128() {#getcode128}

Code128-Parameter.

### getCodeTextParameters() {#getcodetextparameters}

Codetext-Parameter.

### getCoupon() {#getcoupon}

Coupon-Parameter. Verwendet für UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon.

### getDataBar() {#getdatabar}

Databar-Parameter.

### getDataMatrix() {#getdatamatrix}

DataMatrix-Parameter.

### getDotCode() {#getdotcode}

DotCode-Parameter.

### getEnableEscape() {#getenableescape}

Gibt an, ob das Zeichen "\\" als Escape‑Zeichen in der Eigenschaft CodeText interpretiert wird. Wird nur für Pdf417, DataMatrix, Code128 verwendet. Wenn EnableEscape true ist, wird "\\" als spezielles Escape‑Zeichen erklärt. Andernfalls wirkt "\\" wie ein normales Zeichen. Aspose.BarCode unterstützt die Eingabe von dezimalen ASCII‑Codes und Mnemonics für ASCII‑Steuerzeichen. Zum Beispiel stehen \\013 und \\CR für CR.

### getFilledBars() {#getfilledbars}

Liefert einen Wert, der angibt, ob Balken gefüllt sind. Nur für 1D-Barcodes. Standardwert: true.

### getGS1CompositeBar() {#getgs1compositebar}

GS1 Composite Bar‑Parameter. Dieses Beispiel zeigt, wie man ein GS1 Composite Bar‑Bild erstellt und speichert. Hinweis: 1D‑Codetext und 2D‑Codetext werden durch das Symbol '/' getrennt.

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

HanXin-Parameter.

### getITF() {#getitf}

ITF-Parameter.

### getMaxiCode() {#getmaxicode}

MaxiCode-Parameter.

### getPadding() {#getpadding}

Barcode-Abstände. Standardwert: 5pt 5pt 5pt 5pt.

### getPatchCode() {#getpatchcode}

PatchCode-Parameter.

### getPdf417() {#getpdf417}

PDF417-Parameter.

### getPostal() {#getpostal}

Postale Parameter. Verwendet für Postnet, Planet.

### getQR() {#getqr}

QR-Parameter.

### getSupplement() {#getsupplement}

Ergänzende Parameter. Verwendet für Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN.

### getWideNarrowRatio() {#getwidenarrowratio}

Verhältnis von breiten zu schmalen Balken. Standardwert: 3, das heißt, breite Balken sind dreimal so breit wie schmale Balken. Verwendet für ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. Der Parameterwert WideNarrowRatio ist kleiner oder gleich 0.

### getXDimension() {#getxdimension}

Die x‑Dimension ist die kleinste Breite der Einheit von BarCode‑Balken oder -Lücken. Eine Erhöhung führt zu einer breiteren Barcode‑Bildbreite. Ignoriert, wenn die Eigenschaft AutoSizeMode auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist.

### isChecksumEnabled() {#ischecksumenabled}

Prüfsumme während der Erzeugung von 1D‑Barcodes aktivieren. Standardmäßig wird Yes für Symbologien verwendet, die zwingend eine Prüfsumme enthalten, und No, wo eine Prüfsumme nur optional ist. Prüfsumme möglich: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. Prüfsumme immer verwendet: übrige Symbologien.

### setBarColor(value) {#setbarcolor}

Farbe der Balken.

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | String | Für Balkenfarbe. Standardwert: #000000. |

### setBarHeight() {#setbarheight}

Höhe der Balken von 1D-Strichcodes in Einheit. Ignoriert, wenn die Eigenschaft AutoSizeMode auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist.

**Throws:** BarcodeException

### setBarWidthReduction() {#setbarwidthreduction}

Setzt den Reduktionswert der Balken, der verwendet wird, um die Tintenverbreitung beim Drucken auszugleichen.

### setChecksumAlwaysShow() {#setchecksumalwaysshow}

Zeigt immer die Prüfziffer im menschenlesbaren Text für Code128- und GS1Code128-Barcodes an.

### setChecksumEnabled() {#setchecksumenabled}

Prüfsumme während der Erzeugung von 1D‑Barcodes aktivieren. Standardmäßig wird Yes für Symbologien verwendet, die zwingend eine Prüfsumme enthalten, und No, wo eine Prüfsumme nur optional ist. Prüfsumme möglich: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar. Prüfsumme immer verwendet: übrige Symbologien.

### setEnableEscape() {#setenableescape}

Gibt an, ob das Zeichen "\\" als Escape‑Zeichen in der Eigenschaft CodeText interpretiert wird. Wird nur für Pdf417, DataMatrix, Code128 verwendet. Wenn EnableEscape true ist, wird "\\" als spezielles Escape‑Zeichen erklärt. Andernfalls wirkt "\\" wie ein normales Zeichen. Aspose.BarCode unterstützt den dezimalen ASCII‑Code und Mnemonics für ASCII‑Steuerzeichen. Zum Beispiel stehen \\013 und \\CR für CR.

### setFilledBars() {#setfilledbars}

Legt einen Wert fest, der angibt, ob Balken gefüllt sind. Nur für 1D-Strichcodes. Standardwert: true.

### setGS1CompositeBar() {#setgs1compositebar}

GS1 Composite Bar‑Parameter. Dieses Beispiel zeigt, wie man ein GS1 Composite Bar‑Bild erstellt und speichert. Hinweis: 1D‑Codetext und 2D‑Codetext werden durch das Symbol '/' getrennt.

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

Barcode-Abstände. Standardwert: 5pt 5pt 5pt 5pt.

### setWideNarrowRatio() {#setwidenarrowratio}

Verhältnis von breiten zu schmalen Balken. Standardwert: 3, das heißt, breite Balken sind dreimal so breit wie schmale Balken. Verwendet für ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard. Der Parameterwert WideNarrowRatio ist kleiner oder gleich 0.

### setXDimension() {#setxdimension}

Die x‑Dimension ist die kleinste Breite der Einheit von BarCode‑Balken oder -Lücken. Eine Erhöhung führt zu einer breiteren Barcode‑Bildbreite. Ignoriert, wenn die Eigenschaft AutoSizeMode auf AutoSizeMode.NEAREST oder AutoSizeMode.INTERPOLATION gesetzt ist.

**Throws:** BarcodeException
