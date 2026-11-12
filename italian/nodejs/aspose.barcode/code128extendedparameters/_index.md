---
title: "Code128ExtendedParameters"
linktitle: "Code128ExtendedParameters"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Memorizza dati speciali del barcode Code128 riconosciuto. Rappresenta la regione del barcode riconosciuto e l'angolo del barcode."
type: docs
weight: 240
url: /it/nodejs/aspose.barcode/code128extendedparameters/
---

## Code128ExtendedParameters class

Memorizza dati speciali del barcode Code128 riconosciuto. Rappresenta la regione del barcode riconosciuto e l'angolo del barcode.

```js
new Code128ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get code128 raw values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.CODE_128);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("Code128 Data Portions: " + result.getExtended().getCode128());
}
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [equals(obj)](#equals) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato di Code128ExtendedParameters. |
| [getCode128DataPortions()](#getcode128dataportions) | Ottiene l'array Code128DataPortion del codice a barre Code128 riconosciuto. Valore di Code128DataPortion. |
| [hashCode()](#hashcode) | Restituisce il codice hash per questa istanza. |
| [toString()](#tostring) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo Code128ExtendedParameters. |

### equals(obj) {#equals}

Restituisce un valore che indica se questa istanza è uguale a un valore specificato di Code128ExtendedParameters.

| Parametro | Descrizione |
| --- | --- |
| obj | Un valore System.Object da confrontare con questa istanza. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCode128DataPortions() {#getcode128dataportions}

Ottiene l'array Code128DataPortion del codice a barre Code128 riconosciuto. Valore di Code128DataPortion.

### hashCode() {#hashcode}

Restituisce il codice hash per questa istanza.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Restituisce una rappresentazione stringa leggibile dall'uomo di questo Code128ExtendedParameters.

**Returns:** A string that represents this Code128ExtendedParameters.
