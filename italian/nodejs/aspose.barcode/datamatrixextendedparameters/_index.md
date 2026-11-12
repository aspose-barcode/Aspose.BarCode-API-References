---
title: "DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Memorizza dati speciali del codice a barre DataMatrix riconosciuto Questo esempio mostra come ottenere i valori grezzi DataMatrix let generator = new BarcodeGenerator(EncodeTypes.DATA_MA"
type: docs
weight: 350
url: /it/nodejs/aspose.barcode/datamatrixextendedparameters/
---

## DataMatrixExtendedParameters class

Memorizza dati speciali del codice a barre DataMatrix riconosciuto Questo esempio mostra come ottenere i valori grezzi DataMatrix let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345")) generator.save("test.png", BarcodeImageFormat.PNG); let reader = new BarCodeReader("test.png", null, DecodeType.DATA_MATRIX)) let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode type: " + result.getCodeTypeName()); console.log("BarCode codetext: " + result.getCodeText()); console.log("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId()); console.log("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount()); console.log("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId()); console.log("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming()); }

```js
new DataMatrixExtendedParameters()
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [equals(obj)](#equals) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di `DataMatrixExtendedParameters`. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Ottiene l'ID del codice a barre DataMatrix in modalità structured append. L'ID inizia da 1 e deve essere minore o uguale al numero di codici a barre cou |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Ottiene il conteggio dei codici a barre DataMatrix in modalità structured append. Il valore predefinito è -1. Il conteggio deve essere un valore da 1 a 35. Valu |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Ottiene l'ID del codice a barre DataMatrix in modalità structured append. L'ID inizia da 1 e deve essere minore o uguale al numero di codici a barre cou |
| [hashCode()](#hashcode) | Restituisce il codice hash per questa istanza. |
| [isReaderProgramming()](#isreaderprogramming) | Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o |
| [toString()](#tostring) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo `DataMatrixExtendedParameters`. |

### equals(obj) {#equals}

Restituisce un valore che indica se questa istanza è uguale a un valore specificato di `DataMatrixExtendedParameters`.

| Parametro | Descrizione |
| --- | --- |
| obj | Un valore System.Object da confrontare con questa istanza. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Ottiene l'ID del codice a barre DataMatrix in modalità structured append. L'ID inizia da 1 e deve essere minore o uguale al conteggio dei codici a barre. Il valore predefinito è -1. Valore: L'ID del codice a barre DataMatrix in modalità structured append.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Ottiene il conteggio dei codici a barre in modalità di aggiunta strutturata DataMatrix. Il valore predefinito è -1. Il conteggio deve essere un valore da 1 a 35. Valore: Il conteggio del codice a barre in modalità di aggiunta strutturata DataMatrix.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Ottiene l'ID del codice a barre DataMatrix in modalità structured append. L'ID inizia da 1 e deve essere minore o uguale al conteggio dei codici a barre. Il valore predefinito è -1. Valore: L'ID del codice a barre DataMatrix in modalità structured append.

### hashCode() {#hashcode}

Restituisce il codice hash per questa istanza.

**Returns:** A 32-bit signed integer hash code.

### isReaderProgramming() {#isreaderprogramming}

Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. Il valore predefinito è false.

### toString() {#tostring}

Restituisce una rappresentazione stringa leggibile dall'uomo di questo `DataMatrixExtendedParameters`.

**Returns:** A string that represents this `DataMatrixExtendedParameters`.
