---
title: "FontUnit"
linktitle: "FontUnit"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "पाठ के लिए एक विशिष्ट फ़ॉर्मेट को परिभाषित करता है, जिसमें फ़ॉन्ट फ़ेस, आकार, और शैली गुण शामिल हैं जहाँ आकार यूनिट वैल्यू प्रॉपर्टी में होता है।"
type: docs
weight: 410
url: /hi/nodejs/aspose.barcode/fontunit/
---

## FontUnit class

पाठ के लिए एक विशिष्ट फ़ॉर्मेट को परिभाषित करता है, जिसमें फ़ॉन्ट फ़ेस, आकार, और शैली गुण शामिल हैं जहाँ आकार यूनिट वैल्यू प्रॉपर्टी में होता है।

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

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getFamilyName()](#getfamilyname) | इस फ़ॉन्ट का फ़ेस नाम प्राप्त करता है। |
| [getSize()](#getsize) | इस FontUnit का आकार यूनिट मान में प्राप्त करता है। |
| [getStyle()](#getstyle) | इस FontUnit के लिए शैली जानकारी प्राप्त करता है। |
| [setFamilyName()](#setfamilyname) | इस फ़ॉन्ट का फ़ेस नाम सेट करता है। |
| [setStyle()](#setstyle) | इस FontUnit के लिए शैली जानकारी सेट करता है। |

### getFamilyName() {#getfamilyname}

इस फ़ॉन्ट का फ़ेस नाम प्राप्त करता है।

### getSize() {#getsize}

इस FontUnit का आकार यूनिट मान में प्राप्त करता है।

**Throws:** IllegalArgumentExceptionThe Size parameter value is less than or equal to 0.

### getStyle() {#getstyle}

इस FontUnit के लिए शैली जानकारी प्राप्त करता है।

### setFamilyName() {#setfamilyname}

इस फ़ॉन्ट का फ़ेस नाम सेट करता है।

### setStyle() {#setstyle}

इस FontUnit के लिए शैली जानकारी सेट करता है।
