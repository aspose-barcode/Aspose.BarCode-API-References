---
title: "FontUnit"
linktitle: "FontUnit"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Defines a particular format for text, including font face, size, and style attributes where size in Unit value property."
type: docs
weight: 410
url: /nodejs/aspose.barcode/fontunit/
---

## FontUnit class

Defines a particular format for text, including font face, size, and style attributes where size in Unit value property.

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

## Methods

| Name | Description |
| --- | --- |
| [getFamilyName()](#getfamilyname) | Gets the face name of this Font. |
| [getSize()](#getsize) | Gets size of this FontUnit in Unit value. |
| [getStyle()](#getstyle) | Gets style information for this FontUnit. |
| [setFamilyName()](#setfamilyname) | Sets the face name of this Font. |
| [setStyle()](#setstyle) | Sets style information for this FontUnit. |

### getFamilyName() {#getfamilyname}

Gets the face name of this Font.

### getSize() {#getsize}

Gets size of this FontUnit in Unit value.

**Throws:** IllegalArgumentExceptionThe Size parameter value is less than or equal to 0.

### getStyle() {#getstyle}

Gets style information for this FontUnit.

### setFamilyName() {#setfamilyname}

Sets the face name of this Font.

### setStyle() {#setstyle}

Sets style information for this FontUnit.
