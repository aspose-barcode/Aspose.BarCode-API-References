---
title: "PrimaryData"
linktitle: "PrimaryData"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于存储 HIBC LIC 主数据的类。"
type: docs
weight: 800
url: /zh/nodejs/aspose.barcode/primarydata/
---

## PrimaryData class

用于存储 HIBC LIC 主数据的类。

```js
new PrimaryData()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals(obj)](#equals) | 返回一个值，指示此实例是否等于指定的 `PrimaryData` 值。 |
| [getLabelerIdentificationCode()](#getlabeleridentificationcode) | 标识标签者识别码的日期。标签者识别码必须是 4 个字符的字母数字字符串，且 |
| [getProductOrCatalogNumber()](#getproductorcatalognumber) | 标识产品或目录编号。产品或目录编号必须是最长 18 个字符的字母数字字符串。 |
| [getUnitOfMeasureID()](#getunitofmeasureid) | 标识计量单位 ID。计量单位 ID 必须是 0 到 9 的整数值。 |
| [hashCode()](#hashcode) | 返回此实例的哈希码。 |
| [parseFromString(primaryDataCodetext)](#parsefromstring) | 根据 HIBC LIC 规范，从字符串格式实例化主数据。 |
| [setLabelerIdentificationCode()](#setlabeleridentificationcode) | 标识标签者识别码的日期。标签者识别码必须是 4 个字符的字母数字字符串，且 |
| [setProductOrCatalogNumber()](#setproductorcatalognumber) | 标识产品或目录编号。产品或目录编号必须是最长 18 个字符的字母数字字符串。 |
| [setUnitOfMeasureID()](#setunitofmeasureid) | 标识计量单位 ID。计量单位 ID 必须是 0 到 9 的整数值。 |
| [toString()](#tostring) | 根据 HIBC LIC 规范将数据转换为字符串格式。 |

### equals(obj) {#equals}

返回一个值，指示此实例是否等于指定的 `PrimaryData` 值。

| 参数 | 描述 |
| --- | --- |
| obj | 用于与此实例比较的 `PrimaryData` 值。 |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getLabelerIdentificationCode() {#getlabeleridentificationcode}

标识标签者识别码的日期。标签者识别码必须是 4 个字符的字母数字字符串，且首字符必须为字母。

### getProductOrCatalogNumber() {#getproductorcatalognumber}

标识产品或目录编号。产品或目录编号必须是最长 18 个字符的字母数字字符串。

### getUnitOfMeasureID() {#getunitofmeasureid}

标识计量单位 ID。计量单位 ID 必须是 0 到 9 的整数值。

### hashCode() {#hashcode}

返回此实例的哈希码。

**Returns:** A 32-bit signed integer hash code.

### parseFromString(primaryDataCodetext) {#parsefromstring}

根据 HIBC LIC 规范，从字符串格式实例化主数据。

| 参数 | 描述 |
| --- | --- |
| primaryDataCodetext | 格式化字符串。 |

### setLabelerIdentificationCode() {#setlabeleridentificationcode}

标识标签者识别码的日期。标签者识别码必须是 4 个字符的字母数字字符串，且首字符必须为字母。

### setProductOrCatalogNumber() {#setproductorcatalognumber}

标识产品或目录编号。产品或目录编号必须是最长 18 个字符的字母数字字符串。

### setUnitOfMeasureID() {#setunitofmeasureid}

标识计量单位 ID。计量单位 ID 必须是 0 到 9 的整数值。

### toString() {#tostring}

根据 HIBC LIC 规范将数据转换为字符串格式。

**Returns:** Formatted string.
