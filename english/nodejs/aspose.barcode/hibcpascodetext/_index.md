---
title: "HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Class for encoding and decoding the text embedded in the HIBC PAS code."
type: docs
weight: 480
url: /nodejs/aspose.barcode/hibcpascodetext/
---

## HIBCPASCodetext class

Class for encoding and decoding the text embedded in the HIBC PAS code.

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

## Methods

| Name | Description |
| --- | --- |
| [_fromMwObject()](#-frommwobject) *(static)* | HIBCPASRecord constructor |
| [addHIBCPASRecord(record)](#addhibcpasrecord) | Adds new record |
| [addRecord(dataType, data)](#addrecord) | Adds new record |
| [clear()](#clear) | Clears records list |
| [equals(obj)](#equals) | Returns a value indicating whether this instance is equal to a specified `HIBCPASCodetext` value. |
| [getBarcodeType()](#getbarcodetype) | Gets barcode type. |
| [getConstructedCodetext()](#getconstructedcodetext) | Constructs codetext |
| [getDataLocation()](#getdatalocation) | Identifies data location. |
| [getRecords()](#getrecords) | Gets records list |
| [hashCode()](#hashcode) | Returns the hash code for this instance. |
| [initFromString(constructedCodetext)](#initfromstring) | Initializes instance from constructed codetext. |
| [setBarcodeType()](#setbarcodetype) | Gets or sets barcode type. HIBC PAS codetext can be encoded using HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCData |
| [setDataLocation()](#setdatalocation) | Identifies data location. |

### _fromMwObject() (static) {#-frommwobject}

HIBCPASRecord constructor

### addHIBCPASRecord(record) {#addhibcpasrecord}

Adds new record

| Parameter | Description |
| --- | --- |
| record | Record to be added |

### addRecord(dataType, data) {#addrecord}

Adds new record

| Parameter | Description |
| --- | --- |
| dataType | Type of data |
| data | Data string |

### clear() {#clear}

Clears records list

### equals(obj) {#equals}

Returns a value indicating whether this instance is equal to a specified `HIBCPASCodetext` value.

| Parameter | Description |
| --- | --- |
| obj | An `HIBCPASCodetext` value to compare to this instance. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getBarcodeType() {#getbarcodetype}

Gets barcode type.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

Constructs codetext

**Returns:** Constructed codetext

### getDataLocation() {#getdatalocation}

Identifies data location.

### getRecords() {#getrecords}

Gets records list

**Returns:** List of records

### hashCode() {#hashcode}

Returns the hash code for this instance.

**Returns:** A 32-bit signed integer hash code.

### initFromString(constructedCodetext) {#initfromstring}

Initializes instance from constructed codetext.

| Parameter | Description |
| --- | --- |
| constructedCodetext | Constructed codetext. |

### setBarcodeType() {#setbarcodetype}

Gets or sets barcode type. HIBC PAS codetext can be encoded using HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS and HIBCQRPAS encode types. Default value: HIBCCode39PAS.

**Returns:** Barcode type.

### setDataLocation() {#setdatalocation}

Identifies data location.
