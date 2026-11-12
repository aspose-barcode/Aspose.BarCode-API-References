---
title: "HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Klasse zum Kodieren und Dekodieren des in den HIBC PAS‑Code eingebetteten Textes."
type: docs
weight: 480
url: /de/nodejs/aspose.barcode/hibcpascodetext/
---

## HIBCPASCodetext class

Klasse zum Kodieren und Dekodieren des in den HIBC PAS‑Code eingebetteten Textes.

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

| Name | Beschreibung |
| --- | --- |
| [_fromMwObject()](#-frommwobject) *(static)* | HIBCPASRecord Konstruktor |
| [addHIBCPASRecord(record)](#addhibcpasrecord) | Fügt einen neuen Datensatz hinzu |
| [addRecord(dataType, data)](#addrecord) | Fügt einen neuen Datensatz hinzu |
| [clear()](#clear) | Leert die Datensatzliste |
| [equals(obj)](#equals) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `HIBCPASCodetext`-Wert entspricht. |
| [getBarcodeType()](#getbarcodetype) | Ermittelt den Barcode-Typ. |
| [getConstructedCodetext()](#getconstructedcodetext) | Erstellt Codetext |
| [getDataLocation()](#getdatalocation) | Identifiziert den Datenort. |
| [getRecords()](#getrecords) | Liefert die Datensatzliste |
| [hashCode()](#hashcode) | Gibt den Hashcode für diese Instanz zurück. |
| [initFromString(constructedCodetext)](#initfromstring) | Initialisiert die Instanz aus dem erstellten Codetext. |
| [setBarcodeType()](#setbarcodetype) | Liest oder setzt den Barcode-Typ. HIBC PAS Codetext kann mit HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCData codiert werden. |
| [setDataLocation()](#setdatalocation) | Identifiziert den Datenort. |

### _fromMwObject() (static) {#-frommwobject}

HIBCPASRecord Konstruktor

### addHIBCPASRecord(record) {#addhibcpasrecord}

Fügt einen neuen Datensatz hinzu

| Parameter | Beschreibung |
| --- | --- |
| record | Datensatz, der hinzugefügt werden soll |

### addRecord(dataType, data) {#addrecord}

Fügt einen neuen Datensatz hinzu

| Parameter | Beschreibung |
| --- | --- |
| dataType | Datentyp |
| data | Datenzeichenfolge |

### clear() {#clear}

Leert die Datensatzliste

### equals(obj) {#equals}

Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `HIBCPASCodetext`-Wert entspricht.

| Parameter | Beschreibung |
| --- | --- |
| obj | Ein `HIBCPASCodetext`-Wert zum Vergleich mit dieser Instanz. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getBarcodeType() {#getbarcodetype}

Ermittelt den Barcode-Typ.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

Erstellt Codetext

**Returns:** Constructed codetext

### getDataLocation() {#getdatalocation}

Identifiziert den Datenort.

### getRecords() {#getrecords}

Liefert die Datensatzliste

**Returns:** List of records

### hashCode() {#hashcode}

Gibt den Hashcode für diese Instanz zurück.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Initialisiert die Instanz aus dem erstellten Codetext.

| Parameter | Beschreibung |
| --- | --- |
| constructedCodetext | Erstellter Codetext. |

### setBarcodeType() {#setbarcodetype}

Liest oder setzt den Barcode-Typ. HIBC PAS Codetext kann mit den Kodierungstypen HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS und HIBCQRPAS codiert werden. Standardwert: HIBCCode39PAS.

**Returns:** Barcode type.

### setDataLocation() {#setdatalocation}

Identifiziert den Datenort.
