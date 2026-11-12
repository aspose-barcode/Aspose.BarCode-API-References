---
title: "HIBCLICComplexCodetext"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于对嵌入在 HIBC LIC 代码中的文本进行编码和解码的基类。"
type: docs
weight: 450
url: /zh/nodejs/aspose.barcode/hibcliccomplexcodetext/
---

## HIBCLICComplexCodetext class

用于对嵌入在 HIBC LIC 代码中的文本进行编码和解码的基类。此示例展示了如何将原始 HIBC LIC codetext 解码为 HIBCLICComplexCodetext 实例。

```js
new HIBCLICComplexCodetext()
```

**Example:**

```js
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.HIBC_AZTEC_LIC);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
   let resultHIBCLICComplexCodetext = ComplexCodetextReader.tryDecodeHIBCLIC(result.getCodeText());
   print("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
   print("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
}
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | 获取或设置条形码类型。HIBC LIC codetext 可以使用 HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataM 进行编码。 |
| [getConstructedCodetext()](#getconstructedcodetext) | 构造 codetext |
| [initFromString(constructedCodetext)](#initfromstring) | 从构造的 codetext 初始化实例。 |
| [setBarcodeType()](#setbarcodetype) | 获取或设置条形码类型。HIBC LIC codetext 可以使用 HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataM 进行编码。 |

### getBarcodeType() {#getbarcodetype}

获取或设置条形码类型。HIBC LIC codetext 可以使用 HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC 和 HIBCQRLIC 编码类型进行编码。默认值：HIBCCode39LIC。

**Returns:** Barcode type.

### getConstructedCodetext() {#getconstructedcodetext}

构造 codetext

**Returns:** Constructed codetext

### initFromString(constructedCodetext) {#initfromstring}

从构造的 codetext 初始化实例。

| 参数 | 描述 |
| --- | --- |
| constructedCodetext | 已构造的 codetext。 |

### setBarcodeType() {#setbarcodetype}

获取或设置条形码类型。HIBC LIC codetext 可以使用 HIBCCode39LIC、HIBCCode128LIC、HIBCAztecLIC、HIBCDataMatrixLIC 和 HIBCQRLIC 编码类型进行编码。默认值：HIBCCode39LIC。

**Returns:** Barcode type.
