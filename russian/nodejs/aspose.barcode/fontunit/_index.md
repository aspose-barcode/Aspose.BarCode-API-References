---
title: "FontUnit"
linktitle: "FontUnit"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Определяет определённый формат текста, включая шрифт, размер и атрибуты стиля, где размер задаётся в свойстве Unit value."
type: docs
weight: 410
url: /ru/nodejs/aspose.barcode/fontunit/
---

## FontUnit class

Определяет определённый формат текста, включая шрифт, размер и атрибуты стиля, где размер задаётся в свойстве Unit value.

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

## Методы

| Имя | Описание |
| --- | --- |
| [getFamilyName()](#getfamilyname) | Получает название гарнитуры этого Font. |
| [getSize()](#getsize) | Получает размер этого FontUnit в единицах Unit. |
| [getStyle()](#getstyle) | Получает информацию о стиле для этого FontUnit. |
| [setFamilyName()](#setfamilyname) | Устанавливает название гарнитуры этого Font. |
| [setStyle()](#setstyle) | Устанавливает информацию о стиле для этого FontUnit. |

### getFamilyName() {#getfamilyname}

Получает название гарнитуры этого Font.

### getSize() {#getsize}

Получает размер этого FontUnit в единицах Unit.

**Throws:** IllegalArgumentExceptionThe Size parameter value is less than or equal to 0.

### getStyle() {#getstyle}

Получает информацию о стиле для этого FontUnit.

### setFamilyName() {#setfamilyname}

Устанавливает название гарнитуры этого Font.

### setStyle() {#setstyle}

Устанавливает информацию о стиле для этого FontUnit.
