---
title: "BarcodeSettings"
linktitle: "BarcodeSettings"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Les principaux paramètres de décodage BarCode."
type: docs
weight: 150
url: /fr/nodejs/aspose.barcode/barcodesettings/
---

## BarcodeSettings class

Les principaux paramètres de décodage du BarCode. Contient des paramètres qui influencent les données reconnues.

```js
new BarcodeSettings(settings)
```

Constructeur de copie BarcodeSettings

| Paramètre | Description |
| --- | --- |
| paramètres | La source des données |

## Méthodes

| Nom | Description |
| --- | --- |
| [getAustraliaPost()](#getaustraliapost) | Obtient les paramètres de décodage AustraliaPost |
| [getChecksumValidation()](#getchecksumvalidation) | Activer la validation du checksum lors de la reconnaissance des codes-barres 1D et postaux. La valeur par défaut est considérée comme Oui pour les symbologies whic |
| [getDetectEncoding()](#getdetectencoding) | Le drapeau qui force le moteur à détecter l'encodage du texte du code pour les jeux de caractères Unicode. La valeur par défaut est vraie. |
| [getStripFNC()](#getstripfnc) | Supprimer les caractères FNC1, FNC2, FNC3 du texte du code. La valeur par défaut est false. |
| [isOnlyRequestedTypes()](#isonlyrequestedtypes) | Renvoie uniquement les types de codes-barres explicitement spécifiés pour la reconnaissance. Lorsqu'activé, les codes-barres reconnus d'autres types compatibles o |
| [setChecksumValidation(value)](#setchecksumvalidation) | Activer la validation du checksum lors de la reconnaissance des codes-barres 1D et postaux. La valeur par défaut est considérée comme Oui pour les symbologies whic |
| [setDetectEncoding()](#setdetectencoding) | Le drapeau qui force le moteur à détecter l'encodage du texte du code pour les jeux de caractères Unicode. La valeur par défaut est vraie. |
| [setOnlyRequestedTypes()](#setonlyrequestedtypes) | Renvoie uniquement les types de codes-barres explicitement spécifiés pour la reconnaissance. Lorsqu'activé, les codes-barres reconnus d'autres types compatibles o |
| [setStripFNC(value)](#setstripfnc) | Supprimer les caractères FNC1, FNC2, FNC3 du texte du code. La valeur par défaut est false. |

### getAustraliaPost() {#getaustraliapost}

Obtient les paramètres de décodage AustraliaPost

**Returns:** The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology

### getChecksumValidation() {#getchecksumvalidation}

Activer la validation du checksum lors de la reconnaissance des codes-barres 1D et postaux. La valeur par défaut est considérée comme Oui pour les symbologies qui doivent contenir un checksum, et comme Non lorsque le checksum n'est possible que facultatif. Checksum jamais utilisé : Codabar, PatchCode, Pharmacode, DataLogic2of5. Checksum possible : Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Checksum toujours utilisé : le reste des symbologies.

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

Le drapeau qui force le moteur à détecter l'encodage du texte du code pour les jeux de caractères Unicode. La valeur par défaut est vraie.

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

Supprimer les caractères FNC1, FNC2, FNC3 du texte du code. La valeur par défaut est false.

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

Renvoie uniquement les types de codes-barres explicitement spécifiés pour la reconnaissance. Lorsqu'activé, les codes-barres reconnus d'autres types compatibles ou équivalents sont filtrés. La valeur par défaut est false. Exemple : // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setChecksumValidation(value) {#setchecksumvalidation}

Activer la validation du checksum lors de la reconnaissance des codes-barres 1D et postaux. La valeur par défaut est considérée comme Oui pour les symbologies qui doivent contenir un checksum, et comme Non lorsque le checksum n'est possible que facultatif. Checksum jamais utilisé : Codabar, PatchCode, Pharmacode, DataLogic2of5. Checksum possible : Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Checksum toujours utilisé : le reste des symbologies.

| Paramètre | Description |
| --- | --- |
| valeur | Activer la validation du checksum lors de la reconnaissance des codes-barres 1D et postaux. |

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

Le drapeau qui force le moteur à détecter l'encodage du texte du code pour les jeux de caractères Unicode. La valeur par défaut est vraie.

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

Renvoie uniquement les types de codes-barres explicitement spécifiés pour la reconnaissance. Lorsqu'activé, les codes-barres reconnus d'autres types compatibles ou équivalents sont filtrés. La valeur par défaut est false. Exemple : // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setStripFNC(value) {#setstripfnc}

Supprimer les caractères FNC1, FNC2, FNC3 du texte du code. La valeur par défaut est false.

| Paramètre | Description |
| --- | --- |
| valeur | Supprimer les caractères FNC1, FNC2, FNC3 du texte du code. La valeur par défaut est false. |

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
