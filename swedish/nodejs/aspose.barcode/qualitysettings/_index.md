---
title: "QualitySettings"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "QualitySettings möjliggör att konfigurera igenkänningskvalitet och hastighet manuellt."
type: docs
weight: 860
url: /sv/nodejs/aspose.barcode/qualitysettings/
---

## QualitySettings class

QualitySettings möjliggör att konfigurera igenkänningskvalitet och hastighet manuellt. Du kan snabbt ställa in QualitySettings med inbyggda förinställningar: HighPerformance, NormalQuality, HighQuality, MaxBarCodes eller så kan du manuellt konfigurera separata alternativ. Standardvärdet för QualitySettings är NormalQuality.

```js
new QualitySettings()
```

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getHighPerformance()](#gethighperformance) *(static)* | HighPerformance-igenkänningskvalitetsförinställning. Högkvalitativa streckkoder känns igen väl i detta läge. |
| [getHighQuality()](#gethighquality) *(static)* | HighQuality-igenkänningskvalitetsförinställning. Denna förinställning är utvecklad för streckkoder med låg kvalitet. |
| [getMaxQuality()](#getmaxquality) *(static)* | MaxQuality-igenkänningskvalitetsförinställning. Denna förinställning är utvecklad för att känna igen alla möjliga streckkoder, även felaktiga barco |
| [getNormalQuality()](#getnormalquality) *(static)* | NormalQuality-igenkänningskvalitetsförinställning. Lämplig för de flesta streckkoder |
| [getAllowIncorrectBarcodes()](#getallowincorrectbarcodes) | Tillåter motorn att känna igen streckkoder som har felaktig kontrollsumma eller felaktiga värden. Läget kan användas för att känna igen dam |
| [getBarcodeQuality()](#getbarcodequality) | Läge som möjliggör metoder att känna igen streckkodelement med den valda kvaliteten. Streckkodelement med lägre kvalitet r |
| [getComplexBackground()](#getcomplexbackground) | Läge som aktiverar eller inaktiverar ytterligare igenkänning av färgstreckkoder på färgbilder. |
| [getDeconvolution()](#getdeconvolution) | De­konvolution (bildåterställning) läge som definierar graden av bildnedbrytning. Ursprungligen är de­konvolution en funktion |
| [getInverseImage()](#getinverseimage) | Läge som aktiverar eller inaktiverar ytterligare igenkänning av streckkoder på bilder med inverterade färger (luminans). |
| [getMinimalXDimension()](#getminimalxdimension) | Minsta storlek för XDimension i pixlar som används med UseMinimalXDimension. |
| [getXDimension()](#getxdimension) | Igenkänningsläge som anger storlek (från 1 till oändlighet) för streckkodens minsta element: matriscell eller stapel. |
| [setAllowIncorrectBarcodes(value)](#setallowincorrectbarcodes) | Tillåter motorn att känna igen streckkoder som har felaktig kontrollsumma eller felaktiga värden. Läget kan användas för att känna igen dam |
| [setBarcodeQuality(value)](#setbarcodequality) | Läge som möjliggör metoder att känna igen streckkodelement med den valda kvaliteten. Streckkodelement med lägre kvalitet r |
| [setComplexBackground(value)](#setcomplexbackground) | Läge som aktiverar eller inaktiverar ytterligare igenkänning av färgstreckkoder på färgbilder. |
| [setDeconvolution(value)](#setdeconvolution) | De­konvolution (bildåterställning) läge som definierar graden av bildnedbrytning. Ursprungligen är de­konvolution en funktion |
| [setInverseImage(value)](#setinverseimage) | Läge som aktiverar eller inaktiverar ytterligare igenkänning av streckkoder på bilder med inverterade färger (luminans). |
| [setMinimalXDimension(value)](#setminimalxdimension) | Minsta storlek för XDimension i pixlar som används med UseMinimalXDimension. |
| [setXDimension(value)](#setxdimension) | Igenkänningsläge som anger storlek (från 1 till oändlighet) för streckkodens minsta element: matriscell eller stapel. |

### getHighPerformance() (static) {#gethighperformance}

HighPerformance-igenkänningskvalitetsförinställning. Högkvalitativa streckkoder känns igen väl i detta läge.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighPerformance());
```

### getHighQuality() (static) {#gethighquality}

HighQuality-igenkänningskvalitetsförinställning. Denna förinställning är utvecklad för streckkoder med låg kvalitet.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighQuality());
```

### getMaxQuality() (static) {#getmaxquality}

MaxQuality-igenkänningskvalitetsförinställning. Denna förinställning är utvecklad för att känna igen alla möjliga streckkoder, även felaktiga streckkoder. Detta exempel visar hur man använder MaxQuality-läget reader = new BarCodeReader("test.png"null, null, DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128); { reader.setQualitySettings(QualitySettings.getMaxQuality()); for(let i = 0; i < reader.readBarCodes().length; i++) echo (reader.getFoundBarcodes()[i].getCodeText()); } Värde: MaxQuality-igenkänningskvalitetsförinställning.

### getNormalQuality() (static) {#getnormalquality}

NormalQuality-igenkänningskvalitetsförinställning. Lämplig för de flesta streckkoder

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getNormalQuality());
```

### getAllowIncorrectBarcodes() {#getallowincorrectbarcodes}

Tillåter motorn att känna igen streckkoder som har felaktig kontrollsumma eller felaktiga värden. Läget kan användas för att känna igen skadade streckkoder med felaktig text.

**Returns:** Allows engine to recognize incorrect barcodes.

### getBarcodeQuality() {#getbarcodequality}

Läge som möjliggör metoder för att känna igen streckkodelement med den valda kvaliteten. Streckkodelement med lägre kvalitet kräver mer krävande metoder vilket saktar ner igenkänningen.

**Returns:** Mode which enables methods to recognize barcode elements with the selected quality.

### getComplexBackground() {#getcomplexbackground}

Läge som aktiverar eller inaktiverar ytterligare igenkänning av färgstreckkoder på färgbilder.

**Returns:** Additional recognition of color barcodes on color images.

### getDeconvolution() {#getdeconvolution}

Dekonvolution (bildåterställning) läge som definierar nivån av bildnedbrytning. Ursprungligen är dekonvolution en funktion som kan återställa en bild som har försämrats (konvolverats) av någon naturlig funktion som oskärpa, vid bildtagning med kamera. Eftersom vi inte kan upptäcka bildfunktionen som korroderar bilden, måste vi kontrollera de mest välkända funktionerna som skärpa eller matematisk morfologi.

**Returns:** Deconvolution mode which defines level of image degradation.

### getInverseImage() {#getinverseimage}

Läge som aktiverar eller inaktiverar ytterligare igenkänning av streckkoder på bilder med inverterade färger (luminans).

**Returns:** Additional recognition of barcodes on images with inverse colors

### getMinimalXDimension() {#getminimalxdimension}

Minsta storlek för XDimension i pixlar som används med UseMinimalXDimension.

**Returns:** Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

### getXDimension() {#getxdimension}

Igenkänningsläge som anger storlek (från 1 till oändlighet) för streckkodens minsta element: matriscell eller stapel.

**Returns:** size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

### setAllowIncorrectBarcodes(value) {#setallowincorrectbarcodes}

Tillåter motorn att känna igen streckkoder som har felaktig kontrollsumma eller felaktiga värden. Läget kan användas för att känna igen skadade streckkoder med felaktig text.

| Parameter | Beskrivning |
| --- | --- |
| värde | Tillåter motorn att känna igen felaktiga streckkoder. |

### setBarcodeQuality(value) {#setbarcodequality}

Läge som möjliggör metoder för att känna igen streckkodelement med den valda kvaliteten. Streckkodelement med lägre kvalitet kräver mer krävande metoder vilket saktar ner igenkänningen.

| Parameter | Beskrivning |
| --- | --- |
| värde | Läge som möjliggör metoder för att känna igen streckkodelement med den valda kvaliteten. |

### setComplexBackground(value) {#setcomplexbackground}

Läge som aktiverar eller inaktiverar ytterligare igenkänning av färgstreckkoder på färgbilder.

| Parameter | Beskrivning |
| --- | --- |
| värde | Ytterligare igenkänning av färgstreckkoder på färgbilder. |

### setDeconvolution(value) {#setdeconvolution}

Dekonvolution (bildåterställning) läge som definierar nivån av bildnedbrytning. Ursprungligen är dekonvolution en funktion som kan återställa en bild som har försämrats (konvolverats) av någon naturlig funktion som oskärpa, vid bildtagning med kamera. Eftersom vi inte kan upptäcka bildfunktionen som korroderar bilden, måste vi kontrollera de mest välkända funktionerna som skärpa eller matematisk morfologi.

| Parameter | Beskrivning |
| --- | --- |
| värde | Dekonvolutionsläge som definierar nivån av bildnedbrytning. |

### setInverseImage(value) {#setinverseimage}

Läge som aktiverar eller inaktiverar ytterligare igenkänning av streckkoder på bilder med inverterade färger (luminans).

| Parameter | Beskrivning |
| --- | --- |
| värde | Ytterligare igenkänning av streckkoder på bilder med inverterade färger |

### setMinimalXDimension(value) {#setminimalxdimension}

Minsta storlek för XDimension i pixlar som används med UseMinimalXDimension.

| Parameter | Beskrivning |
| --- | --- |
| värde | Minsta storlek för XDimension i pixlar som används med UseMinimalXDimension. |

### setXDimension(value) {#setxdimension}

Igenkänningsläge som anger storlek (från 1 till oändlighet) för streckkodens minsta element: matriscell eller stapel.

| Parameter | Beskrivning |
| --- | --- |
| värde | (från 1 till oändlighet) för streckkodens minsta element: matriscell eller stapel. |
