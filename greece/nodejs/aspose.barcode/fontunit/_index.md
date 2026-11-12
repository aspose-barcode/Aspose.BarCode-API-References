---
title: "FontUnit"
linktitle: "FontUnit"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Ορίζει μια συγκεκριμένη μορφή για κείμενο, συμπεριλαμβανομένης της γραμματοσειράς, του μεγέθους και των χαρακτηριστικών στυλ, όπου το μέγεθος βρίσκεται στην ιδιότητα Unit value."
type: docs
weight: 410
url: /el/nodejs/aspose.barcode/fontunit/
---

## FontUnit class

Ορίζει μια συγκεκριμένη μορφή για κείμενο, συμπεριλαμβανομένης της γραμματοσειράς, του μεγέθους και των χαρακτηριστικών στυλ, όπου το μέγεθος βρίσκεται στην ιδιότητα Unit value.

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

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getFamilyName()](#getfamilyname) | Αποκτά το όνομα γραμματοσειράς (face name) αυτού του Font. |
| [getSize()](#getsize) | Αποκτά το μέγεθος αυτού του FontUnit σε τιμή Unit. |
| [getStyle()](#getstyle) | Αποκτά πληροφορίες στυλ για αυτό το FontUnit. |
| [setFamilyName()](#setfamilyname) | Ορίζει το όνομα γραμματοσειράς (face name) αυτού του Font. |
| [setStyle()](#setstyle) | Ορίζει πληροφορίες στυλ για αυτό το FontUnit. |

### getFamilyName() {#getfamilyname}

Αποκτά το όνομα γραμματοσειράς (face name) αυτού του Font.

### getSize() {#getsize}

Αποκτά το μέγεθος αυτού του FontUnit σε τιμή Unit.

**Throws:** IllegalArgumentExceptionThe Size parameter value is less than or equal to 0.

### getStyle() {#getstyle}

Αποκτά πληροφορίες στυλ για αυτό το FontUnit.

### setFamilyName() {#setfamilyname}

Ορίζει το όνομα γραμματοσειράς (face name) αυτού του Font.

### setStyle() {#setstyle}

Ορίζει πληροφορίες στυλ για αυτό το FontUnit.
