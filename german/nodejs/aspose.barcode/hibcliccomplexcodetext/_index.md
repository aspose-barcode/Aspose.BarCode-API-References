---
title: "HIBCLICComplexCodetext"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Basisklasse für das Codieren und Dekodieren des in den HIBC LIC-Code eingebetteten Textes."
type: docs
weight: 450
url: /de/nodejs/aspose.barcode/hibcliccomplexcodetext/
---

## HIBCLICComplexCodetext class

Basisklasse für das Codieren und Dekodieren des in den HIBC LIC-Code eingebetteten Textes. Dieses Beispiel zeigt, wie man rohen HIBC LIC‑Codetext in eine HIBCLICComplexCodetext‑Instanz dekodiert.

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

| Name | Beschreibung |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Liest oder setzt den Barcode-Typ. HIBC LIC‑Codetext kann mit HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM codiert werden. |
| [getConstructedCodetext()](#getconstructedcodetext) | Erstellt Codetext |
| [initFromString(constructedCodetext)](#initfromstring) | Initialisiert die Instanz aus dem erstellten Codetext. |
| [setBarcodeType()](#setbarcodetype) | Liest oder setzt den Barcode-Typ. HIBC LIC‑Codetext kann mit HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM codiert werden. |

### getBarcodeType() {#getbarcodetype}

Liest oder setzt den Barcode-Typ. HIBC LIC‑Codetext kann mit den Kodierungstypen HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC und HIBCQRLIC codiert werden. Standardwert: HIBCCode39LIC.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

Erstellt Codetext

**Returns:** Constructed codetext

### initFromString(constructedCodetext) {#initfromstring}

Initialisiert die Instanz aus dem erstellten Codetext.

| Parameter | Beschreibung |
| --- | --- |
| constructedCodetext | Erstellter Codetext. |

### setBarcodeType() {#setbarcodetype}

Liest oder setzt den Barcode-Typ. HIBC LIC‑Codetext kann mit den Kodierungstypen HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC und HIBCQRLIC codiert werden. Standardwert: HIBCCode39LIC.

**Returns:** Barcode type.
