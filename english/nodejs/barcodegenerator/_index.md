---
title: BarcodeGenerator Class
linktitle: BarcodeGenerator
articleTitle: BarcodeGenerator
second_title: Aspose.BarCode for Node.js via Java
description: BarcodeGenerator for backend barcode images generation. supported symbologies: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14...
type: docs
weight: 440
url: /nodejs/barcodegenerator/
---
## BarcodeGenerator class

BarcodeGenerator for backend barcode images generation. supported symbologies: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

```javascript
public class BarcodeGenerator : joint.BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [BarcodeGenerator](./barcodegenerator/#constructor)(*object, object*) | BarcodeGenerator constructor. |

## Methods

| Name | Description |
| --- | --- |
| [construct](./construct/)(*object*) |  |
| [exportToXml](./exporttoxml/)(*object*) | Exports BarCode properties to the xml file specified. |
| [generateBarCodeImage](./generatebarcodeimage/)(*object*) | Generate the barcode image under current settings. This sample shows how to create and save a barcode image. |
| [getBarcodeType](./getbarcodetype/) | Barcode symbology type. |
| [getCodeText](./getcodetext/) | Text to be encoded. |
| [getParameters](./getparameters/) | Generation parameters. |
| [importFromXml](./importfromxml/)(*object*) | Imports BarCode properties from the xml-file specified and creates BarcodeGenerator instance. |
| [init](./init/) |  |
| [javaClassName](./javaclassname/) |  |
| [save](./save/)(*object, object*) | Save barcode image to specific file in specific format. |
| [setBarcodeType](./setbarcodetype/)(*object*) | Barcode symbology type. |
| [setCodeText](./setcodetext/)(*object, object, object*) | Encodes the Unicode codeText into a byte sequence using the specified encoding. UTF-8 is the most commonly used encoding. If the encoding supports it and insertBOM is set to true, the function includes a byte order mark (BOM). |

## Fields

| Name | Description |
| --- | --- |
| [parameters](./parameters/) |  |

## Examples

```javascript
// This sample shows how to create and save a barcode image.
let encode_type = EncodeTypes.CODE_128;
let generator = new BarcodeGenerator(encode_type);
generator.setCodeText("123ABC");
```

### See Also

* assembly [Aspose.BarCode](../)

