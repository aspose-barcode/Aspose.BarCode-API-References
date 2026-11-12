---
title: "BarCodeResult"
linktitle: "BarCodeResult"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Stocke les données du code-barres reconnu comme le type SingleDecodeType, le `string` codetext, la région BarCodeRegionParameters et d'autres paramètres"
type: docs
weight: 110
url: /fr/nodejs/aspose.barcode/barcoderesult/
---

## BarCodeResult class

Stocke les données du code-barres reconnu comme le type SingleDecodeType, le `string` codetext, la région BarCodeRegionParameters et d'autres paramètres

```js
new BarCodeResult()
```

**Example:**

```js
//This sample shows how to obtain BarCodeResult.
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("BarCode Confidence: " + result.getConfidence());
    console.log("BarCode ReadingQuality: " + result.getReadingQuality());
    console.log("BarCode Angle: " + result.getRegion().getAngle());
}
```

## Méthodes

| Nom | Description |
| --- | --- |
| [deepClone()](#deepclone) | Crée une copie de la classe BarCodeResult. |
| [equals(other)](#equals) | Renvoie une valeur indiquant si cette instance est égale à une valeur BarCodeResult spécifiée. |
| [getCodeBytes()](#getcodebytes) | Obtient les octets du code encodés Valeur : Les octets du code du code-barres |
| [getCodeText(encoding)](#getcodetext) | Obtient le texte du code avec encodage. Cet exemple montre comment utiliser `getCodeText` : let gen = new BarcodeGenerator(EncodeType |
| [getCodeType()](#getcodetype) | Obtient le type de code-barres Valeur : Les informations de type du code-barres reconnu |
| [getCodeTypeName()](#getcodetypename) | Obtient le nom du type de code-barres Valeur : Le nom du type du code-barres reconnu |
| [getConfidence()](#getconfidence) | Obtient le niveau de confiance de reconnaissance du code-barres reconnu Valeur : BarCodeConfidence.Strong ne contient pas de faux ou d'erreurs de reconnaissance |
| [getExtended()](#getextended) | Obtient les paramètres étendus du code-barres reconnu Valeur : Les paramètres étendus du code-barres reconnu |
| [getReadingQuality()](#getreadingquality) | Obtient la qualité de lecture. Fonctionne pour les codes-barres 1D et postaux. Valeur : Le pourcentage de qualité de lecture |
| [getRegion()](#getregion) | Obtient la région du code-barres Valeur : La région du code-barres reconnu |
| [hashCode()](#hashcode) | Renvoie le code de hachage pour cette instance. |
| [toString()](#tostring) | Renvoie une représentation sous forme de chaîne lisible par l'homme de cet objet BarCodeResult. |

### deepClone() {#deepclone}

Crée une copie de la classe BarCodeResult.

**Returns:** Returns copy of BarCodeResult class.

### equals(other) {#equals}

Renvoie une valeur indiquant si cette instance est égale à une valeur BarCodeResult spécifiée.

| Paramètre | Description |
| --- | --- |
| autre | Une valeur BarCodeResult à comparer à cette instance. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCodeBytes() {#getcodebytes}

Obtient les octets du code encodés Valeur : Les octets du code du code-barres

### getCodeText(encoding) {#getcodetext}

Obtient le texte du code avec encodage. Cet exemple montre comment utiliser `getCodeText` : let gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null); gen.setCodeText("車種名", "932"); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.DATA_MATRIX); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText("932")); }

| Paramètre | Description |
| --- | --- |
| encodage | L'encodage pour le codetext. |

**Returns:** A string containing recognized code text.

### getCodeType() {#getcodetype}

Obtient le type de code-barres Valeur : Les informations de type du code-barres reconnu

### getCodeTypeName() {#getcodetypename}

Obtient le nom du type de code-barres Valeur : Le nom du type du code-barres reconnu

### getConfidence() {#getconfidence}

Obtient le niveau de confiance de reconnaissance du code-barres reconnu Valeur : BarCodeConfidence.Strong ne comporte pas de faux ou de mauvaises reconnaissances, BarCodeConfidence.Moderate peut parfois contenir des faux ou un texte de code incorrect parce que ce niveau de confiance s'applique aux codes-barres avec un checksum faible ou même absent, BarCodeConfidence.NONE a toujours un texte de code incorrect et peut entraîner de fausses reconnaissances

### getExtended() {#getextended}

Obtient les paramètres étendus du code-barres reconnu Valeur : Les paramètres étendus du code-barres reconnu

### getReadingQuality() {#getreadingquality}

Obtient la qualité de lecture. Fonctionne pour les codes-barres 1D et postaux. Valeur : Le pourcentage de qualité de lecture

### getRegion() {#getregion}

Obtient la région du code-barres Valeur : La région du code-barres reconnu

### hashCode() {#hashcode}

Renvoie le code de hachage pour cette instance.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Renvoie une représentation sous forme de chaîne lisible par l'homme de cet objet BarCodeResult.

**Returns:** A string that represents this BarCodeResult.
