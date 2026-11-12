---
title: "BarCodeRegionParameters"
linktitle: "BarCodeRegionParameters"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Représente la région du code-barres reconnu et l'angle du code-barres"
type: docs
weight: 100
url: /fr/nodejs/aspose.barcode/barcoderegionparameters/
---

## BarCodeRegionParameters class

Représente la région du code-barres reconnu et l'angle du code-barres

```js
new BarCodeRegionParameters()
```

**Example:**

```js
//This sample shows how to get barcode Angle and bounding quadrangle values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Angle: " + result.getRegion().getAngle());
   console.log("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
}
```

## Méthodes

| Nom | Description |
| --- | --- |
| [equals(obj)](#equals) | Renvoie une valeur indiquant si cette instance est égale à une valeur BarCodeRegionParameters spécifiée. |
| [getAngle()](#getangle) | Obtient l'angle du code-barres (0-360). Valeur : L'angle du code-barres (0-360). |
| [getPoints()](#getpoints) | Obtient le tableau Points délimitant la région du code-barres Valeur : Retourne le tableau Points délimitant la région du code-barres |
| [getQuadrangle()](#getquadrangle) | Obtient le Quadrangle délimitant la région du code-barres Valeur : Retourne le Quadrangle délimitant la région du code-barres |
| [getRectangle()](#getrectangle) | Obtient le Rectangle délimitant la région du code-barres Valeur : Retourne le Rectangle délimitant la région du code-barres |
| [hashCode()](#hashcode) | Renvoie le code de hachage pour cette instance. |
| [toString()](#tostring) | Renvoie une représentation sous forme de chaîne lisible par l'homme de ces BarCodeRegionParameters. |

### equals(obj) {#equals}

Renvoie une valeur indiquant si cette instance est égale à une valeur BarCodeRegionParameters spécifiée.

| Paramètre | Description |
| --- | --- |
| obj | Une valeur System.Object à comparer à cette instance. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getAngle() {#getangle}

Obtient l'angle du code-barres (0-360). Valeur : L'angle du code-barres (0-360).

### getPoints() {#getpoints}

Obtient le tableau Points délimitant la région du code-barres Valeur : Retourne le tableau Points délimitant la région du code-barres

### getQuadrangle() {#getquadrangle}

Obtient le Quadrangle délimitant la région du code-barres Valeur : Retourne le Quadrangle délimitant la région du code-barres

### getRectangle() {#getrectangle}

Obtient le Rectangle délimitant la région du code-barres Valeur : Retourne le Rectangle délimitant la région du code-barres

### hashCode() {#hashcode}

Renvoie le code de hachage pour cette instance.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Renvoie une représentation sous forme de chaîne lisible par l'homme de ces BarCodeRegionParameters.

**Returns:** A string that represents this BarCodeRegionParameters.
