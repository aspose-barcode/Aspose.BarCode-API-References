---
title: "FontUnit"
linktitle: "FontUnit"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stil‑Attribute, wobei die Größe in der Unit‑value‑Eigenschaft angegeben ist."
type: docs
weight: 410
url: /de/nodejs/aspose.barcode/fontunit/
---

## FontUnit class

Definiert ein bestimmtes Format für Text, einschließlich Schriftart, Größe und Stil‑Attribute, wobei die Größe in der Unit‑value‑Eigenschaft angegeben ist.

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

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getFamilyName()](#getfamilyname) | Liefert den Schriftartnamen dieses Fonts. |
| [getSize()](#getsize) | Liefert die Größe dieses FontUnit im Einheit‑Wert. |
| [getStyle()](#getstyle) | Liefert Stilinformationen für dieses FontUnit. |
| [setFamilyName()](#setfamilyname) | Setzt den Schriftartnamen dieses Fonts. |
| [setStyle()](#setstyle) | Setzt Stilinformationen für dieses FontUnit. |

### getFamilyName() {#getfamilyname}

Liefert den Schriftartnamen dieses Fonts.

### getSize() {#getsize}

Liefert die Größe dieses FontUnit im Einheit‑Wert.

**Throws:** IllegalArgumentExceptionThe Size parameter value is less than or equal to 0.

### getStyle() {#getstyle}

Liefert Stilinformationen für dieses FontUnit.

### setFamilyName() {#setfamilyname}

Setzt den Schriftartnamen dieses Fonts.

### setStyle() {#setstyle}

Setzt Stilinformationen für dieses FontUnit.
