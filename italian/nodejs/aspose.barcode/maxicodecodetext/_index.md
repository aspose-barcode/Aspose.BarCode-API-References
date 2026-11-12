---
title: "MaxiCodeCodetext"
linktitle: "MaxiCodeCodetext"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Classe base per la codifica e decodifica del testo incorporato nel codice MaxiCode."
type: docs
weight: 600
url: /it/nodejs/aspose.barcode/maxicodecodetext/
---

## MaxiCodeCodetext class

Classe base per la codifica e decodifica del testo incorporato nel codice MaxiCode. Questo esempio mostra come decodificare il codetext MaxiCode grezzo in un'istanza MaxiCodeCodetext.

```js
new MaxiCodeCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.MAXI_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     let resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMaxiCodeMode(), result.getCodeText());
     console.log("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
     console.log("MaxiCode mode: " + resultMaxiCodeCodetext.getMode());
     console.log("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Ottiene il tipo di codice a barre. |
| [getECIEncoding()](#geteciencoding) | Ottiene la codifica ECI. Usata quando MaxiCodeEncodeMode è AUTO. |
| [getEncodeMode()](#getencodemode) | Ottiene una modalità di codifica MaxiCode. Valore predefinito: Auto. |
| [getMaxiCodeEncodeMode()](#getmaxicodeencodemode) ~~(deprecated)~~ | Ottiene una modalità di codifica MaxiCode. |
| [getMode()](#getmode) | Ottiene la modalità MaxiCode. |
| [setECIEncoding()](#seteciencoding) | Imposta la codifica ECI. Usata quando MaxiCodeEncodeMode è AUTO. |
| [setEncodeMode(value)](#setencodemode) | Imposta una modalità di codifica MaxiCode. Valore predefinito: Auto. |
| [setMaxiCodeEncodeMode()](#setmaxicodeencodemode) ~~(deprecated)~~ | Imposta una modalità di codifica MaxiCode. |

### getBarcodeType() {#getbarcodetype}

Ottiene il tipo di codice a barre.

**Returns:** Barcode type

### getECIEncoding() {#geteciencoding}

Ottiene la codifica ECI. Usata quando MaxiCodeEncodeMode è AUTO.

### getEncodeMode() {#getencodemode}

Ottiene una modalità di codifica MaxiCode. Valore predefinito: Auto.

**Returns:** a MaxiCode encode mode.

### getMaxiCodeEncodeMode() {#getmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Ottiene una modalità di codifica MaxiCode.

### getMode() {#getmode}

Ottiene la modalità MaxiCode.

**Returns:** MaxiCode mode

### setECIEncoding() {#seteciencoding}

Imposta la codifica ECI. Usata quando MaxiCodeEncodeMode è AUTO.

### setEncodeMode(value) {#setencodemode}

Imposta una modalità di codifica MaxiCode. Valore predefinito: Auto.

| Parametro | Descrizione |
| --- | --- |
| valore | una modalità di codifica MaxiCode. |

### setMaxiCodeEncodeMode() {#setmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Imposta una modalità di codifica MaxiCode.
