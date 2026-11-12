---
title: "OneDExtendedParameters"
linktitle: "OneDExtendedParameters"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Stocke des données spéciales du code-barres 1D reconnu, comme le texte codé séparé et la somme de contrôle"
type: docs
weight: 720
url: /fr/nodejs/aspose.barcode/onedextendedparameters/
---

## OneDExtendedParameters class

Stocke des données spéciales du code-barres 1D reconnu, comme le texte codé séparé et la somme de contrôle

```js
new OneDExtendedParameters()
```

**Example:**

```js
//This sample shows how to get 1D barcode value and checksum
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.EAN_13);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Value: " + result.getExtended().getOneD().getValue());
   console.log("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

## Méthodes

| Nom | Description |
| --- | --- |
| [equals(obj)](#equals) | Renvoie une valeur indiquant si cette instance est égale à une valeur OneDExtendedParameters spécifiée. |
| [getCheckSum()](#getchecksum) | Obtient la somme de contrôle pour les codes-barres 1D. Valeur : La somme de contrôle pour le code-barres 1D. |
| [getValue()](#getvalue) | Obtient le texte de code des codes-barres 1D sans somme de contrôle. Valeur : Le texte de code des codes-barres 1D sans somme de contrôle. |
| [hashCode()](#hashcode) | Renvoie le code de hachage pour cette instance. |
| [isEmpty()](#isempty) | Teste si tous les paramètres n'ont que les valeurs par défaut. Valeur : Renvoie `true ` si tous les paramètres n'ont que les valeurs par défaut ; o |
| [toString()](#tostring) | Renvoie une représentation sous forme de chaîne lisible par l'homme de cet objet OneDExtendedParameters. |

### equals(obj) {#equals}

Renvoie une valeur indiquant si cette instance est égale à une valeur OneDExtendedParameters spécifiée.

| Paramètre | Description |
| --- | --- |
| obj | Une valeur System.Object à comparer à cette instance. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCheckSum() {#getchecksum}

Obtient la somme de contrôle pour les codes-barres 1D. Valeur : La somme de contrôle pour le code-barres 1D.

### getValue() {#getvalue}

Obtient le texte de code des codes-barres 1D sans somme de contrôle. Valeur : Le texte de code des codes-barres 1D sans somme de contrôle.

### hashCode() {#hashcode}

Renvoie le code de hachage pour cette instance.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Teste si tous les paramètres n'ont que les valeurs par défaut. Valeur : Renvoie `true ` si tous les paramètres n'ont que les valeurs par défaut ; sinon, `false `.

### toString() {#tostring}

Renvoie une représentation sous forme de chaîne lisible par l'homme de cet objet OneDExtendedParameters.

**Returns:** A string that represents this OneDExtendedParameters.
