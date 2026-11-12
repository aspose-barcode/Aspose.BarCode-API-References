---
title: "ComplexCodetextReader"
linktitle: "ComplexCodetextReader"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "ComplexCodetextReader αποκωδικοποιεί το codetext σε καθορισμένο τύπο σύνθετου barcode."
type: docs
weight: 290
url: /el/nodejs/aspose.barcode/complexcodetextreader/
---

## ComplexCodetextReader class

ComplexCodetextReader αποκωδικοποιεί το codetext σε καθορισμένο τύπο σύνθετου barcode.

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

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [tryDecodeHIBCLIC(encodedCodetext)](#trydecodehibclic) *(static)* | Αποκωδικοποιεί το κείμενο κώδικα HIBC LIC. |
| [tryDecodeHIBCPAS(encodedCodetext)](#trydecodehibcpas) *(static)* | Αποκωδικοποιεί το κείμενο κώδικα HIBC PAS. |
| [tryDecodeMailmark(encodedCodetext)](#trydecodemailmark) *(static)* | Αποκωδικοποιεί το κείμενο κώδικα Mailmark Barcode C και L. |
| [tryDecodeMailmark2D(encodedCodetext)](#trydecodemailmark2d) *(static)* | Αποκωδικοποιεί το κείμενο κώδικα Royal Mail Mailmark 2D. |
| [tryDecodeMaxiCode(maxiCodeMode, encodedCodetext)](#trydecodemaxicode) *(static)* | Αποκωδικοποιεί το κείμενο κώδικα MaxiCode. |
| [tryDecodeSwissQR(encodedCodetext)](#trydecodeswissqr) *(static)* | Αποκωδικοποιεί το κείμενο κώδικα SwissQR. |
| [tryDecodeUSADriveId(encodedCodetext)](#trydecodeusadriveid) *(static)* | Αποκωδικοποιεί το κείμενο κώδικα USADriveId. |

### tryDecodeHIBCLIC(encodedCodetext) (static) {#trydecodehibclic}

Αποκωδικοποιεί το κείμενο κώδικα HIBC LIC.

| Παράμετρος | Περιγραφή |
| --- | --- |
| encodedCodetext | κωδικοποιημένο κείμενο |

**Returns:** decoded HIBC LIC Complex Codetext or null.

### tryDecodeHIBCPAS(encodedCodetext) (static) {#trydecodehibcpas}

Αποκωδικοποιεί το κείμενο κώδικα HIBC PAS.

| Παράμετρος | Περιγραφή |
| --- | --- |
| encodedCodetext | κωδικοποιημένο κείμενο |

**Returns:** decoded HIBC PAS Complex Codetext or null.

### tryDecodeMailmark(encodedCodetext) (static) {#trydecodemailmark}

Αποκωδικοποιεί το κείμενο κώδικα Mailmark Barcode C και L.

| Παράμετρος | Περιγραφή |
| --- | --- |
| encodedCodetext | κωδικοποιημένο κείμενο |

**Returns:** Decoded Mailmark Barcode C and L or null.

### tryDecodeMailmark2D(encodedCodetext) (static) {#trydecodemailmark2d}

Αποκωδικοποιεί το κείμενο κώδικα Royal Mail Mailmark 2D.

| Παράμετρος | Περιγραφή |
| --- | --- |
| encodedCodetext | κωδικοποιημένο κείμενο |

**Returns:** decoded Royal Mail Mailmark 2D or null.

### tryDecodeMaxiCode(maxiCodeMode, encodedCodetext) (static) {#trydecodemaxicode}

Αποκωδικοποιεί το κείμενο κώδικα MaxiCode.

| Παράμετρος | Περιγραφή |
| --- | --- |
| maxiCodeMode | Λειτουργία MaxiCode |
| encodedCodetext | κωδικοποιημένο κείμενο |

**Returns:** Decoded MaxiCode codetext.

### tryDecodeSwissQR(encodedCodetext) (static) {#trydecodeswissqr}

Αποκωδικοποιεί το κείμενο κώδικα SwissQR.

| Παράμετρος | Περιγραφή |
| --- | --- |
| encodedCodetext | κωδικοποιημένο κείμενο |

**Returns:** decoded SwissQRCodetext or null.

### tryDecodeUSADriveId(encodedCodetext) (static) {#trydecodeusadriveid}

Αποκωδικοποιεί το κείμενο κώδικα USADriveId.

| Παράμετρος | Περιγραφή |
| --- | --- |
| encodedCodetext | Κωδικοποιημένο κείμενο |

**Returns:** Decoded USADriveId or null.
