---
title: "BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "BarCodeReader kapslar in en bild som kan innehålla en eller flera streckkoder, och kan sedan utföra ReadBarCodes‑operationen för att upptäcka streckkoder."
type: docs
weight: 90
url: /sv/nodejs/aspose.barcode/barcodereader/
---

## BarCodeReader class

BarCodeReader kapslar in en bild som kan innehålla en eller flera streckkoder, och kan sedan utföra ReadBarCodes‑operationen för att upptäcka streckkoder.

```js
new BarCodeReader(image, areas, decodeTypes)
```

Initierar en ny instans av BarCodeReader

| Parameter | Beskrivning |
| --- | --- |
| image | kodad som base64‑sträng eller sökväg till bild |
| områden | array av objekt av typen Rectangle |
| decodeTypes | arrayen av objekt efter DecodeType |

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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [importFromXml(xmlFile)](#importfromxml) *(static)* | Exporterar BarCode-egenskaper till den angivna xml-filen |
| [containsAny()](#containsany) | Avgör om någon av de angivna avkodningstyperna är inkluderad i |
| [exportToXml(xmlFile)](#exporttoxml) | Exporterar BarCode-egenskaper till den angivna xml-filen |
| [getBarCodeReadType()](#getbarcodereadtype) | Hämtar avkodningstypen för den inmatade streckkodsavkodningen |
| [getBarcodeSettings()](#getbarcodesettings) | De viktigaste avkodningsparametrarna för streckkod. Innehåller parametrar som påverkar den igenkända datan. |
| [getFoundBarCodes()](#getfoundbarcodes) | Hämtar den igenkända BarCodeResult-arrayen |
| [getFoundCount()](#getfoundcount) | Hämtar antalet igenkända streckkoder |
| [getQualitySettings()](#getqualitysettings) | QualitySettings möjliggör att manuellt konfigurera igenkänningskvalitet och hastighet. Du kan snabbt ställa in QualitySettings genom att ... |
| [getTimeout()](#gettimeout) | Hämtar tidsgränsen för igenkänningsprocessen i millisekunder. |
| [readBarCodes()](#readbarcodes) | Läser BarCodeResult från bilden. |
| [setBarCodeImage(imageResource, …areas)](#setbarcodeimage) | Ställer in bitmap-bild och områden för igenkänning. Måste anropas före metoden ReadBarCodes(). |
| [setBarCodeReadType(…types)](#setbarcodereadtype) | Ställer in SingleDecodeType-typarrayen för igenkänning. Måste anropas före metoden readBarCodes(). |
| [setQualitySettings()](#setqualitysettings) | QualitySettings möjliggör att manuellt konfigurera igenkänningskvalitet och hastighet. Du kan snabbt ställa in QualitySettings genom att ... |
| [setTimeout(value)](#settimeout) | Ställer in tidsgränsen för igenkänningsprocessen i millisekunder. |

### importFromXml(xmlFile) (static) {#importfromxml}

Exporterar BarCode-egenskaper till den angivna xml-filen

| Parameter | Beskrivning |
| --- | --- |
| xmlFile | Filens namn |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### containsAny() {#containsany}

Avgör om någon av de angivna avkodningstyperna är inkluderad i

| Parameter | Beskrivning |
| --- | --- |
| ...decodeTypes | Typer att verifiera. |

**Returns:** bool Value is a true if any types are included into.

### exportToXml(xmlFile) {#exporttoxml}

Exporterar BarCode-egenskaper till den angivna xml-filen

| Parameter | Beskrivning |
| --- | --- |
| xmlFile | Filens namn |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### getBarCodeReadType() {#getbarcodereadtype}

Hämtar avkodningstypen för den inmatade streckkodsavkodningen

**Returns:** *

### getBarcodeSettings() {#getbarcodesettings}

De viktigaste avkodningsparametrarna för streckkod. Innehåller parametrar som påverkar den igenkända datan.

**Returns:** The main BarCode decoding parameters

### getFoundBarCodes() {#getfoundbarcodes}

Hämtar den igenkända BarCodeResult-arrayen

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

Hämtar antalet igenkända streckkoder

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

QualitySettings möjliggör att konfigurera igenkänningskvalitet och hastighet manuellt. Du kan snabbt ställa in QualitySettings med inbyggda förinställningar: HighPerformance, NormalQuality, HighQuality, MaxBarCodes eller så kan du manuellt konfigurera separata alternativ. Standardvärdet för QualitySettings är NormalQuality.

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

Hämtar tidsgränsen för igenkänningsprocessen i millisekunder.

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

Läser BarCodeResult från bilden.

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

Ställer in bitmap-bild och områden för igenkänning. Måste anropas före metoden ReadBarCodes().

| Parameter | Beskrivning |
| --- | --- |
| imageResource | Bilden för igenkänning. |
| områden | områdeslista för igenkänning |

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

Ställer in SingleDecodeType-typarrayen för igenkänning. Måste anropas före metoden readBarCodes().

| Parameter | Beskrivning |
| --- | --- |
| types | SingleDecodeType-typarrayen att läsa. |

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

QualitySettings möjliggör att konfigurera igenkänningskvalitet och hastighet manuellt. Du kan snabbt ställa in QualitySettings med inbyggda förinställningar: HighPerformance, NormalQuality, HighQuality, MaxBarCodes eller så kan du manuellt konfigurera separata alternativ. Standardvärdet för QualitySettings är NormalQuality.

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

Ställer in tidsgränsen för igenkänningsprocessen i millisekunder.

| Parameter | Beskrivning |
| --- | --- |
| värde | Tidsgränsen. |

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
