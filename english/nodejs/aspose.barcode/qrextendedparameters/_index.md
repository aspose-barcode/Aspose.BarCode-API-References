---
title: "QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Stores a QR Structured Append information of recognized barcode"
type: docs
weight: 810
url: /nodejs/aspose.barcode/qrextendedparameters/
---

## QRExtendedParameters class

Stores a QR Structured Append information of recognized barcode

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

## Methods

| Name | Description |
| --- | --- |
| [equals(obj)](#equals) | Returns a value indicating whether this instance is equal to a specified QRExtendedParameters value. |
| [getErrorLevel()](#geterrorlevel) | Reed-Solomon error correction level of recognized barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. |
| [getMicroQRVersion()](#getmicroqrversion) | Version of recognized MicroQR Code. From M1 to M4. |
| [getQRErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Reed-Solomon error correction level of recognized barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. |
| [getQRStructuredAppendModeBarCodeIndex()](#getqrstructuredappendmodebarcodeindex) ~~(deprecated)~~ | Gets the index of the QR structured append mode barcode. Index starts from 0. Default value is -1.Value: The quantity of |
| [getQRStructuredAppendModeBarCodesQuantity()](#getqrstructuredappendmodebarcodesquantity) ~~(deprecated)~~ | Gets the QR structured append mode barcodes quantity. Default value is -1.Value: The quantity of the QR structured appen |
| [getQRStructuredAppendModeParityData()](#getqrstructuredappendmodeparitydata) ~~(deprecated)~~ | Gets the QR structured append mode parity data. Default value is -1.Value: The index of the QR structured append mode ba |
| [getQRVersion()](#getqrversion) ~~(deprecated)~~ | Version of recognized QR Code. From Version1 to Version40. |
| [getRectMicroQRVersion()](#getrectmicroqrversion) | Version of recognized RectMicroQR Code. From R7x43 to R17x139. |
| [getStructuredAppendModeBarCodeIndex()](#getstructuredappendmodebarcodeindex) | Gets the index of the QR structured append mode barcode. Index starts from 0. Default value is -1. Value: The quantity o |
| [getStructuredAppendModeBarCodesQuantity()](#getstructuredappendmodebarcodesquantity) | Gets the QR structured append mode barcodes quantity. Default value is -1. Value: The quantity of the QR structured appe |
| [getStructuredAppendModeParityData()](#getstructuredappendmodeparitydata) | Gets the QR structured append mode parity data. Default value is -1. Value: The index of the QR structured append mode b |
| [getVersion()](#getversion) | Version of recognized QR Code. From Version1 to Version40. |
| [hashCode()](#hashcode) | Returns the hash code for this instance. |
| [isEmpty()](#isempty) | Tests whether all parameters has only default values Value |
| [toString()](#tostring) | Returns a human-readable string representation of this QRExtendedParameters. |

### equals(obj) {#equals}

Returns a value indicating whether this instance is equal to a specified QRExtendedParameters value.

| Parameter | Description |
| --- | --- |
| obj | An object value to compare to this instance. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getErrorLevel() {#geterrorlevel}

Reed-Solomon error correction level of recognized barcode. From low to high: LevelL, LevelM, LevelQ, LevelH.

### getMicroQRVersion() {#getmicroqrversion}

Version of recognized MicroQR Code. From M1 to M4.

**Returns:** Version of recognized MicroQR Code. From M1 to M4.

### getQRErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Reed-Solomon error correction level of recognized barcode. From low to high: LevelL, LevelM, LevelQ, LevelH.

**Returns:** Reed-Solomon error correction level of recognized barcode.

### getQRStructuredAppendModeBarCodeIndex() {#getqrstructuredappendmodebarcodeindex}

> **Deprecated.** See method description for replacement.

Gets the index of the QR structured append mode barcode. Index starts from 0. Default value is -1.Value: The quantity of the QR structured append mode barcode.

### getQRStructuredAppendModeBarCodesQuantity() {#getqrstructuredappendmodebarcodesquantity}

> **Deprecated.** See method description for replacement.

Gets the QR structured append mode barcodes quantity. Default value is -1.Value: The quantity of the QR structured append mode barcode.

### getQRStructuredAppendModeParityData() {#getqrstructuredappendmodeparitydata}

> **Deprecated.** See method description for replacement.

Gets the QR structured append mode parity data. Default value is -1.Value: The index of the QR structured append mode barcode.

### getQRVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Version of recognized QR Code. From Version1 to Version40.

**Returns:** Version of recognized QR Code

### getRectMicroQRVersion() {#getrectmicroqrversion}

Version of recognized RectMicroQR Code. From R7x43 to R17x139.

**Returns:** Version of recognized RectMicroQR Code

### getStructuredAppendModeBarCodeIndex() {#getstructuredappendmodebarcodeindex}

Gets the index of the QR structured append mode barcode. Index starts from 0. Default value is -1. Value: The quantity of the QR structured append mode barcode.

**Returns:** the index of the QR structured append mode barcode.

### getStructuredAppendModeBarCodesQuantity() {#getstructuredappendmodebarcodesquantity}

Gets the QR structured append mode barcodes quantity. Default value is -1. Value: The quantity of the QR structured append mode barcode.

**Returns:** the QR structured append mode barcodes quantity.

### getStructuredAppendModeParityData() {#getstructuredappendmodeparitydata}

Gets the QR structured append mode parity data. Default value is -1. Value: The index of the QR structured append mode barcode.

**Returns:** the QR structured append mode parity data.

### getVersion() {#getversion}

Version of recognized QR Code. From Version1 to Version40.

### hashCode() {#hashcode}

Returns the hash code for this instance.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Tests whether all parameters has only default values Value

**Returns:** true if all parameters has only default values; otherwise, `false `.

### toString() {#tostring}

Returns a human-readable string representation of this QRExtendedParameters.

**Returns:** A string that represents this QRExtendedParameters.
