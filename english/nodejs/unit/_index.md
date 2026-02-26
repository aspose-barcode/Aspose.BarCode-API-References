---
title: Unit Class
linktitle: Unit
articleTitle: Unit
second_title: Aspose.BarCode for Node.js via Java
description: Specifies the size value in different units (Pixel, Inches, etc.).
type: docs
weight: 490
url: /nodejs/unit/
---
## Unit class

Specifies the size value in different units (Pixel, Inches, etc.).

```javascript
public class Unit : joint.BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [Unit](./unit/#constructor)(*object*) | Initializes a new instance of the Unit class. |

## Methods

| Name | Description |
| --- | --- |
| [equals](./equals/)(*object*) | Determines whether this instance and a specified object, which must also be a Unit object, have the same value. |
| [getDocument](./getdocument/) | Gets size value in document units. |
| [getInches](./getinches/) | Gets size value in inches. |
| [getMillimeters](./getmillimeters/) | Gets size value in millimeters. |
| [getPixels](./getpixels/) | Gets size value in pixels. |
| [getPoint](./getpoint/) | Gets size value in point. |
| [init](./init/) |  |
| [initUnit](./initunit/)(*object*) |  |
| [setDocument](./setdocument/)(*object*) | Sets size value in document units. |
| [setInches](./setinches/)(*object*) | Sets size value in inches. |
| [setMillimeters](./setmillimeters/)(*object*) | Sets size value in millimeters. |
| [setPixels](./setpixels/)(*object*) | Sets size value in pixels. |
| [setPoint](./setpoint/)(*object*) | Sets size value in point. |
| [toString](./tostring/) | Returns a human-readable string representation of this Unit. |

## Examples

```javascript
//This sample shows how to create and save a BarCode image.
let generator = new BarcodeGenerator(EncodeTypes.CODE_128);
generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
generator.save("test.png", BarcodeImageFormat.PNG);
```

### See Also

* assembly [Aspose.BarCode](../)

