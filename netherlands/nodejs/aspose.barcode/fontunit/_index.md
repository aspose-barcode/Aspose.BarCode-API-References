---
title: "FontUnit"
linktitle: "FontUnit"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Definieert een specifiek formaat voor tekst, inclusief lettertype, grootte en stijlkenmerken waarbij grootte in de eigenschap Unit value staat."
type: docs
weight: 410
url: /nl/nodejs/aspose.barcode/fontunit/
---

## FontUnit class

Definieert een specifiek formaat voor tekst, inclusief lettertype, grootte en stijlkenmerken waarbij grootte in de eigenschap Unit value staat.

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

| Naam | Beschrijving |
| --- | --- |
| [getFamilyName()](#getfamilyname) | Haalt de naam van dit Lettertype op. |
| [getSize()](#getsize) | Haalt de grootte van deze FontUnit op in eenheidswaarde. |
| [getStyle()](#getstyle) | Haalt stijl-informatie op voor deze FontUnit. |
| [setFamilyName()](#setfamilyname) | Stelt de naam van dit Lettertype in. |
| [setStyle()](#setstyle) | Stelt stijl-informatie in voor deze FontUnit. |

### getFamilyName() {#getfamilyname}

Haalt de naam van dit Lettertype op.

### getSize() {#getsize}

Haalt de grootte van deze FontUnit op in eenheidswaarde.

**Throws:** IllegalArgumentExceptionThe Size parameter value is less than or equal to 0.

### getStyle() {#getstyle}

Haalt stijl-informatie op voor deze FontUnit.

### setFamilyName() {#setfamilyname}

Stelt de naam van dit Lettertype in.

### setStyle() {#setstyle}

Stelt stijl-informatie in voor deze FontUnit.
