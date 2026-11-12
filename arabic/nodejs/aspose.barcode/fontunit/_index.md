---
title: "FontUnit"
linktitle: "FontUnit"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "يحدد تنسيقًا معينًا للنص، بما في ذلك نوع الخط، الحجم، وسمات النمط حيث يكون الحجم في خاصية قيمة الوحدة."
type: docs
weight: 410
url: /ar/nodejs/aspose.barcode/fontunit/
---

## FontUnit class

يحدد تنسيقًا معينًا للنص، بما في ذلك نوع الخط، الحجم، وسمات النمط حيث يكون الحجم في خاصية قيمة الوحدة.

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

## طرق

| اسم | الوصف |
| --- | --- |
| [getFamilyName()](#getfamilyname) | يحصل على اسم الوجه لهذا الخط. |
| [getSize()](#getsize) | يحصل على حجم هذا FontUnit بوحدة القيمة. |
| [getStyle()](#getstyle) | يحصل على معلومات النمط لهذا FontUnit. |
| [setFamilyName()](#setfamilyname) | يضبط اسم الوجه لهذا الخط. |
| [setStyle()](#setstyle) | يضبط معلومات النمط لهذا FontUnit. |

### getFamilyName() {#getfamilyname}

يحصل على اسم الوجه لهذا الخط.

### getSize() {#getsize}

يحصل على حجم هذا FontUnit بوحدة القيمة.

**Throws:** IllegalArgumentExceptionThe Size parameter value is less than or equal to 0.

### getStyle() {#getstyle}

يحصل على معلومات النمط لهذا FontUnit.

### setFamilyName() {#setfamilyname}

يضبط اسم الوجه لهذا الخط.

### setStyle() {#setstyle}

يضبط معلومات النمط لهذا FontUnit.
