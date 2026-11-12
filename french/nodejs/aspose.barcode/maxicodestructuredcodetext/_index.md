---
title: "MaxiCodeStructuredCodetext"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Classe de base pour l'encodage et le décodage du texte intégré dans le code MaxiCode pour les modes 2 et 3."
type: docs
weight: 700
url: /fr/nodejs/aspose.barcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

Classe de base pour l'encodage et le décodage du texte intégré dans le code MaxiCode pour les modes 2 et 3.

```js
new MaxiCodeStructuredCodetext()
```

**Example:**

```js
This sample shows how to decode raw MaxiCode codetext to MaxiCodeStructuredCodetext instance.

 let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
 let results = reader.readBarCodes();
 for(let i = 0; i < results.length; i++)
 {
    let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     if (resultMaxiCodeCodetext instanceof MaxiCodeStructuredCodetext)
     {
         let maxiCodeStructuredCodetext = resultMaxiCodeCodetext;
         console.log("BarCode Type: " + maxiCodeStructuredCodetext.getPostalCode());
         console.log("MaxiCode mode: " + maxiCodeStructuredCodetext.getCountryCode());
         console.log("BarCode CodeText: " + maxiCodeStructuredCodetext.getServiceCategory());
     }
 }
```

## Méthodes

| Nom | Description |
| --- | --- |
| [equals(obj)](#equals) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée. |
| [getConstructedCodetext()](#getconstructedcodetext) | Construit le codetext |
| [getCountryCode()](#getcountrycode) | Identifie le code pays à 3 chiffres. |
| [getHashCode()](#gethashcode) | Renvoie le code de hachage pour cette instance. |
| [getPostalCode()](#getpostalcode) | Identifie le code postal. Doit comporter 9 chiffres en mode 2 ou 6 caractères alphanumériques en mode 3. |
| [getSecondMessage()](#getsecondmessage) | Identifie le deuxième message du code-barres. |
| [getServiceCategory()](#getservicecategory) | Identifie la catégorie de service à 3 chiffres. |
| [initFromString(constructedCodetext)](#initfromstring) | Initialise l'instance à partir du codetext construit. |
| [setCountryCode()](#setcountrycode) | Identifie le code pays à 3 chiffres. |
| [setPostalCode()](#setpostalcode) | Identifie le code postal. Doit comporter 9 chiffres en mode 2 ou 6 caractères alphanumériques en mode 3. |
| [setSecondMessage()](#setsecondmessage) | Identifie le deuxième message du code-barres. |
| [setServiceCategory()](#setservicecategory) | Identifie la catégorie de service à 3 chiffres. |

### equals(obj) {#equals}

Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée.

| Paramètre | Description |
| --- | --- |
| obj | Une valeur à comparer à cette instance |

**Returns:** true if obj has the same value as this instance; otherwise, false

### getConstructedCodetext() {#getconstructedcodetext}

Construit le codetext

**Returns:** Constructed codetext

### getCountryCode() {#getcountrycode}

Identifie le code pays à 3 chiffres.

### getHashCode() {#gethashcode}

Renvoie le code de hachage pour cette instance.

**Returns:** A 32-bit signed integer hash code.

### getPostalCode() {#getpostalcode}

Identifie le code postal. Doit comporter 9 chiffres en mode 2 ou 6 caractères alphanumériques en mode 3.

### getSecondMessage() {#getsecondmessage}

Identifie le deuxième message du code-barres.

### getServiceCategory() {#getservicecategory}

Identifie la catégorie de service à 3 chiffres.

### initFromString(constructedCodetext) {#initfromstring}

Initialise l'instance à partir du codetext construit.

| Paramètre | Description |
| --- | --- |
| constructedCodetext | Codetext construit. |

### setCountryCode() {#setcountrycode}

Identifie le code pays à 3 chiffres.

### setPostalCode() {#setpostalcode}

Identifie le code postal. Doit comporter 9 chiffres en mode 2 ou 6 caractères alphanumériques en mode 3.

### setSecondMessage() {#setsecondmessage}

Identifie le deuxième message du code-barres.

### setServiceCategory() {#setservicecategory}

Identifie la catégorie de service à 3 chiffres.
