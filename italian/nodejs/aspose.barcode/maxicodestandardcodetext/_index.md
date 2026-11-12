---
title: "MaxiCodeStandardCodetext"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Classe per la codifica e decodifica del codetext MaxiCode per le modalità 4, 5 e 6."
type: docs
weight: 670
url: /it/nodejs/aspose.barcode/maxicodestandardcodetext/
---

## MaxiCodeStandardCodetext class

Classe per la codifica e decodifica del codetext MaxiCode per le modalità 4, 5 e 6.

```js
new MaxiCodeStandardCodetext()
```

**Example:**

```js
//Mode 4
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [equals(obj)](#equals) | Restituisce un valore che indica se questa istanza è uguale a un valore specificato. |
| [getConstructedCodetext()](#getconstructedcodetext) | Costruisce il codetext |
| [getHashCode()](#gethashcode) | Restituisce il codice hash per questa istanza. |
| [getMessage()](#getmessage) | Ottiene il messaggio. |
| [getMode()](#getmode) | Ottiene la modalità MaxiCode. |
| [initFromString(constructedCodetext)](#initfromstring) | Inizializza l'istanza dal codetext costruito. |
| [setMessage()](#setmessage) | Imposta il messaggio. |
| [setMode()](#setmode) | Imposta la modalità MaxiCode. Il codetext standard può essere usato solo con le modalità 4, 5 e 6. |

### equals(obj) {#equals}

Restituisce un valore che indica se questa istanza è uguale a un valore specificato.

| Parametro | Descrizione |
| --- | --- |
| obj | Un valore da confrontare con questa istanza. |

**Returns:** if obj has the same value as this instance; otherwise, false .

### getConstructedCodetext() {#getconstructedcodetext}

Costruisce il codetext

**Returns:** Constructed codetext

### getHashCode() {#gethashcode}

Restituisce il codice hash per questa istanza.

**Returns:** A 32-bit signed integer hash code

### getMessage() {#getmessage}

Ottiene il messaggio.

### getMode() {#getmode}

Ottiene la modalità MaxiCode.

**Returns:** MaxiCode mode

### initFromString(constructedCodetext) {#initfromstring}

Inizializza l'istanza dal codetext costruito.

| Parametro | Descrizione |
| --- | --- |
| constructedCodetext | Codetext costruito. |

### setMessage() {#setmessage}

Imposta il messaggio.

### setMode() {#setmode}

Imposta la modalità MaxiCode. Il codetext standard può essere usato solo con le modalità 4, 5 e 6.
