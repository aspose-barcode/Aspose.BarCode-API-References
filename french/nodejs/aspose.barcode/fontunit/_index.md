---
title: "FontUnit"
linktitle: "FontUnit"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Définit un format particulier pour le texte, incluant la police, la taille et les attributs de style où la taille se trouve dans la propriété de valeur Unit."
type: docs
weight: 410
url: /fr/nodejs/aspose.barcode/fontunit/
---

## FontUnit class

Définit un format particulier pour le texte, incluant la police, la taille et les attributs de style où la taille se trouve dans la propriété de valeur Unit.

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

## Méthodes

| Nom | Description |
| --- | --- |
| [getFamilyName()](#getfamilyname) | Obtient le nom de la police de ce Font. |
| [getSize()](#getsize) | Obtient la taille de ce FontUnit en valeur d'unité. |
| [getStyle()](#getstyle) | Obtient les informations de style pour ce FontUnit. |
| [setFamilyName()](#setfamilyname) | Définit le nom de la police de ce Font. |
| [setStyle()](#setstyle) | Définit les informations de style pour ce FontUnit. |

### getFamilyName() {#getfamilyname}

Obtient le nom de la police de ce Font.

### getSize() {#getsize}

Obtient la taille de ce FontUnit en valeur d'unité.

**Throws:** IllegalArgumentExceptionThe Size parameter value is less than or equal to 0.

### getStyle() {#getstyle}

Obtient les informations de style pour ce FontUnit.

### setFamilyName() {#setfamilyname}

Définit le nom de la police de ce Font.

### setStyle() {#setstyle}

Définit les informations de style pour ce FontUnit.
