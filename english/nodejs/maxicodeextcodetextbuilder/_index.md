---
title: MaxiCodeExtCodetextBuilder Class
linktitle: MaxiCodeExtCodetextBuilder
articleTitle: MaxiCodeExtCodetextBuilder
second_title: Aspose.BarCode for Node.js via Java
description: "Extended codetext generator for MaxiCode barcodes for ExtendedCodetext Mode of MaxiCodeEncodeMode Use TwoDDisplayText property of BarcodeGenerator to set vis..."
type: docs
weight: 730
url: /nodejs/maxicodeextcodetextbuilder/
---
## MaxiCodeExtCodetextBuilder class

Extended codetext generator for MaxiCode barcodes for ExtendedCodetext Mode of MaxiCodeEncodeMode Use TwoDDisplayText property of BarcodeGenerator to set visible text to removing managing characters. This sample shows how to use MaxiCodeExtCodetextBuilder in Extended Mode.

```javascript
public class MaxiCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Constructors

| Name | Description |
| --- | --- |
| [MaxiCodeExtCodetextBuilder](./maxicodeextcodetextbuilder/#constructor) | Initializes a new instance of the MaxiCodeExtCodetextBuilder class. |

## Methods

| Name | Description |
| --- | --- |
| [addECICodetext](../extcodetextbuilder/addecicodetext/)(*object, object*) | Adds codetext with Extended Channel Identifier. *(Inherited from ExtCodetextBuilder)* |
| [addPlainCodetext](../extcodetextbuilder/addplaincodetext/)(*object*) | Adds plain codetext to the extended codetext items. *(Inherited from ExtCodetextBuilder)* |
| [clear](../extcodetextbuilder/clear/) | Clears extended codetext items. *(Inherited from ExtCodetextBuilder)* |
| [getExtendedCodetext](./getextendedcodetext/) | Generates Extended codetext from the extended codetext list. |
| [init](./init/) |  |

## Fields

| Name | Description |
| --- | --- |
| [JAVA_CLASS_NAME](./java_class_name/) |  |

## Examples

```javascript
//create codetext
let textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.addPlainCodetext("Plain text");
//generate codetext
let codetext = textBuilder.getExtendedCodetext();
//generate
let generator = new BarcodeGenerator(EncodeTypes.MAXI_CODE, codetext);
generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
generator.save("test.bmp", BarcodeImageFormat.BMP);
```

### See Also

* assembly [Aspose.BarCode](../)

