---
title: "BarcodeSettings"
linktitle: "BarcodeSettings"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "De belangrijkste BarCode-decodering parameters."
type: docs
weight: 150
url: /nl/nodejs/aspose.barcode/barcodesettings/
---

## BarcodeSettings class

De belangrijkste BarCode-decodeerparameters. Bevat parameters die invloed hebben op de herkende gegevens.

```js
new BarcodeSettings(settings)
```

BarcodeSettings kopieconstructor

| Parameter | Beschrijving |
| --- | --- |
| instellingen | De bron van de gegevens |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getAustraliaPost()](#getaustraliapost) | Haalt AustraliaPost-decodering parameters op |
| [getChecksumValidation()](#getchecksumvalidation) | Schakel checksumvalidatie in tijdens herkenning voor 1D- en postcodes. Standaard wordt behandeld als Ja voor symbologieën die |
| [getDetectEncoding()](#getdetectencoding) | De vlag die de engine dwingt om de codetextcodering voor Unicode-sets te detecteren. Standaardwaarde is true. |
| [getStripFNC()](#getstripfnc) | Verwijder FNC1-, FNC2- en FNC3-tekens uit codetext. Standaardwaarde is false. |
| [isOnlyRequestedTypes()](#isonlyrequestedtypes) | Retourneert alleen barcode‑typen die expliciet zijn opgegeven voor herkenning. Wanneer ingeschakeld, worden herkende barcodes van andere compatibele o |
| [setChecksumValidation(value)](#setchecksumvalidation) | Schakel checksumvalidatie in tijdens herkenning voor 1D- en postcodes. Standaard wordt behandeld als Ja voor symbologieën die |
| [setDetectEncoding()](#setdetectencoding) | De vlag die de engine dwingt om de codetextcodering voor Unicode-sets te detecteren. Standaardwaarde is true. |
| [setOnlyRequestedTypes()](#setonlyrequestedtypes) | Retourneert alleen barcode‑typen die expliciet zijn opgegeven voor herkenning. Wanneer ingeschakeld, worden herkende barcodes van andere compatibele o |
| [setStripFNC(value)](#setstripfnc) | Verwijder FNC1-, FNC2- en FNC3-tekens uit codetext. Standaardwaarde is false. |

### getAustraliaPost() {#getaustraliapost}

Haalt AustraliaPost-decodering parameters op

**Returns:** The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology

### getChecksumValidation() {#getchecksumvalidation}

Schakel checksumvalidatie in tijdens herkenning voor 1D- en postcodes. Standaard wordt behandeld als Ja voor symbologieën die een checksum moeten bevatten, als Nee waar een checksum alleen mogelijk is. Checksum nooit gebruikt: Codabar, PatchCode, Pharmacode, DataLogic2of5 Checksum is mogelijk: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN Checksum altijd gebruikt: Rest symbologieën

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

De vlag die de engine dwingt om de codetextcodering voor Unicode-sets te detecteren. Standaardwaarde is true.

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

Verwijder FNC1-, FNC2- en FNC3-tekens uit codetext. Standaardwaarde is false.

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

Retourneert alleen barcode‑typen die expliciet zijn opgegeven voor herkenning. Wanneer ingeschakeld, worden herkende barcodes van andere compatibele of equivalente typen gefilterd. Standaardwaarde is false. Voorbeeld: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setChecksumValidation(value) {#setchecksumvalidation}

Schakel checksumvalidatie in tijdens herkenning voor 1D- en postcodes. Standaard wordt behandeld als Ja voor symbologieën die een checksum moeten bevatten, als Nee waar een checksum alleen mogelijk is. Checksum nooit gebruikt: Codabar, PatchCode, Pharmacode, DataLogic2of5 Checksum is mogelijk: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN Checksum altijd gebruikt: Rest symbologieën

| Parameter | Beschrijving |
| --- | --- |
| waarde | Schakel checksumvalidatie in tijdens herkenning voor 1D- en postcodes. |

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

De vlag die de engine dwingt om de codetextcodering voor Unicode-sets te detecteren. Standaardwaarde is true.

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

Retourneert alleen barcode‑typen die expliciet zijn opgegeven voor herkenning. Wanneer ingeschakeld, worden herkende barcodes van andere compatibele of equivalente typen gefilterd. Standaardwaarde is false. Voorbeeld: // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setStripFNC(value) {#setstripfnc}

Verwijder FNC1-, FNC2- en FNC3-tekens uit codetext. Standaardwaarde is false.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Verwijder FNC1-, FNC2- en FNC3-tekens uit codetext. Standaardwaarde is false. |

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
