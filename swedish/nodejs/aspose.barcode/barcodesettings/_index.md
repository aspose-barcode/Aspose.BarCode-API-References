---
title: "BarcodeSettings"
linktitle: "BarcodeSettings"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "De viktigaste BarCode-avkodningsparametrarna."
type: docs
weight: 150
url: /sv/nodejs/aspose.barcode/barcodesettings/
---

## BarcodeSettings class

De viktigaste avkodningsparametrarna för streckkod. Innehåller parametrar som påverkar den igenkända datan.

```js
new BarcodeSettings(settings)
```

BarcodeSettings kopieringskonstruktor

| Parameter | Beskrivning |
| --- | --- |
| inställningar | Källan till data |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getAustraliaPost()](#getaustraliapost) | Hämtar AustraliaPost-avkodningsparametrar |
| [getChecksumValidation()](#getchecksumvalidation) | Aktivera kontrollsummavalidering under igenkänning för 1D- och poststreckkoder. Standard behandlas som Ja för symboler som |
| [getDetectEncoding()](#getdetectencoding) | Flaggan som tvingar motorn att upptäcka kodtextkodning för Unicode-teckenuppsättningar. Standardvärdet är true. |
| [getStripFNC()](#getstripfnc) | Ta bort FNC1-, FNC2- och FNC3-tecken från kodtexten. Standardvärdet är false. |
| [isOnlyRequestedTypes()](#isonlyrequestedtypes) | Returnerar endast streckkodstyper som uttryckligen specificerats för igenkänning. När aktiverad, erkänns streckkoder av andra kompatibla o |
| [setChecksumValidation(value)](#setchecksumvalidation) | Aktivera kontrollsummavalidering under igenkänning för 1D- och poststreckkoder. Standard behandlas som Ja för symboler som |
| [setDetectEncoding()](#setdetectencoding) | Flaggan som tvingar motorn att upptäcka kodtextkodning för Unicode-teckenuppsättningar. Standardvärdet är true. |
| [setOnlyRequestedTypes()](#setonlyrequestedtypes) | Returnerar endast streckkodstyper som uttryckligen specificerats för igenkänning. När aktiverad, erkänns streckkoder av andra kompatibla o |
| [setStripFNC(value)](#setstripfnc) | Ta bort FNC1-, FNC2- och FNC3-tecken från kodtexten. Standardvärdet är false. |

### getAustraliaPost() {#getaustraliapost}

Hämtar AustraliaPost-avkodningsparametrar

**Returns:** The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology

### getChecksumValidation() {#getchecksumvalidation}

Aktivera kontrollsummavalidering under igenkänning för 1D- och poststreckkoder. Standard behandlas som Ja för symboler som måste innehålla kontrollsumma, och som Nej där kontrollsumma bara är möjlig. Kontrollsumma används aldrig: Codabar, PatchCode, Pharmacode, DataLogic2of5. Kontrollsumma är möjlig: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Kontrollsumma används alltid: övriga symboler.

**Returns:** Enable checksum validation during recognition for 1D and Postal barcodes.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### getDetectEncoding() {#getdetectencoding}

Flaggan som tvingar motorn att upptäcka kodtextkodning för Unicode-teckenuppsättningar. Standardvärdet är true.

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### getStripFNC() {#getstripfnc}

Ta bort FNC1-, FNC2- och FNC3-tecken från kodtexten. Standardvärdet är false.

**Returns:** Strip FNC1, FNC2, FNC3 characters from codetext. Default value is false.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### isOnlyRequestedTypes() {#isonlyrequestedtypes}

Returnerar endast streckkodstyper som uttryckligen specificerats för igenkänning. När aktiverad filtreras erkända streckkoder av andra kompatibla eller motsvarande typer bort. Standardvärdet är false. Exempel: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setChecksumValidation(value) {#setchecksumvalidation}

Aktivera kontrollsummavalidering under igenkänning för 1D- och poststreckkoder. Standard behandlas som Ja för symboler som måste innehålla kontrollsumma, och som Nej där kontrollsumma bara är möjlig. Kontrollsumma används aldrig: Codabar, PatchCode, Pharmacode, DataLogic2of5. Kontrollsumma är möjlig: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Kontrollsumma används alltid: övriga symboler.

| Parameter | Beskrivning |
| --- | --- |
| värde | Aktivera kontrollsummavalidering under igenkänning för 1D- och poststreckkoder. |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### setDetectEncoding() {#setdetectencoding}

Flaggan som tvingar motorn att upptäcka kodtextkodning för Unicode-teckenuppsättningar. Standardvärdet är true.

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### setOnlyRequestedTypes() {#setonlyrequestedtypes}

Returnerar endast streckkodstyper som uttryckligen specificerats för igenkänning. När aktiverad filtreras erkända streckkoder av andra kompatibla eller motsvarande typer bort. Standardvärdet är false. Exempel: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setStripFNC(value) {#setstripfnc}

Ta bort FNC1-, FNC2- och FNC3-tecken från kodtexten. Standardvärdet är false.

| Parameter | Beskrivning |
| --- | --- |
| värde | Ta bort FNC1-, FNC2- och FNC3-tecken från kodtexten. Standardvärdet är false. |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```
