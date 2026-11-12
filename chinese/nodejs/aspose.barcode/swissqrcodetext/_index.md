---
title: "SwissQRCodetext"
linktitle: "SwissQRCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于对嵌入在 SwissQR 代码中的文本进行编码和解码的类。"
type: docs
weight: 930
url: /zh/nodejs/aspose.barcode/swissqrcodetext/
---

## SwissQRCodetext class

用于对嵌入在 SwissQR 代码中的文本进行编码和解码的类。

```js
new SwissQRCodetext(bill)
```

创建 SwissQRCodetext 的实例。

| 参数 | 描述 |
| --- | --- |
| bill | SwissQR 账单数据 |

**Throws:** BarcodeException

## 方法

| 名称 | 描述 |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | 获取条形码类型。 |
| [getBill()](#getbill) | SwissQR 账单数据 |
| [getConstructedCodetext()](#getconstructedcodetext) | 从 SwissQR 账单数据构建 codetext |
| [initFromString(constructedCodetext)](#initfromstring) | 使用构建的 codetext 初始化 Bill。 |

### getBarcodeType() {#getbarcodetype}

获取条形码类型。

**Returns:** Barcode type.

### getBill() {#getbill}

SwissQR 账单数据

### getConstructedCodetext() {#getconstructedcodetext}

从 SwissQR 账单数据构建 codetext

**Returns:** Constructed codetext

### initFromString(constructedCodetext) {#initfromstring}

使用构建的 codetext 初始化 Bill。

| 参数 | 描述 |
| --- | --- |
| constructedCodetext | 已构造的 codetext。 |
