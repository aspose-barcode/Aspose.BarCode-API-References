---
title: "MaxiCodeStandardCodetext"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Classe pour l'encodage et le décodage du texte codé MaxiCode pour les modes 4, 5 et 6."
type: docs
weight: 670
url: /fr/nodejs/aspose.barcode/maxicodestandardcodetext/
---

## MaxiCodeStandardCodetext class

Classe pour l'encodage et le décodage du texte codé MaxiCode pour les modes 4, 5 et 6.

```js
new MaxiCodeStandardCodetext()
```

**Example:**

```js
//Mode 4
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## Méthodes

| Nom | Description |
| --- | --- |
| [equals(obj)](#equals) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée. |
| [getConstructedCodetext()](#getconstructedcodetext) | Construit le codetext |
| [getHashCode()](#gethashcode) | Renvoie le code de hachage pour cette instance. |
| [getMessage()](#getmessage) | Obtient le message. |
| [getMode()](#getmode) | Obtient le mode MaxiCode. |
| [initFromString(constructedCodetext)](#initfromstring) | Initialise l'instance à partir du codetext construit. |
| [setMessage()](#setmessage) | Définit le message. |
| [setMode()](#setmode) | Définit le mode MaxiCode. Le texte de code standard ne peut être utilisé qu'avec les modes 4, 5 et 6. |

### equals(obj) {#equals}

Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée.

| Paramètre | Description |
| --- | --- |
| obj | Une valeur à comparer à cette instance. |

**Returns:** if obj has the same value as this instance; otherwise, false .

### getConstructedCodetext() {#getconstructedcodetext}

Construit le codetext

**Returns:** Constructed codetext

### getHashCode() {#gethashcode}

Renvoie le code de hachage pour cette instance.

**Returns:** A 32-bit signed integer hash code

### getMessage() {#getmessage}

Obtient le message.

### getMode() {#getmode}

Obtient le mode MaxiCode.

**Returns:** MaxiCode mode

### initFromString(constructedCodetext) {#initfromstring}

Initialise l'instance à partir du codetext construit.

| Paramètre | Description |
| --- | --- |
| constructedCodetext | Codetext construit. |

### setMessage() {#setmessage}

Définit le message.

### setMode() {#setmode}

Définit le mode MaxiCode. Le texte de code standard ne peut être utilisé qu'avec les modes 4, 5 et 6.
