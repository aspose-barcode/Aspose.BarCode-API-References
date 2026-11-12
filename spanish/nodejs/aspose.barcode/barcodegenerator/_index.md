---
title: "BarcodeGenerator"
linktitle: "BarcodeGenerator"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "BarcodeGenerator para la generación de imágenes de códigos de barras en el backend."
type: docs
weight: 130
url: /es/nodejs/aspose.barcode/barcodegenerator/
---

## BarcodeGenerator class

BarcodeGenerator para la generación de imágenes de códigos de barras en el backend. symbologías compatibles: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

```js
new BarcodeGenerator(encodeType, codeText)
```

Constructor de BarcodeGenerator.

| Parámetro | Descripción |
| --- | --- |
| encodeType | Tipo de simbología de código de barras. Use la clase EncodeTypes para configurar una simbología. |
| codeText | Texto a codificar. |

**Throws:** BarcodeException

**Example:**

```js
// This sample shows how to create and save a barcode image.
let encode_type = EncodeTypes.CODE_128;
let generator = new BarcodeGenerator(encode_type);
generator.setCodeText("123ABC");
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [importFromXml(filePath)](#importfromxml) *(static)* | Importa las propiedades de BarCode del archivo xml especificado y crea una instancia de BarcodeGenerator. |
| [exportToXml(filePath)](#exporttoxml) | Exporta las propiedades de BarCode al archivo xml especificado. |
| [generateBarCodeImage(format)](#generatebarcodeimage) | Genera la imagen del código de barras con la configuración actual. Este ejemplo muestra cómo crear y guardar una imagen de código de barras. |
| [getBarcodeType()](#getbarcodetype) | Tipo de simbología de código de barras. |
| [getCodeText()](#getcodetext) | Texto a codificar. |
| [getParameters()](#getparameters) | Parámetros de generación. |
| [save(filePath, format)](#save) | Guarda la imagen del código de barras en un archivo específico con un formato específico. |
| [setBarcodeType()](#setbarcodetype) | Tipo de simbología de código de barras. |
| [setCodeText(codeText, encoding, insertBOM)](#setcodetext) | Codifica el Unicode `codeText ` en una secuencia de bytes usando la `encoding ` especificada. UTF-8 es la más utilizada en |

### importFromXml(filePath) (static) {#importfromxml}

Importa las propiedades de BarCode del archivo xml especificado y crea una instancia de BarcodeGenerator.

| Parámetro | Descripción |
| --- | --- |
| filePath | El nombre del archivo |

**Returns:** BarcodeGenerator instance

### exportToXml(filePath) {#exporttoxml}

Exporta las propiedades de BarCode al archivo xml especificado.

| Parámetro | Descripción |
| --- | --- |
| filePath | El archivo xml |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

**Throws:** IOException

### generateBarCodeImage(format) {#generatebarcodeimage}

Genera la imagen del código de barras con la configuración actual. Este ejemplo muestra cómo crear y guardar una imagen de código de barras.

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formato | BarCodeImageFormat | BarCodeImageFormat valor (PNG, BMP, JPEG, GIF) |

**Returns:** String — base64 representation of image.

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
let image = generator.generateBarCodeImage(BarCodeImageFormat.GIF);
```

### getBarcodeType() {#getbarcodetype}

Tipo de simbología de código de barras.

### getCodeText() {#getcodetext}

Texto a codificar.

### getParameters() {#getparameters}

Parámetros de generación.

**Returns:** BaseGenerationParameters

### save(filePath, format) {#save}

Guarda la imagen del código de barras en un archivo específico con un formato específico.

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | Ruta para guardar. |
| formato | BarCodeImageFormat | BarCodeImageFormat valor (PNG, BMP, JPEG, GIF) |

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
generator.save("file path", BarCodeImageFormat.GIF);
```

### setBarcodeType() {#setbarcodetype}

Tipo de simbología de código de barras.

### setCodeText(codeText, encoding, insertBOM) {#setcodetext}

Codifica el Unicode `codeText ` en una secuencia de bytes usando la `encoding ` especificada. UTF-8 es la codificación más utilizada. Si la codificación lo admite y `insertBOM ` está configurado a `true`, la función incluye una `marca de orden de bytes (BOM) `. Esta función está destinada solo al uso con códigos de barras 2D (p. ej., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, etc.). Permite la codificación manual de texto Unicode usando codificaciones nacionales o especiales; sin embargo, este método se considera obsoleto en aplicaciones modernas. Para casos de uso actuales, se recomienda la codificación `ECI ` para datos Unicode. Usar esta función con códigos de barras 1D, códigos de barras compatibles con GS1 (incluidos 2D), o códigos de barras HIBC (incluidos 2D) no está soportado por los estándares de códigos de barras correspondientes y puede producir resultados impredecibles. Este ejemplo muestra cómo usar `SetCodeText` con o sin BOM para códigos de barras 2D. //Encode codetext using UTF-8 with BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText("車種名", "UTF-8", true); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); } //Encode codetext using UTF-8 without BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText("車種名", "UTF-8", false); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

| Parámetro | Descripción |
| --- | --- |
| codeText | Cadena CodeText |
| codificación | Codificación aplicada |
| insertBOM | Indica si se debe insertar una marca de orden de bytes (BOM) cuando la codificación especificada lo admite (p. ej., UTF-8, UTF-16, UTF-32). Si se establece a `true`, se agrega el BOM; si es `false`, el BOM se omite incluso si la codificación normalmente lo utiliza. |
