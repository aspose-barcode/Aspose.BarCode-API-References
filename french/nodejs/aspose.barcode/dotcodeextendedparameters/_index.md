---
title: "DotCodeExtendedParameters"
linktitle: "DotCodeExtendedParameters"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Stocke des données spéciales du code-barres DotCode reconnu. Cet exemple montre comment obtenir les valeurs brutes de DotCode"
type: docs
weight: 380
url: /fr/nodejs/aspose.barcode/dotcodeextendedparameters/
---

## DotCodeExtendedParameters class

Stocke des données spéciales du code-barres DotCode reconnu. Cet exemple montre comment obtenir les valeurs brutes de DotCode

```js
new DotCodeExtendedParameters()
```

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
generator.save("test.png", BarCodeImageFormat.PNG);

let reader = new BarCodeReader("test.png", null, DecodeType.DOT_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    print("BarCode type: " + result.getCodeTypeName());
    print("BarCode codetext: " + result.getCodeText());
    print("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
    print("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
}
```

## Méthodes

| Nom | Description |
| --- | --- |
| [equals(obj)](#equals) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée `DotCodeExtendedParameters`. |
| [getDotCodeIsReaderInitialization()](#getdotcodeisreaderinitialization) ~~(deprecated)~~ | Indique si le code est utilisé pour instruire le lecteur d'interpréter les données suivantes comme des instructions d'initialisation ou |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | Obtient l'ID du code-barres en mode d'ajout structuré DotCode. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | Obtient le nombre de codes-barres en mode d'ajout structuré DotCode. La valeur par défaut est -1. Le nombre doit être compris entre 1 et 35. Valeur : |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Obtient l'ID du code-barres en mode d'ajout structuré DotCode. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres. |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | Obtient le nombre de codes-barres en mode d'ajout structuré DotCode. La valeur par défaut est -1. Le nombre doit être compris entre 1 et 35. Valeur : |
| [hashCode()](#hashcode) | Renvoie le code de hachage pour cette instance. |
| [isReaderInitialization()](#isreaderinitialization) | Indique si le code est utilisé pour instruire le lecteur d'interpréter les données suivantes comme des instructions d'initialisation ou |
| [toString()](#tostring) | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `DotCodeExtendedParameters`. |

### equals(obj) {#equals}

Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée `DotCodeExtendedParameters`.

| Paramètre | Description |
| --- | --- |
| obj | Une valeur System.Object à comparer à cette instance. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDotCodeIsReaderInitialization() {#getdotcodeisreaderinitialization}

> **Deprecated.** See method description for replacement.

Indique si le code est utilisé pour instruire le lecteur d'interpréter les données suivantes comme des instructions d'initialisation ou de reprogrammation du lecteur de codes-barres. La valeur par défaut est false.

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

Obtient l'ID du code-barres en mode d'ajout structuré DotCode. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres. La valeur par défaut est -1. Valeur : L'ID du code-barres en mode d'ajout structuré DotCode.

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

Obtient le nombre de codes-barres en mode d'ajout structuré DotCode. La valeur par défaut est -1. Le nombre doit être compris entre 1 et 35. Valeur : Le nombre de codes-barres en mode d'ajout structuré DotCode.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Obtient l'ID du code-barres en mode d'ajout structuré DotCode. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres. La valeur par défaut est -1. Valeur : L'ID du code-barres en mode d'ajout structuré DotCode.

**Returns:** the ID of the DotCode structured append mode barcode.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

Obtient le nombre de codes-barres en mode d'ajout structuré DotCode. La valeur par défaut est -1. Le nombre doit être compris entre 1 et 35. Valeur : Le nombre de codes-barres en mode d'ajout structuré DotCode.

**Returns:** the DotCode structured append mode barcodes count.

### hashCode() {#hashcode}

Renvoie le code de hachage pour cette instance.

**Returns:** A 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Indique si le code est utilisé pour instruire le lecteur d'interpréter les données suivantes comme des instructions d'initialisation ou de reprogrammation du lecteur de codes-barres. La valeur par défaut est false.

### toString() {#tostring}

Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `DotCodeExtendedParameters`.

**Returns:** A string that represents this `DotCodeExtendedParameters`.
