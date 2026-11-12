---
title: "HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Classe pour l'encodage et le décodage du texte intégré dans le code HIBC PAS."
type: docs
weight: 480
url: /fr/nodejs/aspose.barcode/hibcpascodetext/
---

## HIBCPASCodetext class

Classe pour l'encodage et le décodage du texte intégré dans le code HIBC PAS.

```js
new HIBCPASCodetext()
```

**Example:**

```js
This sample shows how to encode and decode HIBC PAS using HIBCPASCodetext.

 let complexCodetext = new HIBCPASComplexCodetext();
 complexCodetext.setDataLocation(HIBCPASDataLocation.PATIENT);
 complexCodetext.addRecord(HIBCPASDataType.LABELER_IDENTIFICATION_CODE, "A123");
 complexCodetext.addRecord(HIBCPASDataType.MANUFACTURER_SERIAL_NUMBER, "SERIAL123");
 complexCodetext.setBarcodeType(EncodeTypes.HIBC_DATA_MATRIX_PAS);
 let generator = new ComplexBarcodeGenerator(complexCodetext);
 BarCodeReader reader = new BarCodeReader(generator.generateBarCodeImage(BarCodeImageFormat.PNG), null, DecodeType.HIBC_DATA_MATRIX_PAS);
 reader.readBarCodes();
 let codetext = reader.getFoundBarCodes()[0].getCodeText();
	let readCodetext = ComplexCodetextReader.tryDecodeHIBCPAS(codetext);
 print("Data location: " + readCodetext.getDataLocation());
 print("Data type: " + readCodetext.getRecords()[0].getDataType());
 print("Data: " + readCodetext.getRecords()[0].getData());
 print("Data type: " + readCodetext.getRecords()[1].getDataType());
 print("Data: " + readCodetext.getRecords()[1].getData());
```

## Méthodes

| Nom | Description |
| --- | --- |
| [_fromMwObject()](#-frommwobject) *(static)* | Constructeur HIBCPASRecord |
| [addHIBCPASRecord(record)](#addhibcpasrecord) | Ajoute un nouvel enregistrement |
| [addRecord(dataType, data)](#addrecord) | Ajoute un nouvel enregistrement |
| [clear()](#clear) | Efface la liste des enregistrements |
| [equals(obj)](#equals) | Renvoie une valeur indiquant si cette instance est égale à une valeur `HIBCPASCodetext` spécifiée. |
| [getBarcodeType()](#getbarcodetype) | Obtient le type de code-barres. |
| [getConstructedCodetext()](#getconstructedcodetext) | Construit le codetext |
| [getDataLocation()](#getdatalocation) | Identifie l'emplacement des données. |
| [getRecords()](#getrecords) | Obtient la liste des enregistrements |
| [hashCode()](#hashcode) | Renvoie le code de hachage pour cette instance. |
| [initFromString(constructedCodetext)](#initfromstring) | Initialise l'instance à partir du codetext construit. |
| [setBarcodeType()](#setbarcodetype) | Obtient ou définit le type de code-barres. Le texte de code HIBC PAS peut être encodé en utilisant HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCData |
| [setDataLocation()](#setdatalocation) | Identifie l'emplacement des données. |

### _fromMwObject() (static) {#-frommwobject}

Constructeur HIBCPASRecord

### addHIBCPASRecord(record) {#addhibcpasrecord}

Ajoute un nouvel enregistrement

| Paramètre | Description |
| --- | --- |
| enregistrement | Enregistrement à ajouter |

### addRecord(dataType, data) {#addrecord}

Ajoute un nouvel enregistrement

| Paramètre | Description |
| --- | --- |
| dataType | Type de données |
| données | Chaîne de données |

### clear() {#clear}

Efface la liste des enregistrements

### equals(obj) {#equals}

Renvoie une valeur indiquant si cette instance est égale à une valeur `HIBCPASCodetext` spécifiée.

| Paramètre | Description |
| --- | --- |
| obj | Une valeur `HIBCPASCodetext` à comparer à cette instance. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getBarcodeType() {#getbarcodetype}

Obtient le type de code-barres.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

Construit le codetext

**Returns:** Constructed codetext

### getDataLocation() {#getdatalocation}

Identifie l'emplacement des données.

### getRecords() {#getrecords}

Obtient la liste des enregistrements

**Returns:** List of records

### hashCode() {#hashcode}

Renvoie le code de hachage pour cette instance.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Initialise l'instance à partir du codetext construit.

| Paramètre | Description |
| --- | --- |
| constructedCodetext | Codetext construit. |

### setBarcodeType() {#setbarcodetype}

Obtient ou définit le type de code-barres. Le texte de code HIBC PAS peut être encodé en utilisant HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS et HIBCQRPAS. Valeur par défaut : HIBCCode39PAS.

**Returns:** Barcode type.

### setDataLocation() {#setdatalocation}

Identifie l'emplacement des données.
