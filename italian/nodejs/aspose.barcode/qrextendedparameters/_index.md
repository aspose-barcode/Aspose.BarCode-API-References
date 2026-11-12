---
title: "QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Memorizza informazioni QR Structured Append del codice a barre riconosciuto"
type: docs
weight: 810
url: /it/nodejs/aspose.barcode/qrextendedparameters/
---

## QRExtendedParameters class

Memorizza informazioni QR Structured Append del codice a barre riconosciuto

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

## Metodi

| Nome | Descrizione |
| --- | --- |
| [equals(obj)](#equals) | Restituisce un valore che indica se questa istanza è uguale a un valore QRExtendedParameters specificato. |
| [getErrorLevel()](#geterrorlevel) | Livello di correzione errori Reed-Solomon del codice a barre riconosciuto. Da basso a alto: LevelL, LevelM, LevelQ, LevelH. |
| [getMicroQRVersion()](#getmicroqrversion) | Versione del MicroQR Code riconosciuto. Da M1 a M4. |
| [getQRErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Livello di correzione errori Reed-Solomon del codice a barre riconosciuto. Da basso a alto: LevelL, LevelM, LevelQ, LevelH. |
| [getQRStructuredAppendModeBarCodeIndex()](#getqrstructuredappendmodebarcodeindex) ~~(deprecated)~~ | Ottiene l'indice del codice a barre in modalità QR structured append. L'indice inizia da 0. Il valore predefinito è -1. Valore: La quantità di |
| [getQRStructuredAppendModeBarCodesQuantity()](#getqrstructuredappendmodebarcodesquantity) ~~(deprecated)~~ | Ottiene la quantità di codici a barre in modalità QR structured append. Il valore predefinito è -1. Valore: La quantità del QR structured appen |
| [getQRStructuredAppendModeParityData()](#getqrstructuredappendmodeparitydata) ~~(deprecated)~~ | Ottiene i dati di parità della modalità QR structured append. Il valore predefinito è -1. Valore: L'indice della modalità QR structured append ba |
| [getQRVersion()](#getqrversion) ~~(deprecated)~~ | Versione del QR Code riconosciuto. Da Version1 a Version40. |
| [getRectMicroQRVersion()](#getrectmicroqrversion) | Versione del RectMicroQR Code riconosciuto. Da R7x43 a R17x139. |
| [getStructuredAppendModeBarCodeIndex()](#getstructuredappendmodebarcodeindex) | Ottiene l'indice del codice a barre in modalità QR structured append. L'indice inizia da 0. Il valore predefinito è -1. Valore: La quantità o |
| [getStructuredAppendModeBarCodesQuantity()](#getstructuredappendmodebarcodesquantity) | Ottiene la quantità di codici a barre in modalità QR structured append. Il valore predefinito è -1. Valore: La quantità del QR structured appe |
| [getStructuredAppendModeParityData()](#getstructuredappendmodeparitydata) | Ottiene i dati di parità della modalità QR structured append. Il valore predefinito è -1. Valore: L'indice della modalità QR structured append b |
| [getVersion()](#getversion) | Versione del QR Code riconosciuto. Da Version1 a Version40. |
| [hashCode()](#hashcode) | Restituisce il codice hash per questa istanza. |
| [isEmpty()](#isempty) | Verifica se tutti i parametri hanno solo valori predefiniti Valore |
| [toString()](#tostring) | Restituisce una rappresentazione della stringa leggibile dall'uomo di questo QRExtendedParameters. |

### equals(obj) {#equals}

Restituisce un valore che indica se questa istanza è uguale a un valore QRExtendedParameters specificato.

| Parametro | Descrizione |
| --- | --- |
| obj | Un valore oggetto da confrontare con questa istanza. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getErrorLevel() {#geterrorlevel}

Livello di correzione errori Reed-Solomon del codice a barre riconosciuto. Da basso a alto: LevelL, LevelM, LevelQ, LevelH.

### getMicroQRVersion() {#getmicroqrversion}

Versione del MicroQR Code riconosciuto. Da M1 a M4.

**Returns:** Version of recognized MicroQR Code. From M1 to M4.

### getQRErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Livello di correzione errori Reed-Solomon del codice a barre riconosciuto. Da basso a alto: LevelL, LevelM, LevelQ, LevelH.

**Returns:** Reed-Solomon error correction level of recognized barcode.

### getQRStructuredAppendModeBarCodeIndex() {#getqrstructuredappendmodebarcodeindex}

> **Deprecated.** See method description for replacement.

Restituisce l'indice del codice a barre QR in modalità append strutturata. L'indice inizia da 0. Il valore predefinito è -1.Valore: La quantità del codice a barre QR in modalità append strutturata.

### getQRStructuredAppendModeBarCodesQuantity() {#getqrstructuredappendmodebarcodesquantity}

> **Deprecated.** See method description for replacement.

Restituisce la quantità di codici a barre QR in modalità append strutturata. Il valore predefinito è -1.Valore: La quantità del codice a barre QR in modalità append strutturata.

### getQRStructuredAppendModeParityData() {#getqrstructuredappendmodeparitydata}

> **Deprecated.** See method description for replacement.

Restituisce i dati di parità della modalità append strutturata QR. Il valore predefinito è -1.Valore: L'indice del codice a barre QR in modalità append strutturata.

### getQRVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Versione del QR Code riconosciuto. Da Version1 a Version40.

**Returns:** Version of recognized QR Code

### getRectMicroQRVersion() {#getrectmicroqrversion}

Versione del RectMicroQR Code riconosciuto. Da R7x43 a R17x139.

**Returns:** Version of recognized RectMicroQR Code

### getStructuredAppendModeBarCodeIndex() {#getstructuredappendmodebarcodeindex}

Restituisce l'indice del codice a barre QR in modalità append strutturata. L'indice inizia da 0. Il valore predefinito è -1. Valore: La quantità del codice a barre QR in modalità append strutturata.

**Returns:** the index of the QR structured append mode barcode.

### getStructuredAppendModeBarCodesQuantity() {#getstructuredappendmodebarcodesquantity}

Restituisce la quantità di codici a barre QR in modalità append strutturata. Il valore predefinito è -1. Valore: La quantità del codice a barre QR in modalità append strutturata.

**Returns:** the QR structured append mode barcodes quantity.

### getStructuredAppendModeParityData() {#getstructuredappendmodeparitydata}

Restituisce i dati di parità della modalità append strutturata QR. Il valore predefinito è -1. Valore: L'indice del codice a barre QR in modalità append strutturata.

**Returns:** the QR structured append mode parity data.

### getVersion() {#getversion}

Versione del QR Code riconosciuto. Da Version1 a Version40.

### hashCode() {#hashcode}

Restituisce il codice hash per questa istanza.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Verifica se tutti i parametri hanno solo valori predefiniti Valore

**Returns:** true if all parameters has only default values; otherwise, `false `.

### toString() {#tostring}

Restituisce una rappresentazione della stringa leggibile dall'uomo di questo QRExtendedParameters.

**Returns:** A string that represents this QRExtendedParameters.
