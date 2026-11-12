---
title: "AztecExtendedParameters"
linktitle: "AztecExtendedParameters"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Memorizza dati speciali del codice a barre Aztec riconosciuto. Questo esempio mostra come ottenere i valori grezzi di Aztec let generator = new BarcodeGenerator(EncodeTypes.AZTEC, \"12345\"); "
type: docs
weight: 60
url: /it/nodejs/aspose.barcode/aztecextendedparameters/
---

## AztecExtendedParameters class

Memorizza dati speciali del codice a barre Aztec riconosciuto. Questo esempio mostra come ottenere i valori grezzi di Aztec let generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345"); generator.save("test.png", BarcodeImageFormat.PNG);

```js
new AztecExtendedParameters()
```

**Example:**

```js
BarCodeReader reader = new BarCodeReader("test.png", null, DecodeType.AZTEC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode type: " + result.getCodeTypeName());
    console.log("BarCode codetext: " + result.getCodeText());
    console.log("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
    console.log("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
    console.log("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
    console.log("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
}
</pre>
</pre></blockquote></hr></p>
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [equals(obj)](#equals) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di `AztecExtendedParameters`. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Ottiene l'ID del codice a barre in modalità append strutturata Aztec. L'ID inizia da 1 e deve essere inferiore o uguale al conteggio dei codici a barre. D |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Ottiene il conteggio dei codici a barre in modalità append strutturata Aztec. Il valore predefinito è 0. Il conteggio deve essere un valore da 1 a 26. Valore: Il |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Ottiene l'ID file della modalità append strutturata Aztec. Il valore predefinito è una stringa vuota. Valore: L'ID file dell'Aztec stru |
| [hashCode()](#hashcode) | Restituisce il codice hash per questa istanza. |
| [isReaderInitialization()](#isreaderinitialization) | Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o |
| [toString()](#tostring) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo `AztecExtendedParameters`. |

### equals(obj) {#equals}

Restituisce un valore che indica se questa istanza è uguale a un valore specificato di `AztecExtendedParameters`.

| Parametro | Descrizione |
| --- | --- |
| obj | Un valore System.Object da confrontare con questa istanza. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Ottiene l'ID del codice a barre in modalità append strutturata Aztec. L'ID inizia da 1 e deve essere inferiore o uguale al conteggio dei codici a barre. Il valore predefinito è 0. Valore: L'ID del codice a barre della modalità append strutturata Aztec.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Ottiene il conteggio dei codici a barre in modalità append strutturata Aztec. Il valore predefinito è 0. Il conteggio deve essere un valore da 1 a 26. Valore: Il conteggio dei codici a barre della modalità append strutturata Aztec.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Ottiene l'ID file della modalità append strutturata Aztec. Il valore predefinito è una stringa vuota. Valore: L'ID file della modalità append strutturata Aztec.

### hashCode() {#hashcode}

Restituisce il codice hash per questa istanza.

**Returns:** 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Indica se il codice è usato per istruire il lettore a interpretare i dati seguenti come istruzioni per l'inizializzazione o la riprogrammazione del lettore di codici a barre. Il valore predefinito è false.

### toString() {#tostring}

Restituisce una rappresentazione stringa leggibile dall'uomo di questo `AztecExtendedParameters`.

**Returns:** A string that represents this `AztecExtendedParameters`.
