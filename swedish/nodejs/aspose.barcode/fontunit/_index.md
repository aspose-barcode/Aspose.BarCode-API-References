---
title: "FontUnit"
linktitle: "FontUnit"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Definierar ett specifikt format för text, inklusive teckensnitt, storlek och stilattribut där storleken är i enhetsvärdesegenskapen."
type: docs
weight: 410
url: /sv/nodejs/aspose.barcode/fontunit/
---

## FontUnit class

Definierar ett specifikt format för text, inklusive teckensnitt, storlek och stilattribut där storleken är i enhetsvärdesegenskapen.

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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getFamilyName()](#getfamilyname) | Hämtar teckensnittets namn för detta Font. |
| [getSize()](#getsize) | Hämtar storleken för detta FontUnit i enhetsvärde. |
| [getStyle()](#getstyle) | Hämtar stilinformation för detta FontUnit. |
| [setFamilyName()](#setfamilyname) | Ställer in teckensnittets namn för detta Font. |
| [setStyle()](#setstyle) | Ställer in stilinformation för detta FontUnit. |

### getFamilyName() {#getfamilyname}

Hämtar teckensnittets namn för detta Font.

### getSize() {#getsize}

Hämtar storleken för detta FontUnit i enhetsvärde.

**Throws:** IllegalArgumentExceptionThe Size parameter value is less than or equal to 0.

### getStyle() {#getstyle}

Hämtar stilinformation för detta FontUnit.

### setFamilyName() {#setfamilyname}

Ställer in teckensnittets namn för detta Font.

### setStyle() {#setstyle}

Ställer in stilinformation för detta FontUnit.
