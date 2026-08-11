---
title: "BarcodeGenerator"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "BarcodeGenerator for backend barcode images generation."
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
| [importFromXml(filePath)](#importfromxml) *(static)* | Imports BarCode properties from the xml-file specified and creates BarcodeGenerator instance. |
| [exportToXml(filePath)](#exporttoxml) | Exports BarCode properties to the xml file specified |
| [generateBarCodeImage(format)](#generatebarcodeimage) | Generate the barcode image under current settings. This sample shows how to create and save a barcode image. |
| [getBarcodeType()](#getbarcodetype) | Barcode symbology type. |
| [getCodeText()](#getcodetext) | Text to be encoded. |
| [getParameters()](#getparameters) | Generation parameters. |
| [save(filePath, format)](#save) | Save barcode image to specific file in specific format. |
| [setBarcodeType()](#setbarcodetype) | Barcode symbology type. |
| [setCodeText(codeText, encoding, insertBOM)](#setcodetext) | Encodes the Unicode `codeText ` into a byte sequence using the specified `encoding `. UTF-8 is the most commonly used en |

### importFromXml(filePath) (static) {#importfromxml}

Imports BarCode properties from the xml-file specified and creates BarcodeGenerator instance.

| Parameter | Description |
| --- | --- |
| filePath | The name of the file |

**Returns:** BarcodeGenerator instance

### exportToXml(filePath) {#exporttoxml}

Exports BarCode properties to the xml file specified

| Parameter | Description |
| --- | --- |
| filePath | The xml file |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

**Throws:** IOException

### generateBarCodeImage(format) {#generatebarcodeimage}

Generate the barcode image under current settings. This sample shows how to create and save a barcode image.

| Parameter | Type | Description |
| --- | --- | --- |
| format | BarCodeImageFormat | BarCodeImageFormat value (PNG, BMP, JPEG, GIF) |

**Returns:** String — base64 representation of image.

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
let image = generator.generateBarCodeImage(BarCodeImageFormat.GIF);
```

### getBarcodeType() {#getbarcodetype}

Barcode symbology type.

### getCodeText() {#getcodetext}

Text to be encoded.

### getParameters() {#getparameters}

Generation parameters.

**Returns:** BaseGenerationParameters

### save(filePath, format) {#save}

Save barcode image to specific file in specific format.

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | Path to save to. |
| format | BarCodeImageFormat | BarCodeImageFormat value (PNG, BMP, JPEG, GIF) |

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
generator.save("file path", BarCodeImageFormat.GIF);
```

### setBarcodeType() {#setbarcodetype}

Barcode symbology type.

### setCodeText(codeText, encoding, insertBOM) {#setcodetext}

Encodes the Unicode `codeText ` into a byte sequence using the specified `encoding `. UTF-8 is the most commonly used encoding. If the encoding supports it and `insertBOM ` is set to `true`, the function includes a `byte order mark (BOM) `. This function is intended for use with 2D barcodes only (e.g., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, etc.). It enables manual encoding of Unicode text using national or special encodings; however, this method is considered obsolete in modern applications. For modern use cases, `ECI ` encoding is recommended for Unicode data. Using this function with 1D barcodes, GS1-compliant barcodes (including 2D), or HIBC barcodes (including 2D) is not supported by the corresponding barcode standards and may lead to unpredictable results. This example shows how to use `SetCodeText` with or without a BOM for 2D barcodes. //Encode codetext using UTF-8 with BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText("車種名", "UTF-8", true); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); } //Encode codetext using UTF-8 without BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText("車種名", "UTF-8", false); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

| Parameter | Description |
| --- | --- |
| codeText | CodeText string |
| encoding | Applied encoding |
| insertBOM | Indicates whether to insert a byte order mark (BOM) when the specified encoding supports it (e.g., UTF-8, UTF-16, UTF-32). If set to `true`, the BOM is added; if `false`, the BOM is omitted even if the encoding normally uses one. |
