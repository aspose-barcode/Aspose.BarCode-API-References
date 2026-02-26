---
title: AztecExtCodetextBuilder Class
linktitle: AztecExtCodetextBuilder
articleTitle: AztecExtCodetextBuilder
second_title: Aspose.BarCode for Node.js via Java
description: This sample shows how to use AztecExtCodetextBuilder in Extended Mode.
type: docs
weight: 1050
url: /nodejs/aztecextcodetextbuilder/
---
## AztecExtCodetextBuilder class

This sample shows how to use AztecExtCodetextBuilder in Extended Mode.

```javascript
public class AztecExtCodetextBuilder : ExtCodetextBuilder
```

## Constructors

| Name | Description |
| --- | --- |
| [AztecExtCodetextBuilder](./aztecextcodetextbuilder/#constructor) | Initializes a new instance of the AztecExtCodetextBuilder class. |

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
let textBuilder = new AztecExtCodetextBuilder();
textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.addPlainCodetext("Plain text");
//generate codetext
let codetext = textBuilder.getExtendedCodetext();
//generate
let generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
generator.getParameters().getBarcode().getCodeTextParameters().setwoDDisplayText("My Text");
generator.save("test.bmp", BarcodeImageFormat.BMP);
```

### See Also

* assembly [Aspose.BarCode](../)

