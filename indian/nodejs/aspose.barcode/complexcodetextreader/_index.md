---
title: "ComplexCodetextReader"
linktitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "ComplexCodetextReader कोडटेक्स्ट को निर्दिष्ट कॉम्प्लेक्स बारकोड प्रकार में डिकोड करता है।"
type: docs
weight: 290
url: /hi/nodejs/aspose.barcode/complexcodetextreader/
---

## ComplexCodetextReader class

ComplexCodetextReader कोडटेक्स्ट को निर्दिष्ट कॉम्प्लेक्स बारकोड प्रकार में डिकोड करता है।

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

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [tryDecodeHIBCLIC(encodedCodetext)](#trydecodehibclic) *(static)* | HIBC LIC कोडटेक्स्ट को डिकोड करता है। |
| [tryDecodeHIBCPAS(encodedCodetext)](#trydecodehibcpas) *(static)* | HIBC PAS कोडटेक्स्ट को डिकोड करता है। |
| [tryDecodeMailmark(encodedCodetext)](#trydecodemailmark) *(static)* | Mailmark बारकोड C और L कोडटेक्स्ट को डिकोड करता है। |
| [tryDecodeMailmark2D(encodedCodetext)](#trydecodemailmark2d) *(static)* | Royal Mail Mailmark 2D कोडटेक्स्ट को डिकोड करता है। |
| [tryDecodeMaxiCode(maxiCodeMode, encodedCodetext)](#trydecodemaxicode) *(static)* | MaxiCode कोडटेक्स्ट को डिकोड करता है। |
| [tryDecodeSwissQR(encodedCodetext)](#trydecodeswissqr) *(static)* | SwissQR कोडटेक्स्ट को डिकोड करता है। |
| [tryDecodeUSADriveId(encodedCodetext)](#trydecodeusadriveid) *(static)* | USADriveId कोडटेक्स्ट को डिकोड करता है। |

### tryDecodeHIBCLIC(encodedCodetext) (static) {#trydecodehibclic}

HIBC LIC कोडटेक्स्ट को डिकोड करता है।

| पैरामीटर | विवरण |
| --- | --- |
| encodedCodetext | एन्कोडेड कोडटेक्स्ट |

**Returns:** decoded HIBC LIC Complex Codetext or null.

### tryDecodeHIBCPAS(encodedCodetext) (static) {#trydecodehibcpas}

HIBC PAS कोडटेक्स्ट को डिकोड करता है।

| पैरामीटर | विवरण |
| --- | --- |
| encodedCodetext | एन्कोडेड कोडटेक्स्ट |

**Returns:** decoded HIBC PAS Complex Codetext or null.

### tryDecodeMailmark(encodedCodetext) (static) {#trydecodemailmark}

Mailmark बारकोड C और L कोडटेक्स्ट को डिकोड करता है।

| पैरामीटर | विवरण |
| --- | --- |
| encodedCodetext | एन्कोडेड कोडटेक्स्ट |

**Returns:** Decoded Mailmark Barcode C and L or null.

### tryDecodeMailmark2D(encodedCodetext) (static) {#trydecodemailmark2d}

Royal Mail Mailmark 2D कोडटेक्स्ट को डिकोड करता है।

| पैरामीटर | विवरण |
| --- | --- |
| encodedCodetext | एन्कोडेड कोडटेक्स्ट |

**Returns:** decoded Royal Mail Mailmark 2D or null.

### tryDecodeMaxiCode(maxiCodeMode, encodedCodetext) (static) {#trydecodemaxicode}

MaxiCode कोडटेक्स्ट को डिकोड करता है।

| पैरामीटर | विवरण |
| --- | --- |
| maxiCodeMode | MaxiCode मोड |
| encodedCodetext | एन्कोडेड कोडटेक्स्ट |

**Returns:** Decoded MaxiCode codetext.

### tryDecodeSwissQR(encodedCodetext) (static) {#trydecodeswissqr}

SwissQR कोडटेक्स्ट को डिकोड करता है।

| पैरामीटर | विवरण |
| --- | --- |
| encodedCodetext | एन्कोडेड कोडटेक्स्ट |

**Returns:** decoded SwissQRCodetext or null.

### tryDecodeUSADriveId(encodedCodetext) (static) {#trydecodeusadriveid}

USADriveId कोडटेक्स्ट को डिकोड करता है।

| पैरामीटर | विवरण |
| --- | --- |
| encodedCodetext | एन्कोडेड कोडटेक्स्ट |

**Returns:** Decoded USADriveId or null.
