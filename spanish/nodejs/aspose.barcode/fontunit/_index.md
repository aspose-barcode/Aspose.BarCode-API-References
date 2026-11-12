---
title: "FontUnit"
linktitle: "FontUnit"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Define un formato particular para el texto, incluyendo la familia de fuentes, el tamaño y los atributos de estilo donde el tamaño está en la propiedad Unit value."
type: docs
weight: 410
url: /es/nodejs/aspose.barcode/fontunit/
---

## FontUnit class

Define un formato particular para el texto, incluyendo la familia de fuentes, el tamaño y los atributos de estilo donde el tamaño está en la propiedad Unit value.

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

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getFamilyName()](#getfamilyname) | Obtiene el nombre de la familia tipográfica de este Font. |
| [getSize()](#getsize) | Obtiene el tamaño de este FontUnit en unidades. |
| [getStyle()](#getstyle) | Obtiene la información de estilo de este FontUnit. |
| [setFamilyName()](#setfamilyname) | Establece el nombre de la familia tipográfica de este Font. |
| [setStyle()](#setstyle) | Establece la información de estilo para este FontUnit. |

### getFamilyName() {#getfamilyname}

Obtiene el nombre de la familia tipográfica de este Font.

### getSize() {#getsize}

Obtiene el tamaño de este FontUnit en unidades.

**Throws:** IllegalArgumentExceptionThe Size parameter value is less than or equal to 0.

### getStyle() {#getstyle}

Obtiene la información de estilo de este FontUnit.

### setFamilyName() {#setfamilyname}

Establece el nombre de la familia tipográfica de este Font.

### setStyle() {#setstyle}

Establece la información de estilo para este FontUnit.
