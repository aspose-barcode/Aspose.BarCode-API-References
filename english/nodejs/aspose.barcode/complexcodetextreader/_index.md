---
title: "ComplexCodetextReader Class"
linktitle: "ComplexCodetextReader"
articleTitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode for Node.js via Java"
description: "ComplexCodetextReader decodes codetext to specified complex barcode type."
type: docs
weight: 290
url: /nodejs/aspose.barcode/complexcodetextreader/
---

## ComplexCodetextReader class

ComplexCodetextReader decodes codetext to specified complex barcode type.

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

## Methods

| Name | Description |
| --- | --- |
| [tryDecodeHIBCLIC(encodedCodetext)](./trydecodehibclic/) *(static)* | Decodes HIBC LIC codetext. |
| [tryDecodeHIBCPAS(encodedCodetext)](./trydecodehibcpas/) *(static)* | Decodes HIBC PAS codetext. |
| [tryDecodeMailmark(encodedCodetext)](./trydecodemailmark/) *(static)* | Decodes Mailmark Barcode C and L codetext. |
| [tryDecodeMailmark2D(encodedCodetext)](./trydecodemailmark2d/) *(static)* | Decodes Royal Mail Mailmark 2D codetext. |
| [tryDecodeMaxiCode(maxiCodeMode, encodedCodetext)](./trydecodemaxicode/) *(static)* | Decodes MaxiCode codetext. |
| [tryDecodeSwissQR(encodedCodetext)](./trydecodeswissqr/) *(static)* | Decodes SwissQR codetext. |
| [tryDecodeUSADriveId(encodedCodetext)](./trydecodeusadriveid/) *(static)* | Decodes USADriveId codetext. |
