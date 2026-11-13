---
title: "HIBCLICComplexCodetext"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Basklass för kodning och avkodning av text som är inbäddad i HIBC LIC-koden."
type: docs
weight: 450
url: /sv/nodejs/aspose.barcode/hibcliccomplexcodetext/
---

## HIBCLICComplexCodetext class

Basklass för kodning och avkodning av text som är inbäddad i HIBC LIC-koden. Detta exempel visar hur man avkodar rå HIBC LIC-codetext till en HIBCLICComplexCodetext-instans.

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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Hämtar eller anger streckkodstyp. HIBC LIC-codetext kan kodas med HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM |
| [getConstructedCodetext()](#getconstructedcodetext) | Skapar kodtext |
| [initFromString(constructedCodetext)](#initfromstring) | Initierar objektet från konstruerad kodtext. |
| [setBarcodeType()](#setbarcodetype) | Hämtar eller anger streckkodstyp. HIBC LIC-codetext kan kodas med HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM |

### getBarcodeType() {#getbarcodetype}

Hämtar eller anger streckkodstyp. HIBC LIC-kodtext kan kodas med HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC och HIBCQRLIC kodningstyper. Standardvärde: HIBCCode39LIC.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

Skapar kodtext

**Returns:** Constructed codetext

### initFromString(constructedCodetext) {#initfromstring}

Initierar objektet från konstruerad kodtext.

| Parameter | Beskrivning |
| --- | --- |
| constructedCodetext | Konstruerad kodtext. |

### setBarcodeType() {#setbarcodetype}

Hämtar eller anger streckkodstyp. HIBC LIC-kodtext kan kodas med HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC och HIBCQRLIC kodningstyper. Standardvärde: HIBCCode39LIC.

**Returns:** Barcode type.
