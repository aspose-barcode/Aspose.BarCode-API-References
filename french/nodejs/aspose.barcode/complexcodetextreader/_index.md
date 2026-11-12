---
title: "ComplexCodetextReader"
linktitle: "ComplexCodetextReader"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "ComplexCodetextReader décode le codetext en type de code-barres complexe spécifié."
type: docs
weight: 290
url: /fr/nodejs/aspose.barcode/complexcodetextreader/
---

## ComplexCodetextReader class

ComplexCodetextReader décode le codetext en type de code-barres complexe spécifié.

```js
new ComplexCodetextReader()
```

**Example:**

```js
This sample shows how to recognize and decode SwissQR image.

 let cr = new BarCodeReader("SwissQRCodetext.png", null, DecodeType.QR);
 cr.read();
 let result = ComplexCodetextReader.tryDecodeSwissQR(cr.getCodeText(false));
```

## Méthodes

| Nom | Description |
| --- | --- |
| [tryDecodeHIBCLIC(encodedCodetext)](#trydecodehibclic) *(static)* | Décode le texte de code HIBC LIC. |
| [tryDecodeHIBCPAS(encodedCodetext)](#trydecodehibcpas) *(static)* | Décode le texte de code HIBC PAS. |
| [tryDecodeMailmark(encodedCodetext)](#trydecodemailmark) *(static)* | Décode le texte de code du code-barres Mailmark C et L. |
| [tryDecodeMailmark2D(encodedCodetext)](#trydecodemailmark2d) *(static)* | Décode le texte de code Royal Mail Mailmark 2D. |
| [tryDecodeMaxiCode(maxiCodeMode, encodedCodetext)](#trydecodemaxicode) *(static)* | Décode le texte de code MaxiCode. |
| [tryDecodeSwissQR(encodedCodetext)](#trydecodeswissqr) *(static)* | Décode le texte de code SwissQR. |
| [tryDecodeUSADriveId(encodedCodetext)](#trydecodeusadriveid) *(static)* | Décode le texte de code USADriveId. |

### tryDecodeHIBCLIC(encodedCodetext) (static) {#trydecodehibclic}

Décode le texte de code HIBC LIC.

| Paramètre | Description |
| --- | --- |
| encodedCodetext | texte de code encodé |

**Returns:** decoded HIBC LIC Complex Codetext or null.

### tryDecodeHIBCPAS(encodedCodetext) (static) {#trydecodehibcpas}

Décode le texte de code HIBC PAS.

| Paramètre | Description |
| --- | --- |
| encodedCodetext | texte de code encodé |

**Returns:** decoded HIBC PAS Complex Codetext or null.

### tryDecodeMailmark(encodedCodetext) (static) {#trydecodemailmark}

Décode le texte de code du code-barres Mailmark C et L.

| Paramètre | Description |
| --- | --- |
| encodedCodetext | texte de code encodé |

**Returns:** Decoded Mailmark Barcode C and L or null.

### tryDecodeMailmark2D(encodedCodetext) (static) {#trydecodemailmark2d}

Décode le texte de code Royal Mail Mailmark 2D.

| Paramètre | Description |
| --- | --- |
| encodedCodetext | texte de code encodé |

**Returns:** decoded Royal Mail Mailmark 2D or null.

### tryDecodeMaxiCode(maxiCodeMode, encodedCodetext) (static) {#trydecodemaxicode}

Décode le texte de code MaxiCode.

| Paramètre | Description |
| --- | --- |
| maxiCodeMode | Mode MaxiCode |
| encodedCodetext | texte de code encodé |

**Returns:** Decoded MaxiCode codetext.

### tryDecodeSwissQR(encodedCodetext) (static) {#trydecodeswissqr}

Décode le texte de code SwissQR.

| Paramètre | Description |
| --- | --- |
| encodedCodetext | texte de code encodé |

**Returns:** decoded SwissQRCodetext or null.

### tryDecodeUSADriveId(encodedCodetext) (static) {#trydecodeusadriveid}

Décode le texte de code USADriveId.

| Paramètre | Description |
| --- | --- |
| encodedCodetext | Texte de code encodé |

**Returns:** Decoded USADriveId or null.
