---
title: "MaxiCodeCodetext"
linktitle: "MaxiCodeCodetext"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Classe de base pour l'encodage et le décodage du texte intégré dans le code MaxiCode."
type: docs
weight: 600
url: /fr/nodejs/aspose.barcode/maxicodecodetext/
---

## MaxiCodeCodetext class

Classe de base pour l'encodage et le décodage du texte intégré dans le code MaxiCode. Cet exemple montre comment décoder le codetext brut MaxiCode en instance de MaxiCodeCodetext.

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

## Méthodes

| Nom | Description |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Obtient le type de code-barres. |
| [getECIEncoding()](#geteciencoding) | Obtient l'encodage ECI. Utilisé lorsque MaxiCodeEncodeMode est AUTO. |
| [getEncodeMode()](#getencodemode) | Obtient un mode d'encodage MaxiCode. Valeur par défaut : Auto. |
| [getMaxiCodeEncodeMode()](#getmaxicodeencodemode) ~~(deprecated)~~ | Obtient un mode d'encodage MaxiCode. |
| [getMode()](#getmode) | Obtient le mode MaxiCode. |
| [setECIEncoding()](#seteciencoding) | Définit l'encodage ECI. Utilisé lorsque MaxiCodeEncodeMode est AUTO. |
| [setEncodeMode(value)](#setencodemode) | Définit un mode d'encodage MaxiCode. Valeur par défaut : Auto. |
| [setMaxiCodeEncodeMode()](#setmaxicodeencodemode) ~~(deprecated)~~ | Définit un mode d'encodage MaxiCode. |

### getBarcodeType() {#getbarcodetype}

Obtient le type de code-barres.

**Returns:** Barcode type

### getECIEncoding() {#geteciencoding}

Obtient l'encodage ECI. Utilisé lorsque MaxiCodeEncodeMode est AUTO.

### getEncodeMode() {#getencodemode}

Obtient un mode d'encodage MaxiCode. Valeur par défaut : Auto.

**Returns:** a MaxiCode encode mode.

### getMaxiCodeEncodeMode() {#getmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Obtient un mode d'encodage MaxiCode.

### getMode() {#getmode}

Obtient le mode MaxiCode.

**Returns:** MaxiCode mode

### setECIEncoding() {#seteciencoding}

Définit l'encodage ECI. Utilisé lorsque MaxiCodeEncodeMode est AUTO.

### setEncodeMode(value) {#setencodemode}

Définit un mode d'encodage MaxiCode. Valeur par défaut : Auto.

| Paramètre | Description |
| --- | --- |
| valeur | un mode d'encodage MaxiCode. |

### setMaxiCodeEncodeMode() {#setmaxicodeencodemode}

> **Deprecated.** See method description for replacement.

Définit un mode d'encodage MaxiCode.
