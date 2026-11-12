---
title: "DotCodeExtendedParameters"
linktitle: "DotCodeExtendedParameters"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Memorizza dati speciali del barcode DotCode riconosciuto. Questo esempio mostra come ottenere i valori grezzi DotCode"
type: docs
weight: 380
url: /it/nodejs/aspose.barcode/dotcodeextendedparameters/
---

## DotCodeExtendedParameters class

Memorizza dati speciali del barcode DotCode riconosciuto. Questo esempio mostra come ottenere i valori grezzi DotCode

```js
new DotCodeExtendedParameters()
```

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
generator.save("test.png", BarCodeImageFormat.PNG);

let reader = new BarCodeReader("test.png", null, DecodeType.DOT_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    print("BarCode type: " + result.getCodeTypeName());
    print("BarCode codetext: " + result.getCodeText());
    print("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
    print("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
}
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [equals(obj)](#equals) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato `DotCodeExtendedParameters`. |
| [getDotCodeIsReaderInitialization()](#getdotcodeisreaderinitialization) ~~(deprecated)~~ | Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | Ottiene l'ID del codice a barre DotCode in modalità append strutturata. L'ID inizia da 1 e deve essere minore o uguale al conteggio dei codici a barre. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | Ottiene il conteggio dei codici a barre DotCode in modalità append strutturata. Il valore predefinito è -1. Il conteggio deve essere un valore da 1 a 35. Valore: |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Ottiene l'ID del codice a barre DotCode in modalità append strutturata. L'ID inizia da 1 e deve essere minore o uguale al conteggio dei codici a barre. |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | Ottiene il conteggio dei codici a barre DotCode in modalità append strutturata. Il valore predefinito è -1. Il conteggio deve essere un valore da 1 a 35. Valore: |
| [hashCode()](#hashcode) | Restituisce il codice hash per questa istanza. |
| [isReaderInitialization()](#isreaderinitialization) | Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o |
| [toString()](#tostring) | Restituisce una rappresentazione stringa leggibile da un umano di questo `DotCodeExtendedParameters`. |

### equals(obj) {#equals}

Restituisce un valore che indica se questa istanza è uguale a un valore specificato `DotCodeExtendedParameters`.

| Parametro | Descrizione |
| --- | --- |
| obj | Un valore System.Object da confrontare con questa istanza. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDotCodeIsReaderInitialization() {#getdotcodeisreaderinitialization}

> **Deprecated.** See method description for replacement.

Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. Il valore predefinito è false.

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

Ottiene l'ID del codice a barre DotCode in modalità append strutturata. L'ID inizia da 1 e deve essere minore o uguale al conteggio dei codici a barre. Il valore predefinito è -1. Valore: L'ID del codice a barre DotCode in modalità append strutturata.

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

Ottiene il conteggio dei codici a barre DotCode in modalità append strutturata. Il valore predefinito è -1. Il conteggio deve essere un valore da 1 a 35. Valore: Il conteggio dei codici a barre DotCode in modalità append strutturata.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Ottiene l'ID del codice a barre DotCode in modalità append strutturata. L'ID inizia da 1 e deve essere minore o uguale al conteggio dei codici a barre. Il valore predefinito è -1. Valore: L'ID del codice a barre DotCode in modalità append strutturata.

**Returns:** the ID of the DotCode structured append mode barcode.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

Ottiene il conteggio dei codici a barre DotCode in modalità append strutturata. Il valore predefinito è -1. Il conteggio deve essere un valore da 1 a 35. Valore: Il conteggio dei codici a barre DotCode in modalità append strutturata.

**Returns:** the DotCode structured append mode barcodes count.

### hashCode() {#hashcode}

Restituisce il codice hash per questa istanza.

**Returns:** A 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. Il valore predefinito è false.

### toString() {#tostring}

Restituisce una rappresentazione stringa leggibile da un umano di questo `DotCodeExtendedParameters`.

**Returns:** A string that represents this `DotCodeExtendedParameters`.
