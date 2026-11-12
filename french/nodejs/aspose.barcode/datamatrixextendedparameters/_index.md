---
title: "DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Stocke des données spéciales d'un code-barres DataMatrix reconnu Cet exemple montre comment obtenir les valeurs brutes DataMatrix let generator = new BarcodeGenerator(EncodeTypes.DATA_MA"
type: docs
weight: 350
url: /fr/nodejs/aspose.barcode/datamatrixextendedparameters/
---

## DataMatrixExtendedParameters class

Stocke des données spéciales d'un code-barres DataMatrix reconnu Cet exemple montre comment obtenir les valeurs brutes DataMatrix let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345")) generator.save("test.png", BarcodeImageFormat.PNG); let reader = new BarCodeReader("test.png", null, DecodeType.DATA_MATRIX)) let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode type: " + result.getCodeTypeName()); console.log("BarCode codetext: " + result.getCodeText()); console.log("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId()); console.log("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount()); console.log("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId()); console.log("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming()); }

```js
new DataMatrixExtendedParameters()
```

## Méthodes

| Nom | Description |
| --- | --- |
| [equals(obj)](#equals) | Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée `DataMatrixExtendedParameters`. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Obtient l'ID du code-barres DataMatrix en mode structured append. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres cou |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Obtient le nombre de codes-barres en mode structured append du DataMatrix. La valeur par défaut est -1. Le nombre doit être compris entre 1 et 35. Valu |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Obtient l'ID du code-barres DataMatrix en mode structured append. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres cou |
| [hashCode()](#hashcode) | Renvoie le code de hachage pour cette instance. |
| [isReaderProgramming()](#isreaderprogramming) | Indique si le code est utilisé pour instruire le lecteur d'interpréter les données suivantes comme des instructions d'initialisation ou |
| [toString()](#tostring) | Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `DataMatrixExtendedParameters`. |

### equals(obj) {#equals}

Renvoie une valeur indiquant si cette instance est égale à une valeur spécifiée `DataMatrixExtendedParameters`.

| Paramètre | Description |
| --- | --- |
| obj | Une valeur System.Object à comparer à cette instance. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Obtient l'ID du code-barres DataMatrix en mode structured append. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres. La valeur par défaut est -1. Valeur : l'ID du code-barres DataMatrix en mode structured append.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Obtient le nombre de codes-barres en mode d'ajout structuré DataMatrix. La valeur par défaut est -1. Le nombre doit être compris entre 1 et 35. Valeur : Le nombre de codes-barres en mode d'ajout structuré DataMatrix.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Obtient l'ID du code-barres DataMatrix en mode structured append. L'ID commence à 1 et doit être inférieur ou égal au nombre de codes-barres. La valeur par défaut est -1. Valeur : l'ID du code-barres DataMatrix en mode structured append.

### hashCode() {#hashcode}

Renvoie le code de hachage pour cette instance.

**Returns:** A 32-bit signed integer hash code.

### isReaderProgramming() {#isreaderprogramming}

Indique si le code est utilisé pour instruire le lecteur d'interpréter les données suivantes comme des instructions d'initialisation ou de reprogrammation du lecteur de codes-barres. La valeur par défaut est false.

### toString() {#tostring}

Renvoie une représentation sous forme de chaîne lisible par l'homme de ce `DataMatrixExtendedParameters`.

**Returns:** A string that represents this `DataMatrixExtendedParameters`.
