---
title: "HIBCLICComplexCodetext"
linktitle: "HIBCLICComplexCodetext"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Classe de base pour l'encodage et le décodage du texte intégré dans le code HIBC LIC."
type: docs
weight: 450
url: /fr/nodejs/aspose.barcode/hibcliccomplexcodetext/
---

## HIBCLICComplexCodetext class

Classe de base pour l'encodage et le décodage du texte intégré dans le code HIBC LIC. Cet exemple montre comment décoder le codetext HIBC LIC brut en instance HIBCLICComplexCodetext.

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

## Méthodes

| Nom | Description |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Obtient ou définit le type de code-barres. Le codetext HIBC LIC peut être encodé en utilisant HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM |
| [getConstructedCodetext()](#getconstructedcodetext) | Construit le codetext |
| [initFromString(constructedCodetext)](#initfromstring) | Initialise l'instance à partir du codetext construit. |
| [setBarcodeType()](#setbarcodetype) | Obtient ou définit le type de code-barres. Le codetext HIBC LIC peut être encodé en utilisant HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataM |

### getBarcodeType() {#getbarcodetype}

Obtient ou définit le type de code-barres. Le codetext HIBC LIC peut être encodé en utilisant les types d'encodage HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC et HIBCQRLIC. Valeur par défaut : HIBCCode39LIC.

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

Construit le codetext

**Returns:** Constructed codetext

### initFromString(constructedCodetext) {#initfromstring}

Initialise l'instance à partir du codetext construit.

| Paramètre | Description |
| --- | --- |
| constructedCodetext | Codetext construit. |

### setBarcodeType() {#setbarcodetype}

Obtient ou définit le type de code-barres. Le codetext HIBC LIC peut être encodé en utilisant les types d'encodage HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC et HIBCQRLIC. Valeur par défaut : HIBCCode39LIC.

**Returns:** Barcode type.
