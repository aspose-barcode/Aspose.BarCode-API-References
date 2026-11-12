---
title: "OneDExtendedParameters"
linktitle: "OneDExtendedParameters"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Memorizza dati speciali del codice a barre 1D riconosciuto, come codetext separato e checksum"
type: docs
weight: 720
url: /it/nodejs/aspose.barcode/onedextendedparameters/
---

## OneDExtendedParameters class

Memorizza dati speciali del codice a barre 1D riconosciuto, come codetext separato e checksum

```js
new OneDExtendedParameters()
```

**Example:**

```js
//This sample shows how to get 1D barcode value and checksum
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.EAN_13);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Value: " + result.getExtended().getOneD().getValue());
   console.log("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [equals(obj)](#equals) | Restituisce un valore che indica se questa istanza è uguale a un valore OneDExtendedParameters specificato. |
| [getCheckSum()](#getchecksum) | Ottiene il checksum per i codici a barre 1D. Valore: Il checksum per il codice a barre 1D. |
| [getValue()](#getvalue) | Ottiene il codetext dei codici a barre 1D senza checksum. Valore: Il codetext dei codici a barre 1D senza checksum. |
| [hashCode()](#hashcode) | Restituisce il codice hash per questa istanza. |
| [isEmpty()](#isempty) | Verifica se tutti i parametri hanno solo valori predefiniti. Valore: Restituisce `true ` se tutti i parametri hanno solo valori predefiniti; o |
| [toString()](#tostring) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo OneDExtendedParameters. |

### equals(obj) {#equals}

Restituisce un valore che indica se questa istanza è uguale a un valore OneDExtendedParameters specificato.

| Parametro | Descrizione |
| --- | --- |
| obj | Un valore System.Object da confrontare con questa istanza. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCheckSum() {#getchecksum}

Ottiene il checksum per i codici a barre 1D. Valore: Il checksum per il codice a barre 1D.

### getValue() {#getvalue}

Ottiene il codetext dei codici a barre 1D senza checksum. Valore: Il codetext dei codici a barre 1D senza checksum.

### hashCode() {#hashcode}

Restituisce il codice hash per questa istanza.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Verifica se tutti i parametri hanno solo valori predefiniti. Valore: Restituisce `true ` se tutti i parametri hanno solo valori predefiniti; altrimenti, `false `.

### toString() {#tostring}

Restituisce una rappresentazione stringa leggibile dall'uomo di questo OneDExtendedParameters.

**Returns:** A string that represents this OneDExtendedParameters.
