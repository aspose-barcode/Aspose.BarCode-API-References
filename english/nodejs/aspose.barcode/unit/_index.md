---
title: "Unit Class"
linktitle: "Unit"
articleTitle: "Unit"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Specifies the size value in different units (Pixel, Inches, etc.)."
type: docs
weight: 960
url: /nodejs/aspose.barcode/unit/
---

## Unit class

Specifies the size value in different units (Pixel, Inches, etc.).

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

## Methods

| Name | Description |
| --- | --- |
| [equals(obj)](./equals/) | Determines whether this instance and a specified object, which must also be a Unit object, have the same value. |
| [getDocument()](./getdocument/) | Gets size value in document units. |
| [getInches()](./getinches/) | Gets size value in inches. |
| [getMillimeters()](./getmillimeters/) | Gets size value in millimeters. |
| [getPixels()](./getpixels/) | Gets size value in pixels. |
| [getPoint()](./getpoint/) | Gets size value in point. |
| [setDocument()](./setdocument/) | Sets size value in document units. |
| [setInches()](./setinches/) | Sets size value in inches. |
| [setMillimeters()](./setmillimeters/) | Sets size value in millimeters. |
| [setPixels()](./setpixels/) | Sets size value in pixels. |
| [setPoint()](./setpoint/) | Sets size value in point. |
| [toString()](./tostring/) | Returns a human-readable string representation of this Unit. |
