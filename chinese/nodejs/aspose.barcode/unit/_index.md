---
title: "Unit"
linktitle: "Unit"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "指定不同单位（像素、英寸等）中的尺寸值。"
type: docs
weight: 960
url: /zh/nodejs/aspose.barcode/unit/
---

## Unit class

指定不同单位（像素、英寸等）中的尺寸值。

```js
new Unit()
```

**Example:**

```js
//This sample shows how to create and save a BarCode image.
   let generator = new BarcodeGenerator(EncodeTypes.CODE_128);
   generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
   generator.save("test.png", BarcodeImageFormat.PNG);
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals(obj)](#equals) | 确定此实例和指定对象（该对象也必须是 Unit 对象）是否具有相同的值。 |
| [getDocument()](#getdocument) | 获取文档单位中的尺寸值。 |
| [getInches()](#getinches) | 获取英寸中的尺寸值。 |
| [getMillimeters()](#getmillimeters) | 获取毫米中的尺寸值。 |
| [getPixels()](#getpixels) | 获取像素中的尺寸值。 |
| [getPoint()](#getpoint) | 获取点中的尺寸值。 |
| [setDocument()](#setdocument) | 设置文档单位中的尺寸值。 |
| [setInches()](#setinches) | 设置英寸中的尺寸值。 |
| [setMillimeters()](#setmillimeters) | 设置毫米中的尺寸值。 |
| [setPixels()](#setpixels) | 设置像素中的尺寸值。 |
| [setPoint()](#setpoint) | 设置点中的尺寸值。 |
| [toString()](#tostring) | 返回此 Unit 的可读字符串表示。 |

### equals(obj) {#equals}

确定此实例和指定对象（该对象也必须是 Unit 对象）是否具有相同的值。

| 参数 | 描述 |
| --- | --- |
| obj | 用于与此实例比较的 Unit。 |

**Returns:** true if obj is a Unit and its value is the same as this instance; otherwise, false. If obj is null, the method returns false.

### getDocument() {#getdocument}

获取文档单位中的尺寸值。

### getInches() {#getinches}

获取英寸中的尺寸值。

### getMillimeters() {#getmillimeters}

获取毫米中的尺寸值。

### getPixels() {#getpixels}

获取像素中的尺寸值。

### getPoint() {#getpoint}

获取点中的尺寸值。

### setDocument() {#setdocument}

设置文档单位中的尺寸值。

### setInches() {#setinches}

设置英寸中的尺寸值。

### setMillimeters() {#setmillimeters}

设置毫米中的尺寸值。

### setPixels() {#setpixels}

设置像素中的尺寸值。

### setPoint() {#setpoint}

设置点中的尺寸值。

### toString() {#tostring}

返回此 Unit 的可读字符串表示。

**Returns:** A string that represents this Unit.
