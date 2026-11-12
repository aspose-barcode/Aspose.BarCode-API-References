---
title: "BarCodeResult"
linktitle: "BarCodeResult"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "存储已识别的条码数据，如 SingleDecodeType 类型、`string` codetext、BarCodeRegionParameters 区域以及其他参数"
type: docs
weight: 110
url: /zh/nodejs/aspose.barcode/barcoderesult/
---

## BarCodeResult class

存储已识别的条码数据，如 SingleDecodeType 类型、`string` codetext、BarCodeRegionParameters 区域以及其他参数

```js
new BarCodeResult()
```

**Example:**

```js
//This sample shows how to obtain BarCodeResult.
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("BarCode Confidence: " + result.getConfidence());
    console.log("BarCode ReadingQuality: " + result.getReadingQuality());
    console.log("BarCode Angle: " + result.getRegion().getAngle());
}
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [deepClone()](#deepclone) | 创建 BarCodeResult 类的副本。 |
| [equals(other)](#equals) | 返回一个值，指示此实例是否等于指定的 BarCodeResult 值。 |
| [getCodeBytes()](#getcodebytes) | 获取已编码的代码字节 值：条码的代码字节 |
| [getCodeText(encoding)](#getcodetext) | 获取带编码的代码文本。此示例展示如何使用 `getCodeText`：let gen = new BarcodeGenerator(EncodeType |
| [getCodeType()](#getcodetype) | 获取条码类型 值：已识别条码的类型信息 |
| [getCodeTypeName()](#getcodetypename) | 获取条码类型的名称 值：已识别条码的类型名称 |
| [getConfidence()](#getconfidence) | 获取已识别条码的识别置信度 值：BarCodeConfidence.Strong 不会出现伪造或误识别 |
| [getExtended()](#getextended) | 获取已识别条码的扩展参数 值：已识别条码的扩展参数 |
| [getReadingQuality()](#getreadingquality) | 获取读取质量。适用于 1D 和邮政条码。值：读取质量百分比 |
| [getRegion()](#getregion) | 获取条码区域 值：已识别条码的区域 |
| [hashCode()](#hashcode) | 返回此实例的哈希码。 |
| [toString()](#tostring) | 返回此 BarCodeResult 的人类可读字符串表示。 |

### deepClone() {#deepclone}

创建 BarCodeResult 类的副本。

**Returns:** Returns copy of BarCodeResult class.

### equals(other) {#equals}

返回一个值，指示此实例是否等于指定的 BarCodeResult 值。

| 参数 | 描述 |
| --- | --- |
| 其他 | 一个用于与此实例比较的 BarCodeResult 值。 |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getCodeBytes() {#getcodebytes}

获取已编码的代码字节 值：条码的代码字节

### getCodeText(encoding) {#getcodetext}

获取带编码的代码文本。此示例展示如何使用 `getCodeText`：let gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null); gen.setCodeText("車種名", "932"); gen.save("barcode.png", BarCodeImageFormat.PNG); let reader = new BarCodeReader("barcode.png", null, DecodeType.DATA_MATRIX); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText("932")); }

| 参数 | 描述 |
| --- | --- |
| 编码 | codetext 的编码。 |

**Returns:** A string containing recognized code text.

### getCodeType() {#getcodetype}

获取条码类型 值：已识别条码的类型信息

### getCodeTypeName() {#getcodetypename}

获取条码类型的名称 值：已识别条码的类型名称

### getConfidence() {#getconfidence}

获取已识别条码的识别置信度 值：BarCodeConfidence.Strong 不会出现伪造或误识别，BarCodeConfidence.Moderate 有时可能出现伪造或不正确的 codetext，因为此置信度适用于校验和弱或甚至没有校验和的条码，BarCodeConfidence.NONE 总是会出现不正确的 codetext 并可能是伪造的识别

### getExtended() {#getextended}

获取已识别条码的扩展参数 值：已识别条码的扩展参数

### getReadingQuality() {#getreadingquality}

获取读取质量。适用于 1D 和邮政条码。值：读取质量百分比

### getRegion() {#getregion}

获取条码区域 值：已识别条码的区域

### hashCode() {#hashcode}

返回此实例的哈希码。

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

返回此 BarCodeResult 的人类可读字符串表示。

**Returns:** A string that represents this BarCodeResult.
