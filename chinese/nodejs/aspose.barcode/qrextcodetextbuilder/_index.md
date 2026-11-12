---
title: "QrExtCodetextBuilder"
linktitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于 QREncodeMode 的 ExtendedCodetext 模式的 2D QR 条码扩展码文本生成器 使用 BarCodeBuilder 的 Display2DText 属性将可见文本设置为 rem"
type: docs
weight: 820
url: /zh/nodejs/aspose.barcode/qrextcodetextbuilder/
---

## QrExtCodetextBuilder class

用于 QREncodeMode 的 ExtendedCodetext 模式的 2D QR 条码扩展码文本生成器 使用 BarCodeBuilder 的 Display2DText 属性将可见文本设置为删除管理字符。

```js
new QrExtCodetextBuilder()
```

**Example:**

```js
//Example how to generate FNC1 first position for Extended Mode
 //create codetext
 const lTextBuilder = new QrExtCodetextBuilder();
 lTextBuilder.addFNC1FirstPosition();
 lTextBuilder.addPlainCodetext("000%89%%0");
 lTextBuilder.addFNC1GroupSeparator();
 lTextBuilder.addPlainCodetext("12345&lt;FNC1&gt;");
 //generate codetext
 const lCodetext = lTextBuilder.getExtendedCodetext();
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [addCodetextWithCompactionMode(mode, codetext)](#addcodetextwithcompactionmode) | 将具有指定 QR 紧凑模式的代码文本添加到扩展代码文本项。 |
| [addFNC1FirstPosition()](#addfnc1firstposition) | 在第一位置添加 FNC1 到扩展代码文本项 |
| [addFNC1GroupSeparator()](#addfnc1groupseparator) | 将组分隔符 (GS - '\\u001D') 添加到扩展代码文本项 |
| [addFNC1SecondPosition(codetext)](#addfnc1secondposition) | 在第二位置添加 FNC1 到扩展代码文本项 |
| [clear()](#clear) | 清除扩展代码文本项 |
| [getExtendedCodetext()](#getextendedcodetext) | 从扩展码文本列表生成扩展码文本。 |

### addCodetextWithCompactionMode(mode, codetext) {#addcodetextwithcompactionmode}

将具有指定 QR 紧凑模式的代码文本添加到扩展代码文本项。

| 参数 | 描述 |
| --- | --- |
| 模式 | 代码文本的 QR 紧凑模式。 |
| codetext | 以 Unicode 编码的代码文本，用于添加为扩展代码文本项。 |

**Throws:** IllegalArgumentException The specified codetext cannot be encoded in the selected QR compaction mode.

### addFNC1FirstPosition() {#addfnc1firstposition}

在第一位置添加 FNC1 到扩展代码文本项

### addFNC1GroupSeparator() {#addfnc1groupseparator}

将组分隔符 (GS - '\\u001D') 添加到扩展代码文本项

### addFNC1SecondPosition(codetext) {#addfnc1secondposition}

在第二位置添加 FNC1 到扩展代码文本项

| 参数 | 描述 |
| --- | --- |
| codetext | 第二位置的 FNC1 值 |

### clear() {#clear}

清除扩展代码文本项

### getExtendedCodetext() {#getextendedcodetext}

从扩展码文本列表生成扩展码文本。

**Returns:** Extended codetext as string
