---
title: "BarcodeGenerator"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于后端条形码图像生成的 BarcodeGenerator。"
type: docs
weight: 130
url: /zh/nodejs/aspose.barcode/barcodegenerator/
---

## BarcodeGenerator class

用于后端条形码图像生成的 BarcodeGenerator。支持的符号集：1D：Codabar、Code11、Code128、Code39Standard、Code39Extended、Code93Standard、Code93Extended、EAN13、EAN8、Interleaved2of5、MSI、Standard2of5、UPCA、UPCE、ISBN、GS1Code128、Postnet、Planet、EAN14、SCC14、SSCC18、ITF14、SingaporePost ... 2D：Aztec、DataMatrix、PDf417、QR code ...

```js
new BarcodeGenerator(encodeType, codeText)
```

BarcodeGenerator 构造函数。

| 参数 | 描述 |
| --- | --- |
| encodeType | 条形码符号类型。使用 EncodeTypes 类来设置符号。 |
| codeText | 要编码的文本。 |

**Throws:** BarcodeException

**Example:**

```js
// This sample shows how to create and save a barcode image.
let encode_type = EncodeTypes.CODE_128;
let generator = new BarcodeGenerator(encode_type);
generator.setCodeText("123ABC");
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [importFromXml(filePath)](#importfromxml) *(static)* | 从指定的 xml 文件导入 BarCode 属性并创建 BarcodeGenerator 实例。 |
| [exportToXml(filePath)](#exporttoxml) | 将 BarCode 属性导出到指定的 xml 文件。 |
| [generateBarCodeImage(format)](#generatebarcodeimage) | 根据当前设置生成条形码图像。此示例展示了如何创建和保存条形码图像。 |
| [getBarcodeType()](#getbarcodetype) | 条形码符号类型。 |
| [getCodeText()](#getcodetext) | 要编码的文本。 |
| [getParameters()](#getparameters) | 生成参数。 |
| [save(filePath, format)](#save) | 将条形码图像保存为特定格式的特定文件。 |
| [setBarcodeType()](#setbarcodetype) | 条形码符号类型。 |
| [setCodeText(codeText, encoding, insertBOM)](#setcodetext) | 使用指定的 `encoding` 将 Unicode `codeText` 编码为字节序列。UTF-8 是最常用的。 |

### importFromXml(filePath) (static) {#importfromxml}

从指定的 xml 文件导入 BarCode 属性并创建 BarcodeGenerator 实例。

| 参数 | 描述 |
| --- | --- |
| filePath | 文件的名称 |

**Returns:** BarcodeGenerator instance

### exportToXml(filePath) {#exporttoxml}

将 BarCode 属性导出到指定的 xml 文件。

| 参数 | 描述 |
| --- | --- |
| filePath | 该 XML 文件 |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

**Throws:** IOException

### generateBarCodeImage(format) {#generatebarcodeimage}

根据当前设置生成条形码图像。此示例展示了如何创建和保存条形码图像。

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 格式 | BarCodeImageFormat | BarCodeImageFormat 值（PNG、BMP、JPEG、GIF） |

**Returns:** String — base64 representation of image.

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
let image = generator.generateBarCodeImage(BarCodeImageFormat.GIF);
```

### getBarcodeType() {#getbarcodetype}

条形码符号类型。

### getCodeText() {#getcodetext}

要编码的文本。

### getParameters() {#getparameters}

生成参数。

**Returns:** BaseGenerationParameters

### save(filePath, format) {#save}

将条形码图像保存为特定格式的特定文件。

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | 字符串 | 保存路径。 |
| 格式 | BarCodeImageFormat | BarCodeImageFormat 值（PNG、BMP、JPEG、GIF） |

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
generator.save("file path", BarCodeImageFormat.GIF);
```

### setBarcodeType() {#setbarcodetype}

条形码符号类型。

### setCodeText(codeText, encoding, insertBOM) {#setcodetext}

使用指定的 `encoding` 将 Unicode `codeText` 编码为字节序列。UTF-8 是最常用的编码。如果编码支持且 `insertBOM` 被设置为 `true`，函数会包含 `字节顺序标记 (BOM)`。此函数仅用于 2D 条码（例如 Aztec、QR、DataMatrix、PDF417、MaxiCode、DotCode、HanXin、RectMicroQR 等）。它允许使用国家或特殊编码手动编码 Unicode 文本；但在现代应用中此方法已被视为过时。对于现代使用场景，建议使用 `ECI` 编码来处理 Unicode 数据。使用此函数处理 1D 条码、符合 GS1 标准的条码（包括 2D）或 HIBC 条码（包括 2D）不受相应条码标准支持，可能导致不可预测的结果。以下示例展示了如何在 2D 条码中使用或不使用 BOM 调用 `SetCodeText`。\n//Encode codetext using UTF-8 with BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText(\"車種名\", \"UTF-8\", true); gen.save(\"barcode.png\", BarCodeImageFormat.PNG); let reader = new BarCodeReader(\"barcode.png\", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log(\"BarCode CodeText: \" + result.getCodeText()); }\n//Encode codetext using UTF-8 without BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText(\"車種名\", \"UTF-8\", false); gen.save(\"barcode.png\", BarCodeImageFormat.PNG); let reader = new BarCodeReader(\"barcode.png\", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log(\"BarCode CodeText: \" + result.getCodeText()); }

| 参数 | 描述 |
| --- | --- |
| codeText | CodeText 字符串 |
| 编码 | 使用的编码 |
| insertBOM | 指示在指定的编码支持时（例如 UTF-8、UTF-16、UTF-32）是否插入字节顺序标记 (BOM)。如果设置为 `true`，则添加 BOM；如果为 `false`，即使编码通常使用 BOM 也会省略。 |
