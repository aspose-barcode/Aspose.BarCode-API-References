---
title: "QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Stocke une information QR Structured Append du code-barres reconnu"
type: docs
weight: 810
url: /fr/nodejs/aspose.barcode/qrextendedparameters/
---

## QRExtendedParameters class

Stocke une information QR Structured Append du code-barres reconnu

```js
new QRExtendedParameters()
```

**Example:**

```js
//This sample shows how to get QR Structured Append data

let reader = new BarCodeReader("test.png", null,  DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
   console.log("QR Structured Append Index: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodeIndex());
   console.log("QR Structured Append ParityData: " + result.getExtended().getQR().getQRStructuredAppendModeParityData());
}
```

## Méthodes

| Nom | Description |
| --- | --- |
| [equals(obj)](#equals) | Renvoie une valeur indiquant si cette instance est égale à une valeur QRExtendedParameters spécifiée. |
| [getErrorLevel()](#geterrorlevel) | Niveau de correction d'erreur Reed‑Solomon du code-barres reconnu. Du plus bas au plus élevé : LevelL, LevelM, LevelQ, LevelH. |
| [getMicroQRVersion()](#getmicroqrversion) | Version du MicroQR Code reconnu. De M1 à M4. |
| [getQRErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Niveau de correction d'erreur Reed‑Solomon du code-barres reconnu. Du plus bas au plus élevé : LevelL, LevelM, LevelQ, LevelH. |
| [getQRStructuredAppendModeBarCodeIndex()](#getqrstructuredappendmodebarcodeindex) ~~(deprecated)~~ | Obtient l'index du code-barres en mode d'ajout structuré QR. L'index commence à 0. La valeur par défaut est -1. Valeur : La quantité de |
| [getQRStructuredAppendModeBarCodesQuantity()](#getqrstructuredappendmodebarcodesquantity) ~~(deprecated)~~ | Obtient la quantité de codes-barres en mode d'ajout structuré QR. Valeur par défaut : -1. Valeur : La quantité du QR structuré appen |
| [getQRStructuredAppendModeParityData()](#getqrstructuredappendmodeparitydata) ~~(deprecated)~~ | Obtient les données de parité du mode d'ajout structuré QR. Valeur par défaut est -1. Valeur : L'index du QR structured append mode ba |
| [getQRVersion()](#getqrversion) ~~(deprecated)~~ | Version du QR Code reconnu. De Version1 à Version40. |
| [getRectMicroQRVersion()](#getrectmicroqrversion) | Version du RectMicroQR Code reconnu. De R7x43 à R17x139. |
| [getStructuredAppendModeBarCodeIndex()](#getstructuredappendmodebarcodeindex) | Obtient l'index du code-barres en mode d'ajout structuré QR. L'index commence à 0. Valeur par défaut : -1. Valeur : La quantité o |
| [getStructuredAppendModeBarCodesQuantity()](#getstructuredappendmodebarcodesquantity) | Obtient la quantité de codes-barres en mode d'ajout structuré QR. Valeur par défaut : -1. Valeur : La quantité du QR structuré appe |
| [getStructuredAppendModeParityData()](#getstructuredappendmodeparitydata) | Obtient les données de parité du mode d'ajout structuré QR. Valeur par défaut : -1. Valeur : L'index du QR structured append mode b |
| [getVersion()](#getversion) | Version du QR Code reconnu. De Version1 à Version40. |
| [hashCode()](#hashcode) | Renvoie le code de hachage pour cette instance. |
| [isEmpty()](#isempty) | Teste si tous les paramètres n'ont que les valeurs par défaut Valeur |
| [toString()](#tostring) | Renvoie une représentation sous forme de chaîne lisible de ce QRExtendedParameters. |

### equals(obj) {#equals}

Renvoie une valeur indiquant si cette instance est égale à une valeur QRExtendedParameters spécifiée.

| Paramètre | Description |
| --- | --- |
| obj | Une valeur d'objet à comparer à cette instance. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getErrorLevel() {#geterrorlevel}

Niveau de correction d'erreur Reed‑Solomon du code-barres reconnu. Du plus bas au plus élevé : LevelL, LevelM, LevelQ, LevelH.

### getMicroQRVersion() {#getmicroqrversion}

Version du MicroQR Code reconnu. De M1 à M4.

**Returns:** Version of recognized MicroQR Code. From M1 to M4.

### getQRErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Niveau de correction d'erreur Reed‑Solomon du code-barres reconnu. Du plus bas au plus élevé : LevelL, LevelM, LevelQ, LevelH.

**Returns:** Reed-Solomon error correction level of recognized barcode.

### getQRStructuredAppendModeBarCodeIndex() {#getqrstructuredappendmodebarcodeindex}

> **Deprecated.** See method description for replacement.

Obtient l'index du code-barres en mode d'ajout structuré QR. L'index commence à 0. La valeur par défaut est -1.Valeur : la quantité du code-barres en mode d'ajout structuré QR.

### getQRStructuredAppendModeBarCodesQuantity() {#getqrstructuredappendmodebarcodesquantity}

> **Deprecated.** See method description for replacement.

Obtient la quantité de codes-barres en mode d'ajout structuré QR. La valeur par défaut est -1.Valeur : la quantité du code-barres en mode d'ajout structuré QR.

### getQRStructuredAppendModeParityData() {#getqrstructuredappendmodeparitydata}

> **Deprecated.** See method description for replacement.

Obtient les données de parité du mode d'ajout structuré QR. La valeur par défaut est -1.Valeur : l'index du code-barres en mode d'ajout structuré QR.

### getQRVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Version du QR Code reconnu. De Version1 à Version40.

**Returns:** Version of recognized QR Code

### getRectMicroQRVersion() {#getrectmicroqrversion}

Version du RectMicroQR Code reconnu. De R7x43 à R17x139.

**Returns:** Version of recognized RectMicroQR Code

### getStructuredAppendModeBarCodeIndex() {#getstructuredappendmodebarcodeindex}

Obtient l'index du code-barres en mode d'ajout structuré QR. L'index commence à 0. La valeur par défaut est -1. Valeur : la quantité du code-barres en mode d'ajout structuré QR.

**Returns:** the index of the QR structured append mode barcode.

### getStructuredAppendModeBarCodesQuantity() {#getstructuredappendmodebarcodesquantity}

Obtient la quantité de codes-barres en mode d'ajout structuré QR. La valeur par défaut est -1. Valeur : la quantité du code-barres en mode d'ajout structuré QR.

**Returns:** the QR structured append mode barcodes quantity.

### getStructuredAppendModeParityData() {#getstructuredappendmodeparitydata}

Obtient les données de parité du mode d'ajout structuré QR. La valeur par défaut est -1. Valeur : l'index du code-barres en mode d'ajout structuré QR.

**Returns:** the QR structured append mode parity data.

### getVersion() {#getversion}

Version du QR Code reconnu. De Version1 à Version40.

### hashCode() {#hashcode}

Renvoie le code de hachage pour cette instance.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Teste si tous les paramètres n'ont que les valeurs par défaut Valeur

**Returns:** true if all parameters has only default values; otherwise, `false `.

### toString() {#tostring}

Renvoie une représentation sous forme de chaîne lisible de ce QRExtendedParameters.

**Returns:** A string that represents this QRExtendedParameters.
