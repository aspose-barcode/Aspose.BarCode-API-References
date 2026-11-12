---
title: "QualitySettings"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "QualitySettings ermöglicht die manuelle Konfiguration von Erkennungsqualität und -geschwindigkeit."
type: docs
weight: 860
url: /de/nodejs/aspose.barcode/qualitysettings/
---

## QualitySettings class

QualitySettings ermöglicht die manuelle Konfiguration von Erkennungsqualität und -geschwindigkeit. Sie können QualitySettings schnell über integrierte Voreinstellungen einrichten: HighPerformance, NormalQuality, HighQuality, MaxBarCodes, oder Sie können einzelne Optionen manuell konfigurieren. Der Standardwert von QualitySettings ist NormalQuality.

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

| Name | Beschreibung |
| --- | --- |
| [getHighPerformance()](#gethighperformance) *(static)* | HighPerformance-Erkennungsqualitätsvorgabe. Hochwertige Barcodes werden in diesem Modus gut erkannt. |
| [getHighQuality()](#gethighquality) *(static)* | HighQuality-Erkennungsqualitätsvorgabe. Diese Vorgabe ist für Barcodes niedriger Qualität entwickelt. |
| [getMaxQuality()](#getmaxquality) *(static)* | MaxQuality-Erkennungsqualitätsvorgabe. Diese Vorgabe ist entwickelt, um alle möglichen Barcodes zu erkennen, selbst fehlerhafte Barcodes. |
| [getNormalQuality()](#getnormalquality) *(static)* | NormalQuality-Erkennungsqualitätsvorgabe. Geeignet für die meisten Barcodes. |
| [getAllowIncorrectBarcodes()](#getallowincorrectbarcodes) | Ermöglicht der Engine, Barcodes mit falscher Prüfsumme oder falschen Werten zu erkennen. Der Modus kann verwendet werden, um beschädigte Barcodes zu erkennen. |
| [getBarcodeQuality()](#getbarcodequality) | Modus, der Methoden ermöglicht, Barcode-Elemente mit der ausgewählten Qualität zu erkennen. Barcode-Element mit niedrigerer Qualität r |
| [getComplexBackground()](#getcomplexbackground) | Modus, der die zusätzliche Erkennung von Farbcodes in Farbbildern aktiviert oder deaktiviert. |
| [getDeconvolution()](#getdeconvolution) | Deconvolution (Bildrestaurierung)-Modus, der das Niveau der Bilddegradation definiert. Ursprünglich ist Deconvolution eine Funktion |
| [getInverseImage()](#getinverseimage) | Modus, der die zusätzliche Erkennung von Barcodes auf Bildern mit invertierten Farben (Luminanz) aktiviert oder deaktiviert. |
| [getMinimalXDimension()](#getminimalxdimension) | Minimale Größe von XDimension in Pixeln, die mit UseMinimalXDimension verwendet wird. |
| [getXDimension()](#getxdimension) | Erkennungsmodus, der die Größe (von 1 bis unendlich) des minimalen Barcode-Elements festlegt: Matrixzelle oder Strich. |
| [setAllowIncorrectBarcodes(value)](#setallowincorrectbarcodes) | Ermöglicht der Engine, Barcodes mit falscher Prüfsumme oder falschen Werten zu erkennen. Der Modus kann verwendet werden, um beschädigte Barcodes zu erkennen. |
| [setBarcodeQuality(value)](#setbarcodequality) | Modus, der Methoden ermöglicht, Barcode-Elemente mit der ausgewählten Qualität zu erkennen. Barcode-Element mit niedrigerer Qualität r |
| [setComplexBackground(value)](#setcomplexbackground) | Modus, der die zusätzliche Erkennung von Farbcodes in Farbbildern aktiviert oder deaktiviert. |
| [setDeconvolution(value)](#setdeconvolution) | Deconvolution (Bildrestaurierung)-Modus, der das Niveau der Bilddegradation definiert. Ursprünglich ist Deconvolution eine Funktion |
| [setInverseImage(value)](#setinverseimage) | Modus, der die zusätzliche Erkennung von Barcodes auf Bildern mit invertierten Farben (Luminanz) aktiviert oder deaktiviert. |
| [setMinimalXDimension(value)](#setminimalxdimension) | Minimale Größe von XDimension in Pixeln, die mit UseMinimalXDimension verwendet wird. |
| [setXDimension(value)](#setxdimension) | Erkennungsmodus, der die Größe (von 1 bis unendlich) des minimalen Barcode-Elements festlegt: Matrixzelle oder Strich. |

### getHighPerformance() (static) {#gethighperformance}

HighPerformance-Erkennungsqualitätsvorgabe. Hochwertige Barcodes werden in diesem Modus gut erkannt.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighPerformance());
```

### getHighQuality() (static) {#gethighquality}

HighQuality-Erkennungsqualitätsvorgabe. Diese Vorgabe ist für Barcodes niedriger Qualität entwickelt.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighQuality());
```

### getMaxQuality() (static) {#getmaxquality}

MaxQuality-Erkennungsqualitätsvorgabe. Diese Vorgabe wurde entwickelt, um alle möglichen Barcodes zu erkennen, sogar fehlerhafte Barcodes. Dieses Beispiel zeigt, wie man den MaxQuality‑Modus verwendet reader = new BarCodeReader(\"test.png\"null, null, DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128); { reader.setQualitySettings(QualitySettings.getMaxQuality()); for(let i = 0; i < reader.readBarCodes().length; i++) echo (reader.getFoundBarcodes()[i].getCodeText()); } Wert: MaxQuality-Erkennungsqualitätsvorgabe.

### getNormalQuality() (static) {#getnormalquality}

NormalQuality-Erkennungsqualitätsvorgabe. Geeignet für die meisten Barcodes.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getNormalQuality());
```

### getAllowIncorrectBarcodes() {#getallowincorrectbarcodes}

Ermöglicht der Engine, Barcodes zu erkennen, die eine falsche Prüfsumme oder falsche Werte haben. Der Modus kann verwendet werden, um beschädigte Barcodes mit falschem Text zu erkennen.

**Returns:** Allows engine to recognize incorrect barcodes.

### getBarcodeQuality() {#getbarcodequality}

Modus, der Methoden aktiviert, um Barcode-Elemente mit der ausgewählten Qualität zu erkennen. Ein Barcode-Element mit niedrigerer Qualität erfordert aufwändigere Methoden, die die Erkennung verlangsamen.

**Returns:** Mode which enables methods to recognize barcode elements with the selected quality.

### getComplexBackground() {#getcomplexbackground}

Modus, der die zusätzliche Erkennung von Farbcodes in Farbbildern aktiviert oder deaktiviert.

**Returns:** Additional recognition of color barcodes on color images.

### getDeconvolution() {#getdeconvolution}

Deconvolution‑Modus (Bildrestaurierung), der das Niveau der Bilddegradation definiert. Ursprünglich ist Deconvolution eine Funktion, die ein durch eine natürliche Funktion wie Unschärfe degradierte (konvolutierte) Bild wiederherstellen kann, das beim Aufnehmen mit der Kamera entsteht. Da wir die Bildfunktion, die das Bild beschädigt, nicht erkennen können, müssen wir die am besten bekannten Funktionen wie Schärfen oder mathematische Morphologie prüfen.

**Returns:** Deconvolution mode which defines level of image degradation.

### getInverseImage() {#getinverseimage}

Modus, der die zusätzliche Erkennung von Barcodes auf Bildern mit invertierten Farben (Luminanz) aktiviert oder deaktiviert.

**Returns:** Additional recognition of barcodes on images with inverse colors

### getMinimalXDimension() {#getminimalxdimension}

Minimale Größe von XDimension in Pixeln, die mit UseMinimalXDimension verwendet wird.

**Returns:** Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

### getXDimension() {#getxdimension}

Erkennungsmodus, der die Größe (von 1 bis unendlich) des minimalen Barcode-Elements festlegt: Matrixzelle oder Strich.

**Returns:** size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

### setAllowIncorrectBarcodes(value) {#setallowincorrectbarcodes}

Ermöglicht der Engine, Barcodes zu erkennen, die eine falsche Prüfsumme oder falsche Werte haben. Der Modus kann verwendet werden, um beschädigte Barcodes mit falschem Text zu erkennen.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Ermöglicht der Engine, fehlerhafte Barcodes zu erkennen. |

### setBarcodeQuality(value) {#setbarcodequality}

Modus, der Methoden aktiviert, um Barcode-Elemente mit der ausgewählten Qualität zu erkennen. Ein Barcode-Element mit niedrigerer Qualität erfordert aufwändigere Methoden, die die Erkennung verlangsamen.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Modus, der Methoden aktiviert, um Barcode-Elemente mit der ausgewählten Qualität zu erkennen. |

### setComplexBackground(value) {#setcomplexbackground}

Modus, der die zusätzliche Erkennung von Farbcodes in Farbbildern aktiviert oder deaktiviert.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Zusätzliche Erkennung von Farbcodes auf Farbbildern. |

### setDeconvolution(value) {#setdeconvolution}

Deconvolution‑Modus (Bildrestaurierung), der das Niveau der Bilddegradation definiert. Ursprünglich ist Deconvolution eine Funktion, die ein durch eine natürliche Funktion wie Unschärfe degradierte (konvolutierte) Bild wiederherstellen kann, das beim Aufnehmen mit der Kamera entsteht. Da wir die Bildfunktion, die das Bild beschädigt, nicht erkennen können, müssen wir die am besten bekannten Funktionen wie Schärfen oder mathematische Morphologie prüfen.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Deconvolution‑Modus, der das Niveau der Bilddegradation definiert. |

### setInverseImage(value) {#setinverseimage}

Modus, der die zusätzliche Erkennung von Barcodes auf Bildern mit invertierten Farben (Luminanz) aktiviert oder deaktiviert.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Zusätzliche Erkennung von Barcodes auf Bildern mit invertierten Farben |

### setMinimalXDimension(value) {#setminimalxdimension}

Minimale Größe von XDimension in Pixeln, die mit UseMinimalXDimension verwendet wird.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Minimale Größe von XDimension in Pixeln, die mit UseMinimalXDimension verwendet wird. |

### setXDimension(value) {#setxdimension}

Erkennungsmodus, der die Größe (von 1 bis unendlich) des minimalen Barcode-Elements festlegt: Matrixzelle oder Strich.

| Parameter | Beschreibung |
| --- | --- |
| Wert | (von 1 bis unendlich) des minimalen Barcode-Elements: Matrixzelle oder Strich. |
