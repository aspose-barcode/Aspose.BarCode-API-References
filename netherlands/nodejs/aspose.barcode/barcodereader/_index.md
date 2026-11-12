---
title: "BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "BarCodeReader omvat een afbeelding die één of meerdere barcodes kan bevatten, en kan vervolgens de ReadBarCodes‑operatie uitvoeren om barcodes te detecteren."
type: docs
weight: 90
url: /nl/nodejs/aspose.barcode/barcodereader/
---

## BarCodeReader class

BarCodeReader omvat een afbeelding die één of meerdere barcodes kan bevatten, en kan vervolgens de ReadBarCodes‑operatie uitvoeren om barcodes te detecteren.

```js
new BarCodeReader(image, areas, decodeTypes)
```

Initialiseert een nieuwe instantie van de BarCodeReader

| Parameter | Beschrijving |
| --- | --- |
| afbeelding | gecodeerd als base64‑string of pad naar afbeelding |
| gebieden | array van objecten van het type Rectangle |
| decodeTypes | de array van objecten volgens DecodeType |

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

| Naam | Beschrijving |
| --- | --- |
| [importFromXml(xmlFile)](#importfromxml) *(static)* | Exporteert BarCode-eigenschappen naar het opgegeven xml-bestand |
| [containsAny()](#containsany) | Bepaalt of een van de opgegeven decode types is inbegrepen in |
| [exportToXml(xmlFile)](#exporttoxml) | Exporteert BarCode-eigenschappen naar het opgegeven xml-bestand |
| [getBarCodeReadType()](#getbarcodereadtype) | Haalt het decode type op van de invoer barcode decoding |
| [getBarcodeSettings()](#getbarcodesettings) | De belangrijkste BarCode-decodeerparameters. Bevat parameters die invloed hebben op de herkende gegevens. |
| [getFoundBarCodes()](#getfoundbarcodes) | Haalt de herkende BarCodeResult-array op |
| [getFoundCount()](#getfoundcount) | Haalt het aantal herkende barcodes op |
| [getQualitySettings()](#getqualitysettings) | QualitySettings maakt handmatige configuratie van herkenningskwaliteit en -snelheid mogelijk. Je kunt QualitySettings snel instellen via em |
| [getTimeout()](#gettimeout) | Haalt de timeout van het herkenningsproces op in milliseconden. |
| [readBarCodes()](#readbarcodes) | Leest BarCodeResult van de afbeelding. |
| [setBarCodeImage(imageResource, …areas)](#setbarcodeimage) | Stelt bitmap-afbeelding en gebieden in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes()-methode. |
| [setBarCodeReadType(…types)](#setbarcodereadtype) | Stelt SingleDecodeType-type-array in voor herkenning. Moet worden aangeroepen vóór de readBarCodes()-methode. |
| [setQualitySettings()](#setqualitysettings) | QualitySettings maakt handmatige configuratie van herkenningskwaliteit en -snelheid mogelijk. Je kunt QualitySettings snel instellen via em |
| [setTimeout(value)](#settimeout) | Stelt de timeout van het herkenningsproces in milliseconden in. |

### importFromXml(xmlFile) (static) {#importfromxml}

Exporteert BarCode-eigenschappen naar het opgegeven xml-bestand

| Parameter | Beschrijving |
| --- | --- |
| xmlFile | De naam van het bestand |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### containsAny() {#containsany}

Bepaalt of een van de opgegeven decode types is inbegrepen in

| Parameter | Beschrijving |
| --- | --- |
| ...decodeTypes | Typen om te verifiëren. |

**Returns:** bool Value is a true if any types are included into.

### exportToXml(xmlFile) {#exporttoxml}

Exporteert BarCode-eigenschappen naar het opgegeven xml-bestand

| Parameter | Beschrijving |
| --- | --- |
| xmlFile | De naam van het bestand |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### getBarCodeReadType() {#getbarcodereadtype}

Haalt het decode type op van de invoer barcode decoding

**Returns:** *

### getBarcodeSettings() {#getbarcodesettings}

De belangrijkste BarCode-decodeerparameters. Bevat parameters die invloed hebben op de herkende gegevens.

**Returns:** The main BarCode decoding parameters

### getFoundBarCodes() {#getfoundbarcodes}

Haalt de herkende BarCodeResult-array op

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

Haalt het aantal herkende barcodes op

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

QualitySettings maakt handmatige configuratie van herkenningskwaliteit en snelheid mogelijk. U kunt QualitySettings snel instellen met ingebouwde presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes, of u kunt afzonderlijke opties handmatig configureren. Standaardwaarde van QualitySettings is NormalQuality.

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

Haalt de timeout van het herkenningsproces op in milliseconden.

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

Leest BarCodeResult van de afbeelding.

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

Stelt bitmap-afbeelding en gebieden in voor herkenning. Moet worden aangeroepen vóór de ReadBarCodes()-methode.

| Parameter | Beschrijving |
| --- | --- |
| imageResource | De afbeelding voor herkenning. |
| gebieden | gebiedenlijst voor herkenning |

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

Stelt SingleDecodeType-type-array in voor herkenning. Moet worden aangeroepen vóór de readBarCodes()-methode.

| Parameter | Beschrijving |
| --- | --- |
| types | De SingleDecodeType-type-array om te lezen. |

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

QualitySettings maakt handmatige configuratie van herkenningskwaliteit en snelheid mogelijk. U kunt QualitySettings snel instellen met ingebouwde presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes, of u kunt afzonderlijke opties handmatig configureren. Standaardwaarde van QualitySettings is NormalQuality.

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

Stelt de timeout van het herkenningsproces in milliseconden in.

| Parameter | Beschrijving |
| --- | --- |
| waarde | De timeout. |

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
