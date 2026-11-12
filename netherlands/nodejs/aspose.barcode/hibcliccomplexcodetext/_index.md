---
title: "HIBCLICComplexCodetext"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Basisklasse voor het coderen en decoderen van de tekst die in de HIBC LIC-code is ingebed."
type: docs
weight: 450
url: /nl/nodejs/aspose.barcode/hibcliccomplexcodetext/
---

## HIBCLICComplexCodetext class

Basisklasse voor het coderen en decoderen van de tekst die in de HIBC LIC-code is ingebed. Deze voorbeeld toont hoe ruwe HIBC LIC-codetekst te decoderen naar een HIBCLICComplexCodetext‑instantie.

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

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Haalt het type barcode op of stelt het in. HIBC LIC-codetekst kan worden gecodeerd met HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM |
| [getConstructedCodetext()](#getconstructedcodetext) | Construeert codetext |
| [initFromString(constructedCodetext)](#initfromstring) | Initialiseert instantie vanuit geconstrueerde codetext. |
| [setBarcodeType()](#setbarcodetype) | Haalt het type barcode op of stelt het in. HIBC LIC-codetekst kan worden gecodeerd met HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM |

### getBarcodeType() {#getbarcodetype}

Haalt het type barcode op of stelt het in. HIBC LIC-codetekst kan worden gecodeerd met HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC en HIBCQRLIC‑coderingstypen. Standaardwaarde: HIBCCode39LIC.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

Construeert codetext

**Returns:** Constructed codetext

### initFromString(constructedCodetext) {#initfromstring}

Initialiseert instantie vanuit geconstrueerde codetext.

| Parameter | Beschrijving |
| --- | --- |
| constructedCodetext | Geconstrueerde codetext. |

### setBarcodeType() {#setbarcodetype}

Haalt het type barcode op of stelt het in. HIBC LIC-codetekst kan worden gecodeerd met HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC en HIBCQRLIC‑coderingstypen. Standaardwaarde: HIBCCode39LIC.

**Returns:** Barcode type.
