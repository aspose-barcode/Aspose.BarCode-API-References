---
title: "MaxiCodeStandardCodetext"
linktitle: "MaxiCodeStandardCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于对模式 4、5 和 6 的 MaxiCode 编码文本进行编码和解码的类。"
type: docs
weight: 670
url: /zh/nodejs/aspose.barcode/maxicodestandardcodetext/
---

## MaxiCodeStandardCodetext class

用于对模式 4、5 和 6 的 MaxiCode 编码文本进行编码和解码的类。

```js
new MaxiCodeStandardCodetext()
```

**Example:**

```js
//Mode 4
let maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
maxiCodeCodetext.setMessage("Test message");
let complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
complexGenerator.generateBarCodeImage(BarcodeImageFormat.PNG);
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals(obj)](#equals) | 返回一个值，指示此实例是否等于指定的值。 |
| [getConstructedCodetext()](#getconstructedcodetext) | 构造 codetext |
| [getHashCode()](#gethashcode) | 返回此实例的哈希码。 |
| [getMessage()](#getmessage) | 获取消息。 |
| [getMode()](#getmode) | 获取 MaxiCode 模式。 |
| [initFromString(constructedCodetext)](#initfromstring) | 从构造的 codetext 初始化实例。 |
| [setMessage()](#setmessage) | 设置消息。 |
| [setMode()](#setmode) | 设置 MaxiCode 模式。标准代码文本只能与模式 4、5 和 6 一起使用。 |

### equals(obj) {#equals}

返回一个值，指示此实例是否等于指定的值。

| 参数 | 描述 |
| --- | --- |
| obj | 一个用于与此实例比较的值。 |

**Returns:** if obj has the same value as this instance; otherwise, false .

### getConstructedCodetext() {#getconstructedcodetext}

构造 codetext

**Returns:** Constructed codetext

### getHashCode() {#gethashcode}

返回此实例的哈希码。

**Returns:** A 32-bit signed integer hash code

### getMessage() {#getmessage}

获取消息。

### getMode() {#getmode}

获取 MaxiCode 模式。

**Returns:** MaxiCode mode

### initFromString(constructedCodetext) {#initfromstring}

从构造的 codetext 初始化实例。

| 参数 | 描述 |
| --- | --- |
| constructedCodetext | 已构造的 codetext。 |

### setMessage() {#setmessage}

设置消息。

### setMode() {#setmode}

设置 MaxiCode 模式。标准代码文本只能与模式 4、5 和 6 一起使用。
