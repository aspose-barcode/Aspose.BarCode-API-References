---
title: "DataBarExtendedParameters"
linktitle: "DataBarExtendedParameters"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Stocke des informations supplémentaires DataBar du code-barres reconnu"
type: docs
weight: 310
url: /fr/nodejs/aspose.barcode/databarextendedparameters/
---

## DataBarExtendedParameters class

Stocke des informations supplémentaires DataBar du code-barres reconnu

```js
new DataBarExtendedParameters()
```

**Example:**

```js
let reader = new BarCodeReader("test.png", DecodeType.DATABAR_OMNI_DIRECTIONAL);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
}
```

## Méthodes

| Nom | Description |
| --- | --- |
| [equals(obj)](#equals) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de DataBarExtendedParameters. |
| [hashCode()](#hashcode) | Renvoie le code de hachage pour cette instance. |
| [is2DCompositeComponent()](#is2dcompositecomponent) | Obtient le drapeau du composant composite DataBar 2D. La valeur par défaut est false. |
| [toString()](#tostring) | Renvoie une représentation sous forme de chaîne lisible par l'homme de cet objet. |

### equals(obj) {#equals}

Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée de DataBarExtendedParameters.

| Paramètre | Description |
| --- | --- |
| obj | Valeur DataBarExtendedParameters à comparer à cette instance. |

**Returns:** true if obj has the same value as this instance; otherwise, false .

### hashCode() {#hashcode}

Renvoie le code de hachage pour cette instance.

**Returns:** A 32-bit signed integer hash code.

### is2DCompositeComponent() {#is2dcompositecomponent}

Obtient le drapeau du composant composite DataBar 2D. La valeur par défaut est false.

**Returns:** The DataBar 2D composite component flag.

### toString() {#tostring}

Renvoie une représentation sous forme de chaîne lisible par l'homme de cet objet.

**Returns:** A string that represents this .
