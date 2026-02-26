---
title: BarcodeParameters.setGS1CompositeBar
linktitle: setGS1CompositeBar
articleTitle: setGS1CompositeBar
second_title: Aspose.BarCode for Node.js via Java
description: "GS1 Composite Bar parameters."
type: docs
weight: 530
url: /nodejs/barcodeparameters/setgs1compositebar/
---
## setGS1CompositeBar(object) {#setgs1compositebar}

GS1 Composite Bar parameters.

```javascript
setGS1CompositeBar(value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| value | object |  |

## Examples

```javascript
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);
generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);
// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);
// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);
// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);
generator.save("test.png", BarcodeImageFormat.PNG);
```

### See Also

* class [BarcodeParameters](../)
* assembly [Aspose.BarCode](../../)

