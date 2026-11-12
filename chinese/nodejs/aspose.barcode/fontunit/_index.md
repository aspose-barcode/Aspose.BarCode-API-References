---
title: "FontUnit"
linktitle: "FontUnit"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "定义文本的特定格式，包括字体、大小和样式属性，其中大小在 Unit 值属性中。"
type: docs
weight: 410
url: /zh/nodejs/aspose.barcode/fontunit/
---

## FontUnit class

定义文本的特定格式，包括字体、大小和样式属性，其中大小在 Unit 值属性中。

```js
new FontUnit()
```

**Example:**

```js
This sample shows how to create and save a BarCode image.

  let generator = new BarcodeGenerator(EncodeTypes.CODE_128);
  generator.getParameters().getCaptionAbove().setText("CAPTION ABOOVE");
  generator.getParameters().getCaptionAbove().setVisible(true);
  generator.getParameters().getCaptionAbove().getFont().setStyle(FontStyle.ITALIC);
  generator.getParameters().getCaptionAbove().getFont().getSize().setPoint(25);
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getFamilyName()](#getfamilyname) | 获取此 Font 的字体名称。 |
| [getSize()](#getsize) | 获取此 FontUnit 的大小（以单位值表示）。 |
| [getStyle()](#getstyle) | 获取此 FontUnit 的样式信息。 |
| [setFamilyName()](#setfamilyname) | 设置此 Font 的字体名称。 |
| [setStyle()](#setstyle) | 设置此 FontUnit 的样式信息。 |

### getFamilyName() {#getfamilyname}

获取此 Font 的字体名称。

### getSize() {#getsize}

获取此 FontUnit 的大小（以单位值表示）。

**Throws:** IllegalArgumentExceptionThe Size parameter value is less than or equal to 0.

### getStyle() {#getstyle}

获取此 FontUnit 的样式信息。

### setFamilyName() {#setfamilyname}

设置此 Font 的字体名称。

### setStyle() {#setstyle}

设置此 FontUnit 的样式信息。
