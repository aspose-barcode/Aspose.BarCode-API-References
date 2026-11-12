---
title: "FontUnit"
linktitle: "FontUnit"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Definisce un formato particolare per il testo, includendo il tipo di carattere, la dimensione e gli attributi di stile dove la dimensione è nella proprietà Unit value."
type: docs
weight: 410
url: /it/nodejs/aspose.barcode/fontunit/
---

## FontUnit class

Definisce un formato particolare per il testo, includendo il tipo di carattere, la dimensione e gli attributi di stile dove la dimensione è nella proprietà Unit value.

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

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getFamilyName()](#getfamilyname) | Ottiene il nome del tipo di carattere di questo Font. |
| [getSize()](#getsize) | Ottiene la dimensione di questo FontUnit nel valore Unit. |
| [getStyle()](#getstyle) | Ottiene le informazioni di stile per questo FontUnit. |
| [setFamilyName()](#setfamilyname) | Imposta il nome del tipo di carattere di questo Font. |
| [setStyle()](#setstyle) | Imposta le informazioni di stile per questo FontUnit. |

### getFamilyName() {#getfamilyname}

Ottiene il nome del tipo di carattere di questo Font.

### getSize() {#getsize}

Ottiene la dimensione di questo FontUnit nel valore Unit.

**Throws:** IllegalArgumentExceptionThe Size parameter value is less than or equal to 0.

### getStyle() {#getstyle}

Ottiene le informazioni di stile per questo FontUnit.

### setFamilyName() {#setfamilyname}

Imposta il nome del tipo di carattere di questo Font.

### setStyle() {#setstyle}

Imposta le informazioni di stile per questo FontUnit.
