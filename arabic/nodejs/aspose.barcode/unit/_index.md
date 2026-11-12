---
title: "Unit"
linktitle: "Unit"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "يحدد قيمة الحجم بوحدات مختلفة (بكسل، بوصات، إلخ)."
type: docs
weight: 960
url: /ar/nodejs/aspose.barcode/unit/
---

## Unit class

يحدد قيمة الحجم بوحدات مختلفة (بكسل، بوصات، إلخ).

```js
new Unit()
```

**Example:**

```js
//This sample shows how to create and save a BarCode image.
   let generator = new BarcodeGenerator(EncodeTypes.CODE_128);
   generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
   generator.save("test.png", BarcodeImageFormat.PNG);
```

## طرق

| اسم | الوصف |
| --- | --- |
| [equals(obj)](#equals) | يحدد ما إذا كانت هذه المثيلة وكائن محدد، والذي يجب أن يكون أيضًا كائن Unit، لهما نفس القيمة. |
| [getDocument()](#getdocument) | يحصل على قيمة الحجم بوحدات المستند. |
| [getInches()](#getinches) | يحصل على قيمة الحجم بالبوصة. |
| [getMillimeters()](#getmillimeters) | يحصل على قيمة الحجم بالمليمتر. |
| [getPixels()](#getpixels) | يحصل على قيمة الحجم بالبكسل. |
| [getPoint()](#getpoint) | يحصل على قيمة الحجم بالنقطة. |
| [setDocument()](#setdocument) | يضبط قيمة الحجم بوحدات المستند. |
| [setInches()](#setinches) | يضبط قيمة الحجم بالبوصة. |
| [setMillimeters()](#setmillimeters) | يضبط قيمة الحجم بالمليمتر. |
| [setPixels()](#setpixels) | يضبط قيمة الحجم بالبكسل. |
| [setPoint()](#setpoint) | يضبط قيمة الحجم بالنقطة. |
| [toString()](#tostring) | يعيد تمثيلًا نصيًا قابلًا للقراءة لهذا Unit. |

### equals(obj) {#equals}

يحدد ما إذا كانت هذه المثيلة وكائن محدد، والذي يجب أن يكون أيضًا كائن Unit، لهما نفس القيمة.

| معامل | الوصف |
| --- | --- |
| obj | الوحدة للمقارنة مع هذه المثيلة. |

**Returns:** true if obj is a Unit and its value is the same as this instance; otherwise, false. If obj is null, the method returns false.

### getDocument() {#getdocument}

يحصل على قيمة الحجم بوحدات المستند.

### getInches() {#getinches}

يحصل على قيمة الحجم بالبوصة.

### getMillimeters() {#getmillimeters}

يحصل على قيمة الحجم بالمليمتر.

### getPixels() {#getpixels}

يحصل على قيمة الحجم بالبكسل.

### getPoint() {#getpoint}

يحصل على قيمة الحجم بالنقطة.

### setDocument() {#setdocument}

يضبط قيمة الحجم بوحدات المستند.

### setInches() {#setinches}

يضبط قيمة الحجم بالبوصة.

### setMillimeters() {#setmillimeters}

يضبط قيمة الحجم بالمليمتر.

### setPixels() {#setpixels}

يضبط قيمة الحجم بالبكسل.

### setPoint() {#setpoint}

يضبط قيمة الحجم بالنقطة.

### toString() {#tostring}

يعيد تمثيلًا نصيًا قابلًا للقراءة لهذا Unit.

**Returns:** A string that represents this Unit.
