---
title: "BarcodeGenerator Class"
linktitle: "BarcodeGenerator"
articleTitle: "BarcodeGenerator"
second_title: "Aspose.BarCode for Node.js via Java"
description: "BarcodeGenerator for backend barcode images generation. supported symbologies: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, C..."
type: docs
weight: 130
url: /nodejs/aspose.barcode/barcodegenerator/
---

## BarcodeGenerator class

BarcodeGenerator for backend barcode images generation. supported symbologies: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

```js
new BarcodeGenerator(encodeType, codeText)
```

BarcodeGenerator constructor.

| Parameter | Description |
| --- | --- |
| encodeType | Barcode symbology type. Use EncodeTypes class to setup a symbology |
| codeText | Text to be encoded. |

**Throws:** BarcodeException

**Example:**

```js
// This sample shows how to create and save a barcode image.
let encode_type = EncodeTypes.CODE_128;
let generator = new BarcodeGenerator(encode_type);
generator.setCodeText("123ABC");
```

## Methods

| Name | Description |
| --- | --- |
| [importFromXml(filePath)](./importfromxml/) *(static)* | Imports BarCode properties from the xml-file specified and creates BarcodeGenerator instance. |
| [exportToXml(filePath)](./exporttoxml/) | Exports BarCode properties to the xml file specified |
| [generateBarCodeImage(format)](./generatebarcodeimage/) | Generate the barcode image under current settings. This sample shows how to create and save a barcode image. |
| [getBarcodeType()](./getbarcodetype/) | Barcode symbology type. |
| [getCodeText()](./getcodetext/) | Text to be encoded. |
| [getParameters()](./getparameters/) | Generation parameters. |
| [save(filePath, format)](./save/) | Save barcode image to specific file in specific format. |
| [setBarcodeType()](./setbarcodetype/) | Barcode symbology type. |
| [setCodeText(codeText, encoding, insertBOM)](./setcodetext/) | Encodes the Unicode `codeText ` into a byte sequence using the specified `encoding `. UTF-8 is the most commonly used en |
