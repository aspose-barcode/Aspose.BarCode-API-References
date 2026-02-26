---
title: "ComplexCodetextReader Class"
linktitle: "ComplexCodetextReader"
articleTitle: "ComplexCodetextReader"
second_title: "Aspose.BarCode for Node.js via Java"
description: "ComplexCodetextReader decodes codetext to specified complex barcode type."
type: docs
weight: 70
url: /nodejs/complexcodetextreader/
---
## ComplexCodetextReader class

ComplexCodetextReader decodes codetext to specified complex barcode type.

```javascript
public class ComplexCodetextReader
```

## Methods

| Name | Description |
| --- | --- |
| [tryDecodeHIBCLIC](./trydecodehibclic/)(*object*) | Decodes HIBC LIC codetext. |
| [tryDecodeHIBCPAS](./trydecodehibcpas/)(*object*) | Decodes HIBC PAS codetext. |
| [tryDecodeMailmark](./trydecodemailmark/)(*object*) | Decodes Mailmark Barcode C and L codetext. |
| [tryDecodeMailmark2D](./trydecodemailmark2d/)(*object*) | Decodes Royal Mail Mailmark 2D codetext. |
| [tryDecodeMaxiCode](./trydecodemaxicode/)(*object, object*) | Decodes MaxiCode codetext. |
| [tryDecodeSwissQR](./trydecodeswissqr/)(*object*) | Decodes SwissQR codetext. |
| [tryDecodeUSADriveId](./trydecodeusadriveid/)(*object*) | Decodes USADriveId codetext. |

## Fields

| Name | Description |
| --- | --- |
| [javaClassName](./javaclassname/) |  |

## Examples

This sample shows how to recognize and decode SwissQR image.

```javascript
let cr = new BarCodeReader("SwissQRCodetext.png", null, DecodeType.QR);
cr.read();
let result = ComplexCodetextReader.tryDecodeSwissQR(cr.getCodeText(false));
```

### See Also

* assembly [Aspose.BarCode](../)

