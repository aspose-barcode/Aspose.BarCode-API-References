---
title: "QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Lagrar QR Structured Append‑information för igenkänd streckkod"
type: docs
weight: 810
url: /sv/nodejs/aspose.barcode/qrextendedparameters/
---

## QRExtendedParameters class

Lagrar QR Structured Append‑information för igenkänd streckkod

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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [equals(obj)](#equals) | Returnerar ett värde som indikerar om denna instans är lika med ett specificerat QRExtendedParameters-värde. |
| [getErrorLevel()](#geterrorlevel) | Reed-Solomon-felkorrigeringsnivå för identifierad streckkod. Från låg till hög: LevelL, LevelM, LevelQ, LevelH. |
| [getMicroQRVersion()](#getmicroqrversion) | Version av identifierad MicroQR Code. Från M1 till M4. |
| [getQRErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Reed-Solomon-felkorrigeringsnivå för identifierad streckkod. Från låg till hög: LevelL, LevelM, LevelQ, LevelH. |
| [getQRStructuredAppendModeBarCodeIndex()](#getqrstructuredappendmodebarcodeindex) ~~(deprecated)~~ | Hämtar indexet för QR structured append mode-streckkoden. Indexet startar från 0. Standardvärde är -1.Värde: Kvantiteten av |
| [getQRStructuredAppendModeBarCodesQuantity()](#getqrstructuredappendmodebarcodesquantity) ~~(deprecated)~~ | Hämtar kvantiteten av QR structured append mode-streckkoder. Standardvärde är -1.Värde: Kvantiteten av QR structured appen |
| [getQRStructuredAppendModeParityData()](#getqrstructuredappendmodeparitydata) ~~(deprecated)~~ | Hämtar parity-data för QR structured append mode. Standardvärde är -1.Värde: Indexet för QR structured append mode ba |
| [getQRVersion()](#getqrversion) ~~(deprecated)~~ | Version av identifierad QR Code. Från Version1 till Version40. |
| [getRectMicroQRVersion()](#getrectmicroqrversion) | Version av identifierad RectMicroQR Code. Från R7x43 till R17x139. |
| [getStructuredAppendModeBarCodeIndex()](#getstructuredappendmodebarcodeindex) | Hämtar indexet för QR structured append mode-streckkoden. Indexet startar från 0. Standardvärde är -1. Värde: Kvantiteten o |
| [getStructuredAppendModeBarCodesQuantity()](#getstructuredappendmodebarcodesquantity) | Hämtar kvantiteten av QR structured append mode-streckkoder. Standardvärde är -1. Värde: Kvantiteten av QR structured appe |
| [getStructuredAppendModeParityData()](#getstructuredappendmodeparitydata) | Hämtar parity-data för QR structured append mode. Standardvärde är -1. Värde: Indexet för QR structured append mode b |
| [getVersion()](#getversion) | Version av identifierad QR Code. Från Version1 till Version40. |
| [hashCode()](#hashcode) | Returnerar hashkoden för detta objekt. |
| [isEmpty()](#isempty) | Testar om alla parametrar endast har standardvärden Värde |
| [toString()](#tostring) | Returnerar en människoläsbar strängrepresentation av dessa QRExtendedParameters. |

### equals(obj) {#equals}

Returnerar ett värde som indikerar om denna instans är lika med ett specificerat QRExtendedParameters-värde.

| Parameter | Beskrivning |
| --- | --- |
| obj | Ett objektvärde att jämföra med detta objekt. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getErrorLevel() {#geterrorlevel}

Reed-Solomon-felkorrigeringsnivå för identifierad streckkod. Från låg till hög: LevelL, LevelM, LevelQ, LevelH.

### getMicroQRVersion() {#getmicroqrversion}

Version av identifierad MicroQR Code. Från M1 till M4.

**Returns:** Version of recognized MicroQR Code. From M1 to M4.

### getQRErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Reed-Solomon-felkorrigeringsnivå för identifierad streckkod. Från låg till hög: LevelL, LevelM, LevelQ, LevelH.

**Returns:** Reed-Solomon error correction level of recognized barcode.

### getQRStructuredAppendModeBarCodeIndex() {#getqrstructuredappendmodebarcodeindex}

> **Deprecated.** See method description for replacement.

Hämtar indexet för QR structured append mode-streckkoden. Indexet startar från 0. Standardvärde är -1.Värde: Kvantiteten av QR structured append mode-streckkoden.

### getQRStructuredAppendModeBarCodesQuantity() {#getqrstructuredappendmodebarcodesquantity}

> **Deprecated.** See method description for replacement.

Hämtar kvantiteten av QR structured append mode-streckkoder. Standardvärde är -1.Värde: Kvantiteten av QR structured append mode-streckkoden.

### getQRStructuredAppendModeParityData() {#getqrstructuredappendmodeparitydata}

> **Deprecated.** See method description for replacement.

Hämtar parity-data för QR structured append mode. Standardvärde är -1.Värde: Indexet för QR structured append mode-streckkoden.

### getQRVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Version av identifierad QR Code. Från Version1 till Version40.

**Returns:** Version of recognized QR Code

### getRectMicroQRVersion() {#getrectmicroqrversion}

Version av identifierad RectMicroQR Code. Från R7x43 till R17x139.

**Returns:** Version of recognized RectMicroQR Code

### getStructuredAppendModeBarCodeIndex() {#getstructuredappendmodebarcodeindex}

Hämtar indexet för QR structured append mode-streckkoden. Indexet startar från 0. Standardvärde är -1. Värde: Kvantiteten av QR structured append mode-streckkoden.

**Returns:** the index of the QR structured append mode barcode.

### getStructuredAppendModeBarCodesQuantity() {#getstructuredappendmodebarcodesquantity}

Hämtar kvantiteten av QR structured append mode-streckkoder. Standardvärde är -1. Värde: Kvantiteten av QR structured append mode-streckkoden.

**Returns:** the QR structured append mode barcodes quantity.

### getStructuredAppendModeParityData() {#getstructuredappendmodeparitydata}

Hämtar parity-data för QR structured append mode. Standardvärde är -1. Värde: Indexet för QR structured append mode-streckkoden.

**Returns:** the QR structured append mode parity data.

### getVersion() {#getversion}

Version av identifierad QR Code. Från Version1 till Version40.

### hashCode() {#hashcode}

Returnerar hashkoden för detta objekt.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Testar om alla parametrar endast har standardvärden Värde

**Returns:** true if all parameters has only default values; otherwise, `false `.

### toString() {#tostring}

Returnerar en människoläsbar strängrepresentation av dessa QRExtendedParameters.

**Returns:** A string that represents this QRExtendedParameters.
