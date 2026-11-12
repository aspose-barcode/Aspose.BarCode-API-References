---
title: "BarCodeResult"
linktitle: "BarCodeResult"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Memorizza i dati del codice a barre riconosciuto come tipo SingleDecodeType, `string` codetext, BarCodeRegionParameters region e altri parametri"
type: docs
weight: 110
url: /it/nodejs/aspose.barcode/barcoderesult/
---

## BarCodeResult class

Memorizza i dati del codice a barre riconosciuto come tipo SingleDecodeType, `string` codetext, BarCodeRegionParameters region e altri parametri

```js
new BarCodeResult()
```

**Example:**

```js
//This sample shows how to obtain BarCodeResult.
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("BarCode Confidence: " + result.getConfidence());
    console.log("BarCode ReadingQuality: " + result.getReadingQuality());
    console.log("BarCode Angle: " + result.getRegion().getAngle());
}
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [deepClone()](#deepclone) | Crea una copia della classe BarCodeResult. |
| [equals(other)](#equals) | Restituisce un valore che indica se questa istanza è uguale a un valore BarCodeResult specificato. |
| [getCodeBytes()](#getcodebytes) | Ottiene i byte del codice codificati. Valore: I byte del codice del codice a barre |
| [getCodeText(encoding)](#getcodetext) | Ottiene il testo del codice con codifica. Questo esempio mostra come usare `getCodeText`: let gen = new BarcodeGenerator(EncodeType |
| [getCodeType()](#getcodetype) | Ottiene il tipo di codice a barre. Valore: Le informazioni sul tipo del codice a barre riconosciuto |
| [getCodeTypeName()](#getcodetypename) | Ottiene il nome del tipo di codice a barre. Valore: Il nome del tipo del codice a barre riconosciuto |
| [getConfidence()](#getconfidence) | Ottiene il livello di fiducia del riconoscimento del codice a barre riconosciuto. Valore: BarCodeConfidence.Strong non ha falsi o errori di riconoscimento |
| [getExtended()](#getextended) | Ottiene i parametri estesi del codice a barre riconosciuto. Valore: I parametri estesi del codice a barre riconosciuto |
| [getReadingQuality()](#getreadingquality) | Ottiene la qualità di lettura. Funziona per codici a barre 1D e postali. Valore: La percentuale di qualità di lettura |
| [getRegion()](#getregion) | Ottiene la regione del codice a barre. Valore: La regione del codice a barre riconosciuto |
| [hashCode()](#hashcode) | Restituisce il codice hash per questa istanza. |
| [toString()](#tostring) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo BarCodeResult. |

### deepClone() {#deepclone}

Crea una copia della classe BarCodeResult.

**Returns:** Returns copy of BarCodeResult class.

### equals(other) {#equals}

Restituisce un valore che indica se questa istanza è uguale a un valore BarCodeResult specificato.

| Parametro | Descrizione |
| --- | --- |
| altro | Un valore BarCodeResult da confrontare con questa istanza. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCodeBytes() {#getcodebytes}

Ottiene i byte del codice codificati. Valore: I byte del codice del codice a barre

### getCodeText(encoding) {#getcodetext}

Ottiene il testo del codice con codifica. Questo esempio mostra come usare `getCodeText`: let gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null); gen.setCodeText("車種名", "932"); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.DATA_MATRIX); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText("932")); }

| Parametro | Descrizione |
| --- | --- |
| codifica | La codifica per il codetext. |

**Returns:** A string containing recognized code text.

### getCodeType() {#getcodetype}

Ottiene il tipo di codice a barre. Valore: Le informazioni sul tipo del codice a barre riconosciuto

### getCodeTypeName() {#getcodetypename}

Ottiene il nome del tipo di codice a barre. Valore: Il nome del tipo del codice a barre riconosciuto

### getConfidence() {#getconfidence}

Ottiene il livello di fiducia del riconoscimento del codice a barre riconosciuto. Valore: BarCodeConfidence.Strong non ha falsi o errori di riconoscimento, BarCodeConfidence.Moderate a volte può avere falsi o codetext errato perché questo livello di fiducia si applica a codici a barre con checksum debole o anche senza di esso, BarCodeConfidence.NONE ha sempre codetext errato e potrebbe produrre riconoscimenti falsi

### getExtended() {#getextended}

Ottiene i parametri estesi del codice a barre riconosciuto. Valore: I parametri estesi del codice a barre riconosciuto

### getReadingQuality() {#getreadingquality}

Ottiene la qualità di lettura. Funziona per codici a barre 1D e postali. Valore: La percentuale di qualità di lettura

### getRegion() {#getregion}

Ottiene la regione del codice a barre. Valore: La regione del codice a barre riconosciuto

### hashCode() {#hashcode}

Restituisce il codice hash per questa istanza.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Restituisce una rappresentazione stringa leggibile dall'uomo di questo BarCodeResult.

**Returns:** A string that represents this BarCodeResult.
