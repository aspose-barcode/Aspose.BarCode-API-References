---
title: "QualitySettings"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "QualitySettings maakt handmatige configuratie van herkenningskwaliteit en snelheid mogelijk."
type: docs
weight: 860
url: /nl/nodejs/aspose.barcode/qualitysettings/
---

## QualitySettings class

QualitySettings maakt handmatige configuratie van herkenningskwaliteit en snelheid mogelijk. U kunt QualitySettings snel instellen met ingebouwde presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes, of u kunt afzonderlijke opties handmatig configureren. Standaardwaarde van QualitySettings is NormalQuality.

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

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getHighPerformance()](#gethighperformance) *(static)* | HighPerformance herkenningskwaliteitspreset. Barcodes van hoge kwaliteit worden in deze modus goed herkend. |
| [getHighQuality()](#gethighquality) *(static)* | HighQuality herkenningskwaliteitspreset. Deze preset is ontwikkeld voor barcodes van lage kwaliteit. |
| [getMaxQuality()](#getmaxquality) *(static)* | MaxQuality herkenningskwaliteitspreset. Deze preset is ontwikkeld om alle mogelijke barcodes te herkennen, zelfs onjuiste barc |
| [getNormalQuality()](#getnormalquality) *(static)* | NormalQuality herkenningskwaliteitspreset. Geschikt voor de meeste barcodes |
| [getAllowIncorrectBarcodes()](#getallowincorrectbarcodes) | Staat de engine toe barcodes te herkennen met een onjuiste controlesom of onjuiste waarden. Modus kan worden gebruikt om beschadigde |
| [getBarcodeQuality()](#getbarcodequality) | Modus die methoden mogelijk maakt om barcode‑elementen te herkennen met de geselecteerde kwaliteit. Barcode‑element met lagere kwaliteit r |
| [getComplexBackground()](#getcomplexbackground) | Modus die extra herkenning van gekleurde barcodes op kleurafbeeldingen in- of uitschakelt. |
| [getDeconvolution()](#getdeconvolution) | Deconvolution (beeldherstel) modus die het niveau van beelddegradatie definieert. Oorspronkelijk is deconvolution een functie |
| [getInverseImage()](#getinverseimage) | Modus die extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren (luminantie) in- of uitschakelt. |
| [getMinimalXDimension()](#getminimalxdimension) | Minimale grootte van XDimension in pixels die wordt gebruikt met UseMinimalXDimension. |
| [getXDimension()](#getxdimension) | Herkenningsmodus die de grootte (van 1 tot oneindig) van het minimale barcode‑element instelt: matrixcel of balk. |
| [setAllowIncorrectBarcodes(value)](#setallowincorrectbarcodes) | Staat de engine toe barcodes te herkennen met een onjuiste controlesom of onjuiste waarden. Modus kan worden gebruikt om beschadigde |
| [setBarcodeQuality(value)](#setbarcodequality) | Modus die methoden mogelijk maakt om barcode‑elementen te herkennen met de geselecteerde kwaliteit. Barcode‑element met lagere kwaliteit r |
| [setComplexBackground(value)](#setcomplexbackground) | Modus die extra herkenning van gekleurde barcodes op kleurafbeeldingen in- of uitschakelt. |
| [setDeconvolution(value)](#setdeconvolution) | Deconvolution (beeldherstel) modus die het niveau van beelddegradatie definieert. Oorspronkelijk is deconvolution een functie |
| [setInverseImage(value)](#setinverseimage) | Modus die extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren (luminantie) in- of uitschakelt. |
| [setMinimalXDimension(value)](#setminimalxdimension) | Minimale grootte van XDimension in pixels die wordt gebruikt met UseMinimalXDimension. |
| [setXDimension(value)](#setxdimension) | Herkenningsmodus die de grootte (van 1 tot oneindig) van het minimale barcode‑element instelt: matrixcel of balk. |

### getHighPerformance() (static) {#gethighperformance}

HighPerformance herkenningskwaliteitspreset. Barcodes van hoge kwaliteit worden in deze modus goed herkend.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighPerformance());
```

### getHighQuality() (static) {#gethighquality}

HighQuality herkenningskwaliteitspreset. Deze preset is ontwikkeld voor barcodes van lage kwaliteit.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighQuality());
```

### getMaxQuality() (static) {#getmaxquality}

MaxQuality herkenningskwaliteitsvoorinstelling. Deze voorinstelling is ontwikkeld om alle mogelijke barcodes te herkennen, zelfs onjuiste barcodes. Deze voorbeeld toont hoe MaxQuality-modus te gebruiken reader = new BarCodeReader(\"test.png\"null, null, DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128); { reader.setQualitySettings(QualitySettings.getMaxQuality()); for(let i = 0; i < reader.readBarCodes().length; i++) echo (reader.getFoundBarcodes()[i].getCodeText()); } Waarde: MaxQuality herkenningskwaliteitsvoorinstelling.

### getNormalQuality() (static) {#getnormalquality}

NormalQuality herkenningskwaliteitspreset. Geschikt voor de meeste barcodes

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getNormalQuality());
```

### getAllowIncorrectBarcodes() {#getallowincorrectbarcodes}

Staat de engine toe barcodes te herkennen die een onjuiste controlesom of onjuiste waarden hebben. De modus kan worden gebruikt om beschadigde barcodes met onjuiste tekst te herkennen.

**Returns:** Allows engine to recognize incorrect barcodes.

### getBarcodeQuality() {#getbarcodequality}

Modus die methoden inschakelt om barcode‑elementen met de geselecteerde kwaliteit te herkennen. Een barcode‑element met lagere kwaliteit vereist meer intensieve methoden, waardoor de herkenning trager wordt.

**Returns:** Mode which enables methods to recognize barcode elements with the selected quality.

### getComplexBackground() {#getcomplexbackground}

Modus die extra herkenning van gekleurde barcodes op kleurafbeeldingen in- of uitschakelt.

**Returns:** Additional recognition of color barcodes on color images.

### getDeconvolution() {#getdeconvolution}

Deconvolutie (beeldherstel) modus die het niveau van beelddegradatie definieert. Oorspronkelijk is deconvolutie een functie die een door een natuurlijke functie, zoals vervaging, gedegradeerd (geconvolueerd) beeld kan herstellen, bijvoorbeeld bij het verkrijgen van een afbeelding met een camera. Omdat we de beeldfunctie die het beeld corrumpeert niet kunnen detecteren, moeten we de meest bekende functies zoals scherpte of wiskundige morfologie controleren.

**Returns:** Deconvolution mode which defines level of image degradation.

### getInverseImage() {#getinverseimage}

Modus die extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren (luminantie) in- of uitschakelt.

**Returns:** Additional recognition of barcodes on images with inverse colors

### getMinimalXDimension() {#getminimalxdimension}

Minimale grootte van XDimension in pixels die wordt gebruikt met UseMinimalXDimension.

**Returns:** Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

### getXDimension() {#getxdimension}

Herkenningsmodus die de grootte (van 1 tot oneindig) van het minimale barcode‑element instelt: matrixcel of balk.

**Returns:** size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

### setAllowIncorrectBarcodes(value) {#setallowincorrectbarcodes}

Staat de engine toe barcodes te herkennen die een onjuiste controlesom of onjuiste waarden hebben. De modus kan worden gebruikt om beschadigde barcodes met onjuiste tekst te herkennen.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Staat de engine toe onjuiste barcodes te herkennen. |

### setBarcodeQuality(value) {#setbarcodequality}

Modus die methoden inschakelt om barcode‑elementen met de geselecteerde kwaliteit te herkennen. Een barcode‑element met lagere kwaliteit vereist meer intensieve methoden, waardoor de herkenning trager wordt.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Modus die methoden inschakelt om barcode‑elementen met de geselecteerde kwaliteit te herkennen. |

### setComplexBackground(value) {#setcomplexbackground}

Modus die extra herkenning van gekleurde barcodes op kleurafbeeldingen in- of uitschakelt.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Extra herkenning van gekleurde barcodes op gekleurde afbeeldingen. |

### setDeconvolution(value) {#setdeconvolution}

Deconvolutie (beeldherstel) modus die het niveau van beelddegradatie definieert. Oorspronkelijk is deconvolutie een functie die een door een natuurlijke functie, zoals vervaging, gedegradeerd (geconvolueerd) beeld kan herstellen, bijvoorbeeld bij het verkrijgen van een afbeelding met een camera. Omdat we de beeldfunctie die het beeld corrumpeert niet kunnen detecteren, moeten we de meest bekende functies zoals scherpte of wiskundige morfologie controleren.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Deconvolutiemodus die het niveau van beelddegradatie definieert. |

### setInverseImage(value) {#setinverseimage}

Modus die extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren (luminantie) in- of uitschakelt.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Extra herkenning van barcodes op afbeeldingen met omgekeerde kleuren |

### setMinimalXDimension(value) {#setminimalxdimension}

Minimale grootte van XDimension in pixels die wordt gebruikt met UseMinimalXDimension.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Minimale grootte van XDimension in pixels die wordt gebruikt met UseMinimalXDimension. |

### setXDimension(value) {#setxdimension}

Herkenningsmodus die de grootte (van 1 tot oneindig) van het minimale barcode‑element instelt: matrixcel of balk.

| Parameter | Beschrijving |
| --- | --- |
| waarde | (van 1 tot oneindig) van het minimale barcode‑element: matrixcel of balk. |
