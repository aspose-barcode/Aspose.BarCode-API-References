---
title: "AztecExtendedParameters"
linktitle: "AztecExtendedParameters"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Stocke les données spéciales du code-barres Aztec reconnu. Cet exemple montre comment obtenir les valeurs brutes Aztec let generator = new BarcodeGenerator(EncodeTypes.AZTEC, \"12345\"); "
type: docs
weight: 60
url: /fr/nodejs/aspose.barcode/aztecextendedparameters/
---

## AztecExtendedParameters class

Stocke les données spéciales du code-barres Aztec reconnu. Cet exemple montre comment obtenir les valeurs brutes Aztec let generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345"); generator.save("test.png", BarcodeImageFormat.PNG);

```js
new AztecExtendedParameters()
```

**Example:**

```js
BarCodeReader reader = new BarCodeReader("test.png", null, DecodeType.AZTEC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode type: " + result.getCodeTypeName());
    console.log("BarCode codetext: " + result.getCodeText());
    console.log("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
    console.log("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
    console.log("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
    console.log("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
}
</pre>
</pre></blockquote></hr></p>
```

## Méthodes

| Nom | Description |
| --- | --- |
| [equals(obj)](#equals) | Renvoie une valeur indiquant si cette instance est égale à une valeur `AztecExtendedParameters` spécifiée. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Obtient l'ID du code-barres en mode d'ajout structuré Aztec. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres. D |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Obtient le nombre de codes-barres en mode d'ajout structuré Aztec. La valeur par défaut est 0. Le nombre doit être compris entre 1 et 26. Valeur : The |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Obtient l'ID de fichier du mode d'ajout structuré Aztec. La valeur par défaut est une chaîne vide. Valeur : The File ID of the Aztec stru |
| [hashCode()](#hashcode) | Renvoie le code de hachage pour cette instance. |
| [isReaderInitialization()](#isreaderinitialization) | Indique si le code est utilisé pour instruire le lecteur d'interpréter les données suivantes comme des instructions d'initialisation ou |
| [toString()](#tostring) | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `AztecExtendedParameters`. |

### equals(obj) {#equals}

Renvoie une valeur indiquant si cette instance est égale à une valeur `AztecExtendedParameters` spécifiée.

| Paramètre | Description |
| --- | --- |
| obj | Une valeur System.Object à comparer à cette instance. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Obtient l'ID du code-barres en mode d'ajout structuré Aztec. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres. La valeur par défaut est 0. Valeur : L'ID du code-barres du mode d'ajout structuré Aztec.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Obtient le nombre de codes-barres du mode d'ajout structuré Aztec. La valeur par défaut est 0. Le nombre doit être compris entre 1 et 26. Valeur : Le nombre de codes-barres du mode d'ajout structuré Aztec.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Obtient l'ID de fichier du mode d'ajout structuré Aztec. La valeur par défaut est une chaîne vide. Valeur : L'ID de fichier du mode d'ajout structuré Aztec.

### hashCode() {#hashcode}

Renvoie le code de hachage pour cette instance.

**Returns:** 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Indique si le code est utilisé pour instruire le lecteur d'interpréter les données suivantes comme des instructions d'initialisation ou de reprogrammation du lecteur de codes-barres. La valeur par défaut est false.

### toString() {#tostring}

Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `AztecExtendedParameters`.

**Returns:** A string that represents this `AztecExtendedParameters`.
