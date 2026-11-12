---
title: "ExtCodetextBuilder"
linktitle: "ExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于自动生成扩展码文本模式的帮助类。"
type: docs
weight: 400
url: /zh/nodejs/aspose.barcode/extcodetextbuilder/
---

## ExtCodetextBuilder class

用于自动生成扩展码文本模式的帮助类。

```js
new ExtCodetextBuilder()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [addECICodetext(ECIEncoding, codetext)](#addecicodetext) | 添加带有扩展通道标识符的代码文本 |
| [addPlainCodetext(codetext)](#addplaincodetext) | 向扩展代码文本项添加普通代码文本 |
| [clear()](#clear) | 清除扩展代码文本项 |
| [getExtendedCodetext()](#getextendedcodetext) | 从生成项列表生成扩展代码文本 |

### addECICodetext(ECIEncoding, codetext) {#addecicodetext}

添加带有扩展通道标识符的代码文本

| 参数 | 描述 |
| --- | --- |
| ECIEncoding | 扩展通道标识符 |
| codetext | 以 Unicode 编码的代码文本，作为带有扩展通道标识符的扩展代码文本项添加 |

### addPlainCodetext(codetext) {#addplaincodetext}

向扩展代码文本项添加普通代码文本

| 参数 | 描述 |
| --- | --- |
| codetext | 以 Unicode 形式的代码文本，用于添加为扩展代码文本项 |

### clear() {#clear}

清除扩展代码文本项

### getExtendedCodetext() {#getextendedcodetext}

从生成项列表生成扩展代码文本

**Returns:** Return string of extended codetext
