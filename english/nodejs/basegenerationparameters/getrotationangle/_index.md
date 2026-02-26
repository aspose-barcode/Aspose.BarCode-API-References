---
title: BaseGenerationParameters.getRotationAngle
linktitle: getRotationAngle
articleTitle: getRotationAngle
second_title: Aspose.BarCode for Node.js via Java
description: "BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270..."
type: docs
weight: 170
url: /nodejs/basegenerationparameters/getrotationangle/
---
## getRotationAngle() {#getrotationangle}

BarCode image rotation angle, measured in degree, e.g. RotationAngle = 0 or RotationAngle = 360 means no rotation. If RotationAngle NOT equal to 90, 180, 270 or 0, it may increase the difficulty for the scanner to read the image. Default value: 0.

```javascript
getRotationAngle()
```

## Examples

```javascript
//This sample shows how to create and save a BarCode image.
let generator = new BarcodeGenerator( EncodeTypes.DATA_MATRIX);
generator.getParameters().setRotationAngle(7);
generator.save("test.png", BarcodeImageFormat.PNG);
```

### See Also

* class [BaseGenerationParameters](../)
* assembly [Aspose.BarCode](../../)

