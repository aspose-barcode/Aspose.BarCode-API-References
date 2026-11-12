---
title: "SecondaryAndAdditionalData"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于存储 HIBC LIC 次要和附加数据的类。"
type: docs
weight: 880
url: /zh/nodejs/aspose.barcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

用于存储 HIBC LIC 次要和附加数据的类。

```js
new SecondaryAndAdditionalData()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals(obj)](#equals) | 返回一个值，指示此实例是否等于指定的 `SecondaryAndAdditionalData` 值。 |
| [getDateOfManufacture()](#getdateofmanufacture) | 标识生产日期。生产日期可以设置为 DateTime.MinValue 以不使用此字段。Defa |
| [getExpiryDate()](#getexpirydate) | 标识有效期。若 ExpiryDateFormat 未设置为 None，则会使用此字段。 |
| [getExpiryDateFormat()](#getexpirydateformat) | 标识有效期格式。 |
| [getLotNumber()](#getlotnumber) | 标识批号或批次号。批号/批次号必须是最长 18 个字符的字母数字字符串。 . |
| [getQuantity()](#getquantity) | 标识数量，必须是 0 到 500 的整数值。数量可以设置为 -1 以不使用此字段。Defa |
| [getSerialNumber()](#getserialnumber) | 标识序列号。序列号必须是最长 18 个字符的字母数字字符串。 |
| [hashCode()](#hashcode) | 返回此实例的哈希码。 |
| [parseFromString(secondaryDataCodetext)](#parsefromstring) | 根据 HIBC LIC 规范，从字符串格式实例化次要和附加补充数据。 |
| [setDateOfManufacture()](#setdateofmanufacture) | 标识生产日期。生产日期可以设置为 DateTime.MinValue 以不使用此字段。Defa |
| [setExpiryDate()](#setexpirydate) | 标识有效期。若 ExpiryDateFormat 未设置为 None，则会使用此字段。 |
| [setExpiryDateFormat()](#setexpirydateformat) | 标识有效期格式。 |
| [setLotNumber()](#setlotnumber) | 标识批号或批次号。批号/批次号必须是最长 18 个字符的字母数字字符串。 . |
| [setQuantity()](#setquantity) | 标识数量，必须是 0 到 500 的整数值。数量可以设置为 -1 以不使用此字段。Defa |
| [setSerialNumber()](#setserialnumber) | 标识序列号。序列号必须是最长 18 个字符的字母数字字符串。 |
| [toString()](#tostring) | 根据 HIBC LIC 规范将数据转换为字符串格式。 |

### equals(obj) {#equals}

返回一个值，指示此实例是否等于指定的 `SecondaryAndAdditionalData` 值。

| 参数 | 描述 |
| --- | --- |
| obj | 用于与此实例比较的 `SecondaryAndAdditionalData` 值。 |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDateOfManufacture() {#getdateofmanufacture}

标识生产日期。生产日期可以设置为 DateTime.MinValue 以不使用此字段。默认值：DateTime.MinValue

### getExpiryDate() {#getexpirydate}

标识有效期。若 ExpiryDateFormat 未设置为 None，则会使用此字段。

### getExpiryDateFormat() {#getexpirydateformat}

标识有效期格式。

### getLotNumber() {#getlotnumber}

标识批号或批次号。批号/批次号必须是最长 18 个字符的字母数字字符串。 .

### getQuantity() {#getquantity}

标识数量，必须是 0 到 500 的整数值。数量可以设置为 -1 以不使用此字段。默认值：-1

### getSerialNumber() {#getserialnumber}

标识序列号。序列号必须是最长 18 个字符的字母数字字符串。

### hashCode() {#hashcode}

返回此实例的哈希码。

**Returns:** A 32-bit signed integer hash code.

### parseFromString(secondaryDataCodetext) {#parsefromstring}

根据 HIBC LIC 规范，从字符串格式实例化次要和附加补充数据。

| 参数 | 描述 |
| --- | --- |
| secondaryDataCodetext | 格式化字符串。 |

### setDateOfManufacture() {#setdateofmanufacture}

标识生产日期。生产日期可以设置为 DateTime.MinValue 以不使用此字段。默认值：DateTime.MinValue

### setExpiryDate() {#setexpirydate}

标识有效期。若 ExpiryDateFormat 未设置为 None，则会使用此字段。

### setExpiryDateFormat() {#setexpirydateformat}

标识有效期格式。

### setLotNumber() {#setlotnumber}

标识批号或批次号。批号/批次号必须是最长 18 个字符的字母数字字符串。 .

### setQuantity() {#setquantity}

标识数量，必须是 0 到 500 的整数值。数量可以设置为 -1 以不使用此字段。默认值：-1

### setSerialNumber() {#setserialnumber}

标识序列号。序列号必须是最长 18 个字符的字母数字字符串。

### toString() {#tostring}

根据 HIBC LIC 规范将数据转换为字符串格式。

**Returns:** Formatted string.
