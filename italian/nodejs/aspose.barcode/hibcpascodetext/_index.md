---
title: "HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Classe per la codifica e decodifica del testo incorporato nel codice HIBC PAS."
type: docs
weight: 480
url: /it/nodejs/aspose.barcode/hibcpascodetext/
---

## HIBCPASCodetext class

Classe per la codifica e decodifica del testo incorporato nel codice HIBC PAS.

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

## Metodi

| Nome | Descrizione |
| --- | --- |
| [_fromMwObject()](#-frommwobject) *(static)* | Costruttore HIBCPASRecord |
| [addHIBCPASRecord(record)](#addhibcpasrecord) | Aggiunge un nuovo record |
| [addRecord(dataType, data)](#addrecord) | Aggiunge un nuovo record |
| [clear()](#clear) | Cancella l'elenco dei record |
| [equals(obj)](#equals) | Restituisce un valore che indica se questa istanza è uguale a un valore `HIBCPASCodetext` specificato. |
| [getBarcodeType()](#getbarcodetype) | Ottiene il tipo di codice a barre. |
| [getConstructedCodetext()](#getconstructedcodetext) | Costruisce il codetext |
| [getDataLocation()](#getdatalocation) | Identifica la posizione dei dati. |
| [getRecords()](#getrecords) | Ottiene l'elenco dei record |
| [hashCode()](#hashcode) | Restituisce il codice hash per questa istanza. |
| [initFromString(constructedCodetext)](#initfromstring) | Inizializza l'istanza dal codetext costruito. |
| [setBarcodeType()](#setbarcodetype) | Ottiene o imposta il tipo di codice a barre. Il codetext HIBC PAS può essere codificato usando HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCData |
| [setDataLocation()](#setdatalocation) | Identifica la posizione dei dati. |

### _fromMwObject() (static) {#-frommwobject}

Costruttore HIBCPASRecord

### addHIBCPASRecord(record) {#addhibcpasrecord}

Aggiunge un nuovo record

| Parametro | Descrizione |
| --- | --- |
| record | Record da aggiungere |

### addRecord(dataType, data) {#addrecord}

Aggiunge un nuovo record

| Parametro | Descrizione |
| --- | --- |
| dataType | Tipo di dati |
| dati | Stringa di dati |

### clear() {#clear}

Cancella l'elenco dei record

### equals(obj) {#equals}

Restituisce un valore che indica se questa istanza è uguale a un valore `HIBCPASCodetext` specificato.

| Parametro | Descrizione |
| --- | --- |
| obj | Un valore `HIBCPASCodetext` da confrontare con questa istanza. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getBarcodeType() {#getbarcodetype}

Ottiene il tipo di codice a barre.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

Costruisce il codetext

**Returns:** Constructed codetext

### getDataLocation() {#getdatalocation}

Identifica la posizione dei dati.

### getRecords() {#getrecords}

Ottiene l'elenco dei record

**Returns:** List of records

### hashCode() {#hashcode}

Restituisce il codice hash per questa istanza.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Inizializza l'istanza dal codetext costruito.

| Parametro | Descrizione |
| --- | --- |
| constructedCodetext | Codetext costruito. |

### setBarcodeType() {#setbarcodetype}

Ottiene o imposta il tipo di codice a barre. Il codetext HIBC PAS può essere codificato usando i tipi di codifica HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS e HIBCQRPAS. Valore predefinito: HIBCCode39PAS.

**Returns:** Barcode type.

### setDataLocation() {#setdatalocation}

Identifica la posizione dei dati.
