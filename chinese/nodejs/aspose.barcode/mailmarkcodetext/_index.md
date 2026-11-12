---
title: "MailmarkCodetext"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于对嵌入 4 状态 Royal Mailmark 代码中的文本进行编码和解码的类。"
type: docs
weight: 580
url: /zh/nodejs/aspose.barcode/mailmarkcodetext/
---

## MailmarkCodetext class

用于对嵌入 4 状态 Royal Mailmark 代码中的文本进行编码和解码的类。

```js
new MailmarkCodetext()
```

初始化 `MailmarkCodetext` 类的新实例。

## 方法

| 名称 | 描述 |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | 获取条形码类型。 |
| [getClass_()](#getclass-) | "0" - 空或测试 "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - 高级 (RetailPublishing Mail) (用于 pote |
| [getConstructedCodetext()](#getconstructedcodetext) | 从 Mailmark 数据构建代码文本。 |
| [getDestinationPostCodePlusDPS()](#getdestinationpostcodeplusdps) | PC 和 DP 必须符合 PAF 格式。九字符字符串表示国际 "XY11 "（注意后面 5 个空格） |
| [getFormat()](#getformat) | "0" – 空或测试 "1" – 字母 "2" – 大写字母 |
| [getItemID()](#getitemid) | 最大值为 99999999。 |
| [getSupplychainID()](#getsupplychainid) | Barcode C 的最大值为 99，Barcode L 的最大值为 999999。 |
| [getVersionID()](#getversionid) | 当前 "1" – 用于 Mailmark 条形码（0 以及 2 到 9 和 A 到 Z 预留供将来使用） |
| [initFromString(constructedCodetext)](#initfromstring) | 从构建的代码文本初始化 Mailmark 数据。 |
| [setClass_()](#setclass-) | "0" - 空或测试 "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - 高级 (RetailPublishing Mail) (用于 pote |
| [setDestinationPostCodePlusDPS()](#setdestinationpostcodeplusdps) | PC 和 DP 必须符合 PAF 格式。九字符字符串表示国际 "XY11 "（注意后面 5 个空格） |
| [setFormat()](#setformat) | "0" – 空或测试 "1" – LetterN "2" – 大写字母 |
| [setItemID()](#setitemid) | 最大值为 99999999。 |
| [setSupplychainID()](#setsupplychainid) | Barcode C 的最大值为 99，Barcode L 的最大值为 999999。 |
| [setVersionID()](#setversionid) | 当前 "1" – 用于 Mailmark 条形码（0 以及 2 到 9 和 A 到 Z 预留供将来使用） |

### getBarcodeType() {#getbarcodetype}

获取条形码类型。

**Returns:** Barcode type.

### getClass_() {#getclass-}

"0" - 空或测试 "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - 高级 (RetailPublishing Mail) (用于潜在的未来使用) "5" - 延迟 (Retail) "6" - 空中 (Retail) (用于潜在的未来使用) "7" - 表面 (Retail) (用于潜在的未来使用) "8" - 高级 (Network Access) "9" - 标准 (Network Access)

### getConstructedCodetext() {#getconstructedcodetext}

从 Mailmark 数据构建代码文本。

**Returns:** Constructed codetext

### getDestinationPostCodePlusDPS() {#getdestinationpostcodeplusdps}

PC 和 DP 必须符合 PAF 格式。九字符字符串表示国际 "XY11 "（注意后面 5 个空格）或表示国内分拣代码的字符模式。国内分拣代码由外部邮编、内部邮编和投递点后缀组成。

### getFormat() {#getformat}

"0" – 空或测试 "1" – 字母 "2" – 大写字母

### getItemID() {#getitemid}

最大值为 99999999。

### getSupplychainID() {#getsupplychainid}

Barcode C 的最大值为 99，Barcode L 的最大值为 999999。

### getVersionID() {#getversionid}

当前 "1" – 用于 Mailmark 条形码（0 以及 2 到 9 和 A 到 Z 预留供将来使用）

### initFromString(constructedCodetext) {#initfromstring}

从构建的代码文本初始化 Mailmark 数据。

| 参数 | 描述 |
| --- | --- |
| constructedCodetext | 已构造的 codetext。 |

### setClass_() {#setclass-}

"0" - 空或测试 "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - 高级 (RetailPublishing Mail) (用于潜在的未来使用) "5" - 延迟 (Retail) "6" - 空中 (Retail) (用于潜在的未来使用) "7" - 表面 (Retail) (用于潜在的未来使用) "8" - 高级 (Network Access) "9" - 标准 (Network Access)

### setDestinationPostCodePlusDPS() {#setdestinationpostcodeplusdps}

PC 和 DP 必须符合 PAF 格式。九字符字符串表示国际 "XY11 "（注意后面 5 个空格）或表示国内分拣代码的字符模式。国内分拣代码由外部邮编、内部邮编和投递点后缀组成。

### setFormat() {#setformat}

"0" – 空或测试 "1" – LetterN "2" – 大写字母

### setItemID() {#setitemid}

最大值为 99999999。

### setSupplychainID() {#setsupplychainid}

Barcode C 的最大值为 99，Barcode L 的最大值为 999999。

### setVersionID() {#setversionid}

当前 "1" – 用于 Mailmark 条形码（0 以及 2 到 9 和 A 到 Z 预留供将来使用）
