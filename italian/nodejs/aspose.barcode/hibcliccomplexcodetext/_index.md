---
title: "HIBCLICComplexCodetext"
linktitle: "HIBCLICComplexCodetext"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Classe base per la codifica e decodifica del testo incorporato nel codice HIBC LIC."
type: docs
weight: 450
url: /it/nodejs/aspose.barcode/hibcliccomplexcodetext/
---

## HIBCLICComplexCodetext class

Classe base per la codifica e decodifica del testo incorporato nel codice HIBC LIC. Questo esempio mostra come decodificare il codetext HIBC LIC grezzo in un'istanza di HIBCLICComplexCodetext.

```js
new HIBCLICComplexCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.HIBC_AZTEC_LIC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
   let resultHIBCLICComplexCodetext = ComplexCodetextReader.tryDecodeHIBCLIC(result.getCodeText());
   print("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
   print("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Restituisce o imposta il tipo di barcode. Il codetext HIBC LIC può essere codificato usando HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM |
| [getConstructedCodetext()](#getconstructedcodetext) | Costruisce il codetext |
| [initFromString(constructedCodetext)](#initfromstring) | Inizializza l'istanza dal codetext costruito. |
| [setBarcodeType()](#setbarcodetype) | Restituisce o imposta il tipo di barcode. Il codetext HIBC LIC può essere codificato usando HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM |

### getBarcodeType() {#getbarcodetype}

Restituisce o imposta il tipo di barcode. Il codetext HIBC LIC può essere codificato usando i tipi di codifica HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC e HIBCQRLIC. Valore predefinito: HIBCCode39LIC.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

Costruisce il codetext

**Returns:** Constructed codetext

### initFromString(constructedCodetext) {#initfromstring}

Inizializza l'istanza dal codetext costruito.

| Parametro | Descrizione |
| --- | --- |
| constructedCodetext | Codetext costruito. |

### setBarcodeType() {#setbarcodetype}

Restituisce o imposta il tipo di barcode. Il codetext HIBC LIC può essere codificato usando i tipi di codifica HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC e HIBCQRLIC. Valore predefinito: HIBCCode39LIC.

**Returns:** Barcode type.
