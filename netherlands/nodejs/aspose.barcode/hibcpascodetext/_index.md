---
title: "HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Klasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC PAS-code."
type: docs
weight: 480
url: /nl/nodejs/aspose.barcode/hibcpascodetext/
---

## HIBCPASCodetext class

Klasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC PAS-code.

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

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [_fromMwObject()](#-frommwobject) *(static)* | HIBCPASRecord‑constructor |
| [addHIBCPASRecord(record)](#addhibcpasrecord) | Voegt een nieuw record toe |
| [addRecord(dataType, data)](#addrecord) | Voegt een nieuw record toe |
| [clear()](#clear) | Leegt de lijst met records |
| [equals(obj)](#equals) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `HIBCPASCodetext`-waarde. |
| [getBarcodeType()](#getbarcodetype) | Haalt barcode type op. |
| [getConstructedCodetext()](#getconstructedcodetext) | Construeert codetext |
| [getDataLocation()](#getdatalocation) | Identificeert de gegevenslocatie. |
| [getRecords()](#getrecords) | Haalt de lijst met records op |
| [hashCode()](#hashcode) | Retourneert de hashcode voor deze instantie. |
| [initFromString(constructedCodetext)](#initfromstring) | Initialiseert instantie vanuit geconstrueerde codetext. |
| [setBarcodeType()](#setbarcodetype) | Haalt het type barcode op of stelt het in. HIBC PAS-codetext kan worden gecodeerd met HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCData |
| [setDataLocation()](#setdatalocation) | Identificeert de gegevenslocatie. |

### _fromMwObject() (static) {#-frommwobject}

HIBCPASRecord‑constructor

### addHIBCPASRecord(record) {#addhibcpasrecord}

Voegt een nieuw record toe

| Parameter | Beschrijving |
| --- | --- |
| record | Toe te voegen record |

### addRecord(dataType, data) {#addrecord}

Voegt een nieuw record toe

| Parameter | Beschrijving |
| --- | --- |
| dataType | Gegevenstype |
| data | Gegevensreeks |

### clear() {#clear}

Leegt de lijst met records

### equals(obj) {#equals}

Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven `HIBCPASCodetext`-waarde.

| Parameter | Beschrijving |
| --- | --- |
| obj | Een `HIBCPASCodetext`-waarde om te vergelijken met deze instantie. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getBarcodeType() {#getbarcodetype}

Haalt barcode type op.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

Construeert codetext

**Returns:** Constructed codetext

### getDataLocation() {#getdatalocation}

Identificeert de gegevenslocatie.

### getRecords() {#getrecords}

Haalt de lijst met records op

**Returns:** List of records

### hashCode() {#hashcode}

Retourneert de hashcode voor deze instantie.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Initialiseert instantie vanuit geconstrueerde codetext.

| Parameter | Beschrijving |
| --- | --- |
| constructedCodetext | Geconstrueerde codetext. |

### setBarcodeType() {#setbarcodetype}

Haalt het type barcode op of stelt het in. HIBC PAS-codetext kan worden gecodeerd met HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS en HIBCQRPAS-coderingstypen. Standaardwaarde: HIBCCode39PAS.

**Returns:** Barcode type.

### setDataLocation() {#setdatalocation}

Identificeert de gegevenslocatie.
