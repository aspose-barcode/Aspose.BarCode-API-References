---
title: "HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Klass för kodning och avkodning av text som är inbäddad i HIBC PAS-koden."
type: docs
weight: 480
url: /sv/nodejs/aspose.barcode/hibcpascodetext/
---

## HIBCPASCodetext class

Klass för kodning och avkodning av text som är inbäddad i HIBC PAS-koden.

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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [_fromMwObject()](#-frommwobject) *(static)* | HIBCPASRecord konstruktor |
| [addHIBCPASRecord(record)](#addhibcpasrecord) | Lägger till ny post |
| [addRecord(dataType, data)](#addrecord) | Lägger till ny post |
| [clear()](#clear) | Rensar postlistan |
| [equals(obj)](#equals) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `HIBCPASCodetext`‑värde. |
| [getBarcodeType()](#getbarcodetype) | Hämtar streckkodstyp. |
| [getConstructedCodetext()](#getconstructedcodetext) | Skapar kodtext |
| [getDataLocation()](#getdatalocation) | Identifierar dataplats. |
| [getRecords()](#getrecords) | Hämtar postlistan |
| [hashCode()](#hashcode) | Returnerar hashkoden för detta objekt. |
| [initFromString(constructedCodetext)](#initfromstring) | Initierar objektet från konstruerad kodtext. |
| [setBarcodeType()](#setbarcodetype) | Hämtar eller anger streckkodstyp. HIBC PAS‑kodtext kan kodas med HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCData |
| [setDataLocation()](#setdatalocation) | Identifierar dataplats. |

### _fromMwObject() (static) {#-frommwobject}

HIBCPASRecord konstruktor

### addHIBCPASRecord(record) {#addhibcpasrecord}

Lägger till ny post

| Parameter | Beskrivning |
| --- | --- |
| post | Post som ska läggas till |

### addRecord(dataType, data) {#addrecord}

Lägger till ny post

| Parameter | Beskrivning |
| --- | --- |
| dataType | Typ av data |
| data | Data-sträng |

### clear() {#clear}

Rensar postlistan

### equals(obj) {#equals}

Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `HIBCPASCodetext`‑värde.

| Parameter | Beskrivning |
| --- | --- |
| obj | Ett `HIBCPASCodetext`‑värde att jämföra med detta objekt. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getBarcodeType() {#getbarcodetype}

Hämtar streckkodstyp.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

Skapar kodtext

**Returns:** Constructed codetext

### getDataLocation() {#getdatalocation}

Identifierar dataplats.

### getRecords() {#getrecords}

Hämtar postlistan

**Returns:** List of records

### hashCode() {#hashcode}

Returnerar hashkoden för detta objekt.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Initierar objektet från konstruerad kodtext.

| Parameter | Beskrivning |
| --- | --- |
| constructedCodetext | Konstruerad kodtext. |

### setBarcodeType() {#setbarcodetype}

Hämtar eller anger streckkodstyp. HIBC PAS‑kodtext kan kodas med HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS och HIBCQRPAS‑kodningstyper. Standardvärde: HIBCCode39PAS.

**Returns:** Barcode type.

### setDataLocation() {#setdatalocation}

Identifierar dataplats.
