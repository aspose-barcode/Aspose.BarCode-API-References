---
title: "ITFParameters"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "ITF 参数。"
type: docs
weight: 540
url: /zh/nodejs/aspose.barcode/itfparameters/
---

## ITFParameters class

ITF 参数。

```js
new ITFParameters()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getBorderThickness()](#getborderthickness) | 获取 ITF 边框（承载条）的厚度，单位值。默认值：12pt。 |
| [getBorderType()](#getbordertype) | ITF 条码的边框类型。默认值：ITF14BorderType.Bar。 |
| [getItfBorderThickness()](#getitfborderthickness) ~~(deprecated)~~ | 获取 ITF 边框（承载条）的厚度，单位值。默认值：12pt。 |
| [getItfBorderType()](#getitfbordertype) ~~(deprecated)~~ | ITF 条码的边框类型。默认值：ITF14BorderType.BAR。 |
| [getQuietZoneCoef()](#getquietzonecoef) | 在 xDimension 中安静区的大小。默认值：10，意味着如果 xDimension = 2px，则安静区将为 20px。 |
| [setBorderThickness(value)](#setborderthickness) | 设置 ITF 边框（承载条）的厚度，单位值。默认值：12pt。 |
| [setBorderType()](#setbordertype) | ITF 条码的边框类型。默认值：ITF14BorderType.Bar。 |
| [setItfBorderThickness()](#setitfborderthickness) ~~(deprecated)~~ | 设置 ITF 边框（承载条）的厚度，单位值。默认值：12pt。 |
| [setItfBorderType()](#setitfbordertype) ~~(deprecated)~~ | ITF 条码的边框类型。默认值：ITF14BorderType.BAR。 |
| [setQuietZoneCoef()](#setquietzonecoef) | 在 xDimension 中安静区的大小。默认值：10，意味着如果 xDimension = 2px，则安静区将为 20px。 |
| [toString()](#tostring) | 返回此 ITFParameters 的可读字符串表示。 |

### getBorderThickness() {#getborderthickness}

获取 ITF 边框（承载条）的厚度，单位值。默认值：12pt。

**Returns:** an ITF border (bearer bar) thickness in Unit value.

### getBorderType() {#getbordertype}

ITF 条码的边框类型。默认值：ITF14BorderType.Bar。

### getItfBorderThickness() {#getitfborderthickness}

> **Deprecated.** See method description for replacement.

获取 ITF 边框（承载条）的厚度，单位值。默认值：12pt。

### getItfBorderType() {#getitfbordertype}

> **Deprecated.** See method description for replacement.

ITF 条码的边框类型。默认值：ITF14BorderType.BAR。

### getQuietZoneCoef() {#getquietzonecoef}

在 xDimension 中安静区的大小。默认值：10，意味着如果 xDimension = 2px，则安静区将为 20px。

**Throws:** IllegalArgumentException
QuietZoneCoef 参数值小于 10。

### setBorderThickness(value) {#setborderthickness}

设置 ITF 边框（承载条）的厚度，单位值。默认值：12pt。

| 参数 | 描述 |
| --- | --- |
| 值 | ITF 边框（承载条）的厚度，单位值。 |

### setBorderType() {#setbordertype}

ITF 条码的边框类型。默认值：ITF14BorderType.Bar。

### setItfBorderThickness() {#setitfborderthickness}

> **Deprecated.** See method description for replacement.

设置 ITF 边框（承载条）的厚度，单位值。默认值：12pt。

### setItfBorderType() {#setitfbordertype}

> **Deprecated.** See method description for replacement.

ITF 条码的边框类型。默认值：ITF14BorderType.BAR。

### setQuietZoneCoef() {#setquietzonecoef}

在 xDimension 中安静区的大小。默认值：10，意味着如果 xDimension = 2px，则安静区将为 20px。

**Throws:** IllegalArgumentException
QuietZoneCoef 参数值小于 10。

### toString() {#tostring}

返回此 ITFParameters 的可读字符串表示。

**Returns:** A string that represents this ITFParameters.
