---
title: "BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "BarCodeReader encapsule une image qui peut contenir un ou plusieurs codes-barres, il peut alors effectuer l'opération ReadBarCodes pour détecter les codes-barres."
type: docs
weight: 90
url: /fr/nodejs/aspose.barcode/barcodereader/
---

## BarCodeReader class

BarCodeReader encapsule une image qui peut contenir un ou plusieurs codes-barres, il peut alors effectuer l'opération ReadBarCodes pour détecter les codes-barres.

```js
new BarCodeReader(image, areas, decodeTypes)
```

Initialise une nouvelle instance de BarCodeReader

| Paramètre | Description |
| --- | --- |
| image | encodé en chaîne base64 ou chemin vers l'image |
| zones | tableau d'objets de type Rectangle |
| decodeTypes | le tableau d'objets par DecodeType |

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

## Méthodes

| Nom | Description |
| --- | --- |
| [importFromXml(xmlFile)](#importfromxml) *(static)* | Exporte les propriétés BarCode vers le fichier xml spécifié |
| [containsAny()](#containsany) | Détermine si l'un des types de décodage fournis est inclus dans |
| [exportToXml(xmlFile)](#exporttoxml) | Exporte les propriétés BarCode vers le fichier xml spécifié |
| [getBarCodeReadType()](#getbarcodereadtype) | Obtient le type de décodage du code-barres d'entrée |
| [getBarcodeSettings()](#getbarcodesettings) | Les principaux paramètres de décodage du BarCode. Contient des paramètres qui influencent les données reconnues. |
| [getFoundBarCodes()](#getfoundbarcodes) | Obtient le tableau BarCodeResult reconnu |
| [getFoundCount()](#getfoundcount) | Obtient le nombre de codes-barres reconnus |
| [getQualitySettings()](#getqualitysettings) | QualitySettings permet de configurer manuellement la qualité et la vitesse de reconnaissance. Vous pouvez configurer rapidement QualitySettings par em |
| [getTimeout()](#gettimeout) | Obtient le délai d'attente du processus de reconnaissance en millisecondes. |
| [readBarCodes()](#readbarcodes) | Lit le BarCodeResult depuis l'image. |
| [setBarCodeImage(imageResource, …areas)](#setbarcodeimage) | Définit l'image bitmap et les zones pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes(). |
| [setBarCodeReadType(…types)](#setbarcodereadtype) | Définit le tableau de types SingleDecodeType pour la reconnaissance. Doit être appelé avant la méthode readBarCodes(). |
| [setQualitySettings()](#setqualitysettings) | QualitySettings permet de configurer manuellement la qualité et la vitesse de reconnaissance. Vous pouvez configurer rapidement QualitySettings par em |
| [setTimeout(value)](#settimeout) | Définit le délai d'attente du processus de reconnaissance en millisecondes. |

### importFromXml(xmlFile) (static) {#importfromxml}

Exporte les propriétés BarCode vers le fichier xml spécifié

| Paramètre | Description |
| --- | --- |
| xmlFile | Le nom du fichier |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### containsAny() {#containsany}

Détermine si l'un des types de décodage fournis est inclus dans

| Paramètre | Description |
| --- | --- |
| ...decodeTypes | Types à vérifier. |

**Returns:** bool Value is a true if any types are included into.

### exportToXml(xmlFile) {#exporttoxml}

Exporte les propriétés BarCode vers le fichier xml spécifié

| Paramètre | Description |
| --- | --- |
| xmlFile | Le nom du fichier |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### getBarCodeReadType() {#getbarcodereadtype}

Obtient le type de décodage du code-barres d'entrée

**Returns:** *

### getBarcodeSettings() {#getbarcodesettings}

Les principaux paramètres de décodage du BarCode. Contient des paramètres qui influencent les données reconnues.

**Returns:** The main BarCode decoding parameters

### getFoundBarCodes() {#getfoundbarcodes}

Obtient le tableau BarCodeResult reconnu

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

Obtient le nombre de codes-barres reconnus

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

QualitySettings permet de configurer manuellement la qualité et la vitesse de reconnaissance. Vous pouvez configurer rapidement QualitySettings à l'aide de préréglages intégrés : HighPerformance, NormalQuality, HighQuality, MaxBarCodes ou vous pouvez configurer manuellement les options séparées. La valeur par défaut de QualitySettings est NormalQuality.

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

Obtient le délai d'attente du processus de reconnaissance en millisecondes.

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

Lit le BarCodeResult depuis l'image.

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

Définit l'image bitmap et les zones pour la reconnaissance. Doit être appelé avant la méthode ReadBarCodes().

| Paramètre | Description |
| --- | --- |
| imageResource | L'image pour la reconnaissance. |
| zones | liste des zones pour la reconnaissance |

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

Définit le tableau de types SingleDecodeType pour la reconnaissance. Doit être appelé avant la méthode readBarCodes().

| Paramètre | Description |
| --- | --- |
| types | Le tableau de types SingleDecodeType à lire. |

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

QualitySettings permet de configurer manuellement la qualité et la vitesse de reconnaissance. Vous pouvez configurer rapidement QualitySettings à l'aide de préréglages intégrés : HighPerformance, NormalQuality, HighQuality, MaxBarCodes ou vous pouvez configurer manuellement les options séparées. La valeur par défaut de QualitySettings est NormalQuality.

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

Définit le délai d'attente du processus de reconnaissance en millisecondes.

| Paramètre | Description |
| --- | --- |
| valeur | Le délai d'attente. |

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
