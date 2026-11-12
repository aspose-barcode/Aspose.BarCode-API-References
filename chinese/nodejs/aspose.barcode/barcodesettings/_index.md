---
title: "BarcodeSettings"
linktitle: "BarcodeSettings"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "主要的 BarCode 解码参数。"
type: docs
weight: 150
url: /zh/nodejs/aspose.barcode/barcodesettings/
---

## BarcodeSettings class

主要的 BarCode 解码参数。包含对识别数据产生影响的参数。

```js
new BarcodeSettings(settings)
```

BarcodeSettings 复制构造函数

| 参数 | 描述 |
| --- | --- |
| settings | 数据的来源 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [getAustraliaPost()](#getaustraliapost) | 获取 AustraliaPost 解码参数 |
| [getChecksumValidation()](#getchecksumvalidation) | 在识别 1D 和邮政条码时启用校验和验证。默认情况下对该类符号视为是。 |
| [getDetectEncoding()](#getdetectencoding) | 强制引擎检测 Unicode 代码集的代码文本编码的标志。默认值为 true。 |
| [getStripFNC()](#getstripfnc) | 从代码文本中剥离 FNC1、FNC2、FNC3 字符。默认值为 false。 |
| [isOnlyRequestedTypes()](#isonlyrequestedtypes) | 仅返回明确指定用于识别的条码类型。启用后，其他兼容的条码将被过滤。 |
| [setChecksumValidation(value)](#setchecksumvalidation) | 在识别 1D 和邮政条码时启用校验和验证。默认情况下对该类符号视为是。 |
| [setDetectEncoding()](#setdetectencoding) | 强制引擎检测 Unicode 代码集的代码文本编码的标志。默认值为 true。 |
| [setOnlyRequestedTypes()](#setonlyrequestedtypes) | 仅返回明确指定用于识别的条码类型。启用后，其他兼容的条码将被过滤。 |
| [setStripFNC(value)](#setstripfnc) | 从代码文本中剥离 FNC1、FNC2、FNC3 字符。默认值为 false。 |

### getAustraliaPost() {#getaustraliapost}

获取 AustraliaPost 解码参数

**Returns:** The AustraliaPost decoding parameters which make influence on recognized data of AustraliaPost symbology

### getChecksumValidation() {#getchecksumvalidation}

在识别 1D 和邮政条码时启用校验和验证。默认情况下，对必须包含校验和的符号视为 Yes，对仅可能包含校验和的符号视为 No。以下符号从不使用校验和：Codabar、PatchCode、Pharmacode、DataLogic2of5。以下符号可能使用校验和：Code39 Standard/Extended、Standard2of5、Interleaved2of5、ItalianPost25、Matrix2of5、MSI、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN。其余符号始终使用校验和。

**Returns:** Enable checksum validation during recognition for 1D and Postal barcodes.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### getDetectEncoding() {#getdetectencoding}

强制引擎检测 Unicode 代码集的代码文本编码的标志。默认值为 true。

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### getStripFNC() {#getstripfnc}

从代码文本中剥离 FNC1、FNC2、FNC3 字符。默认值为 false。

**Returns:** Strip FNC1, FNC2, FNC3 characters from codetext. Default value is false.

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### isOnlyRequestedTypes() {#isonlyrequestedtypes}

仅返回明确指定用于识别的条码类型。启用后，其他兼容或等效类型的已识别条码将被过滤。默认值为 false。示例： // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setChecksumValidation(value) {#setchecksumvalidation}

在识别 1D 和邮政条码时启用校验和验证。默认情况下，对必须包含校验和的符号视为 Yes，对仅可能包含校验和的符号视为 No。以下符号从不使用校验和：Codabar、PatchCode、Pharmacode、DataLogic2of5。以下符号可能使用校验和：Code39 Standard/Extended、Standard2of5、Interleaved2of5、ItalianPost25、Matrix2of5、MSI、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN。其余符号始终使用校验和。

| 参数 | 描述 |
| --- | --- |
| 值 | 在识别 1D 和邮政条码时启用校验和验证。 |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
     let result = results[i];
     console.log ("BarCode CodeText: " + result.getCodeText());
     console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
     console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### setDetectEncoding() {#setdetectencoding}

强制引擎检测 Unicode 代码集的代码文本编码的标志。默认值为 true。

**Returns:** The flag which force engine to detect codetext encoding for Unicode codesets

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.QR, "Слово"))
im = generator.generateBarcodeImage(BarcodeImageFormat.PNG);

//detects encoding for Unicode codesets is enabled
let reader = new BarCodeReader(im, DecodeType.QR);
reader.getBarcodeSettings().setDetectEncoding(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```

### setOnlyRequestedTypes() {#setonlyrequestedtypes}

仅返回明确指定用于识别的条码类型。启用后，其他兼容或等效类型的已识别条码将被过滤。默认值为 false。示例： // generate EAN13 barcode let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "2383823482894"); generator.save("test.png"); // recognize only UPCA barcodes (no results, because source is EAN13) const reader = new BarCodeReader("test.png", null, DecodeType.UPCA); reader.getBarcodeSettings().setOnlyRequestedTypes(true); let results = reader.readBarCodes(); for (let i = 0; i < results.length; i++) { console.log("BarCode CodeText: " + results[i].getCodeText()); } // recognize compatible types: EAN13, UPCA, ISSN, ISMN, ISBN // (EAN13 will be returned as UPCA-equivalent) let reader2 = new BarCodeReader("test.png", null, DecodeType.UPCA); reader2.getBarcodeSettings().setOnlyRequestedTypes(false); let results2 = reader2.readBarCodes(); for (let i = 0; i < results2.length; i++) { console.log("BarCode CodeText: " + results2[i].getCodeText()); }

**Returns:** true if only explicitly requested barcode types are returned; otherwise false

### setStripFNC(value) {#setstripfnc}

从代码文本中剥离 FNC1、FNC2、FNC3 字符。默认值为 false。

| 参数 | 描述 |
| --- | --- |
| 值 | 从代码文本中剥离 FNC1、FNC2、FNC3 字符。默认值为 false。 |

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.GS_1_CODE_128, "(02)04006664241007(37)1(400)7019590754");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.CODE_128);

//StripFNC disabled
reader.getBarcodeSettings().setStripFNC(false);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log ("BarCode CodeText: " + result.getCodeText());
}
```
