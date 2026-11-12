---
title: "BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "BarCodeReader kapselt ein Bild, das einen oder mehrere Barcodes enthalten kann, und kann anschließend die Operation ReadBarCodes ausführen, um Barcodes zu erkennen."
type: docs
weight: 90
url: /de/nodejs/aspose.barcode/barcodereader/
---

## BarCodeReader class

BarCodeReader kapselt ein Bild, das einen oder mehrere Barcodes enthalten kann, und kann anschließend die Operation ReadBarCodes ausführen, um Barcodes zu erkennen.

```js
new BarCodeReader(image, areas, decodeTypes)
```

Initialisiert eine neue Instanz von BarCodeReader

| Parameter | Beschreibung |
| --- | --- |
| Bild | kodiert als Base64‑String oder Pfad zum Bild |
| Bereiche | Array von Objekten vom Typ Rectangle |
| decodeTypes | das Array von Objekten nach DecodeType |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader("test.png", null,  [DecodeType.CODE_39, DecodeType.CODE_128]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [importFromXml(xmlFile)](#importfromxml) *(static)* | Exportiert BarCode-Eigenschaften in die angegebene XML-Datei |
| [containsAny()](#containsany) | Bestimmt, ob einer der angegebenen Dekodierungstypen enthalten ist |
| [exportToXml(xmlFile)](#exporttoxml) | Exportiert BarCode-Eigenschaften in die angegebene XML-Datei |
| [getBarCodeReadType()](#getbarcodereadtype) | Ermittelt den Dekodierungstyp der Eingabe-Barcode-Dekodierung |
| [getBarcodeSettings()](#getbarcodesettings) | Die Haupt-Barcode-Dekodierungsparameter. Enthält Parameter, die Einfluss auf erkannte Daten haben. |
| [getFoundBarCodes()](#getfoundbarcodes) | Ermittelt das erkannte BarCodeResult-Array |
| [getFoundCount()](#getfoundcount) | Ermittelt die Anzahl erkannter Barcodes |
| [getQualitySettings()](#getqualitysettings) | QualitySettings ermöglicht die manuelle Konfiguration von Erkennungsqualität und -geschwindigkeit. Sie können QualitySettings schnell einrichten, indem Sie ... |
| [getTimeout()](#gettimeout) | Ermittelt den Timeout des Erkennungsprozesses in Millisekunden. |
| [readBarCodes()](#readbarcodes) | Liest BarCodeResult aus dem Bild. |
| [setBarCodeImage(imageResource, …areas)](#setbarcodeimage) | Setzt das Bitmap-Bild und die Bereiche für die Erkennung. Muss vor der Methode ReadBarCodes() aufgerufen werden. |
| [setBarCodeReadType(…types)](#setbarcodereadtype) | Setzt das SingleDecodeType-Typ-Array für die Erkennung. Muss vor der Methode readBarCodes() aufgerufen werden. |
| [setQualitySettings()](#setqualitysettings) | QualitySettings ermöglicht die manuelle Konfiguration von Erkennungsqualität und -geschwindigkeit. Sie können QualitySettings schnell einrichten, indem Sie ... |
| [setTimeout(value)](#settimeout) | Setzt den Timeout des Erkennungsprozesses in Millisekunden. |

### importFromXml(xmlFile) (static) {#importfromxml}

Exportiert BarCode-Eigenschaften in die angegebene XML-Datei

| Parameter | Beschreibung |
| --- | --- |
| xmlFile | Der Name der Datei |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### containsAny() {#containsany}

Bestimmt, ob einer der angegebenen Dekodierungstypen enthalten ist

| Parameter | Beschreibung |
| --- | --- |
| ...decodeTypes | Typen zum Überprüfen. |

**Returns:** bool Value is a true if any types are included into.

### exportToXml(xmlFile) {#exporttoxml}

Exportiert BarCode-Eigenschaften in die angegebene XML-Datei

| Parameter | Beschreibung |
| --- | --- |
| xmlFile | Der Name der Datei |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### getBarCodeReadType() {#getbarcodereadtype}

Ermittelt den Dekodierungstyp der Eingabe-Barcode-Dekodierung

**Returns:** *

### getBarcodeSettings() {#getbarcodesettings}

Die Haupt-Barcode-Dekodierungsparameter. Enthält Parameter, die Einfluss auf erkannte Daten haben.

**Returns:** The main BarCode decoding parameters

### getFoundBarCodes() {#getfoundbarcodes}

Ermittelt das erkannte BarCodeResult-Array

**Returns:** recognized BarCodeResult array

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " +  reader.getFoundBarCodes()[i].getCodeText());
```

### getFoundCount() {#getfoundcount}

Ermittelt die Anzahl erkannter Barcodes

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
Value: The recognized barcodes count
```

### getQualitySettings() {#getqualitysettings}

QualitySettings ermöglicht die manuelle Konfiguration von Erkennungsqualität und -geschwindigkeit. Sie können QualitySettings schnell über integrierte Voreinstellungen einrichten: HighPerformance, NormalQuality, HighQuality, MaxBarCodes, oder Sie können einzelne Optionen manuell konfigurieren. Der Standardwert von QualitySettings ist NormalQuality.

**Returns:** QualitySettings to configure recognition quality and speed.

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader

let reader = new BarCodeReader("test.png", null, null);
 //set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### getTimeout() {#gettimeout}

Ermittelt den Timeout des Erkennungsprozesses in Millisekunden.

**Returns:** The timeout.

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### readBarCodes() {#readbarcodes}

Liest BarCodeResult aus dem Bild.

**Returns:** Returns array of recognized `BarCodeResult`s on the image. If nothing is recognized, zero array is returned.

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
```

### setBarCodeImage(imageResource, …areas) {#setbarcodeimage}

Setzt das Bitmap-Bild und die Bereiche für die Erkennung. Muss vor der Methode ReadBarCodes() aufgerufen werden.

| Parameter | Beschreibung |
| --- | --- |
| imageResource | Das Bild für die Erkennung. |
| Bereiche | Bereichsliste für die Erkennung |

**Throws:** BarcodeException

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let bmp = "test.png";
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
var img = new Image();
img.src = 'path_to_image';
width = img.width;
height = img.height;
reader.setBarCodeImage(bmp, new Rectangle[] { new Rectangle(0, 0, width, height) });
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setBarCodeReadType(…types) {#setbarcodereadtype}

Setzt das SingleDecodeType-Typ-Array für die Erkennung. Muss vor der Methode readBarCodes() aufgerufen werden.

| Parameter | Beschreibung |
| --- | --- |
| types | Das SingleDecodeType-Typ-Array zum Lesen. |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.setBarCodeImage("test.png");
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setQualitySettings() {#setqualitysettings}

QualitySettings ermöglicht die manuelle Konfiguration von Erkennungsqualität und -geschwindigkeit. Sie können QualitySettings schnell über integrierte Voreinstellungen einrichten: HighPerformance, NormalQuality, HighQuality, MaxBarCodes, oder Sie können einzelne Optionen manuell konfigurieren. Der Standardwert von QualitySettings ist NormalQuality.

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

### setTimeout(value) {#settimeout}

Setzt den Timeout des Erkennungsprozesses in Millisekunden.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Der Timeout. |

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```
