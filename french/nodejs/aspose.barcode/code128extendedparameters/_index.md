---
title: "Code128ExtendedParameters"
linktitle: "Code128ExtendedParameters"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Stocke des données spéciales du code-barres Code128 reconnu. Représente la région du code-barres reconnu et l'angle du code-barres"
type: docs
weight: 240
url: /fr/nodejs/aspose.barcode/code128extendedparameters/
---

## Code128ExtendedParameters class

Stocke des données spéciales du code-barres Code128 reconnu. Représente la région du code-barres reconnu et l'angle du code-barres

```js
new Code128ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get code128 raw values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.CODE_128);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("Code128 Data Portions: " + result.getExtended().getCode128());
}
```

## Méthodes

| Nom | Description |
| --- | --- |
| [equals(obj)](#equals) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de Code128ExtendedParameters. |
| [getCode128DataPortions()](#getcode128dataportions) | Obtient le tableau Code128DataPortion du code-barres Code128 reconnu. Valeur du Code128DataPortion. |
| [hashCode()](#hashcode) | Renvoie le code de hachage pour cette instance. |
| [toString()](#tostring) | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce Code128ExtendedParameters. |

### equals(obj) {#equals}

Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de Code128ExtendedParameters.

| Paramètre | Description |
| --- | --- |
| obj | Une valeur System.Object à comparer à cette instance. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCode128DataPortions() {#getcode128dataportions}

Obtient le tableau Code128DataPortion du code-barres Code128 reconnu. Valeur du Code128DataPortion.

### hashCode() {#hashcode}

Renvoie le code de hachage pour cette instance.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Renvoie une représentation sous forme de chaîne lisible par l'homme de ce Code128ExtendedParameters.

**Returns:** A string that represents this Code128ExtendedParameters.
