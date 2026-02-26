---
title: DataMatrixExtCodetextBuilder Class
linktitle: DataMatrixExtCodetextBuilder
articleTitle: DataMatrixExtCodetextBuilder
second_title: Aspose.BarCode for Node.js via Java
description: 
type: docs
weight: 770
url: /nodejs/datamatrixextcodetextbuilder/
---
## DataMatrixExtCodetextBuilder class

//Extended codetext mode //create codetext let textBuilder = new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, DataMatrixEncodeMode.BYTES, "World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF_8, "犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C_40, "ABCDE"); //generate codetext let codetext = textBuilder.getExtendedCodetext(); //generate let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null, codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.BMP);

```javascript
public class DataMatrixExtCodetextBuilder : ExtCodetextBuilder
```

## Constructors

| Name | Description |
| --- | --- |
| [DataMatrixExtCodetextBuilder](./datamatrixextcodetextbuilder/#constructor) | Initializes a new instance of the DataMatrixExtCodetextBuilder class. |

## Methods

| Name | Description |
| --- | --- |
| [addCodetextWithEncodeMode](./addcodetextwithencodemode/)(*object, object*) | Adds codetext with defined encode mode to the extended codetext items. |
| [addECICodetext](../extcodetextbuilder/addecicodetext/)(*object, object*) | Adds codetext with Extended Channel Identifier. *(Inherited from ExtCodetextBuilder)* |
| [addECICodetextWithEncodeMode](./addecicodetextwithencodemode/)(*object, object, object*) | Adds codetext with Extended Channel Identifier with defined encode mode. |
| [addPlainCodetext](../extcodetextbuilder/addplaincodetext/)(*object*) | Adds plain codetext to the extended codetext items. *(Inherited from ExtCodetextBuilder)* |
| [clear](../extcodetextbuilder/clear/) | Clears extended codetext items. *(Inherited from ExtCodetextBuilder)* |
| [construct](./construct/)(*object*) |  |
| [getExtendedCodetext](./getextendedcodetext/) | Generates Extended codetext from the extended codetext list. |
| [init](./init/) |  |

## Fields

| Name | Description |
| --- | --- |
| [JAVA_CLASS_NAME](./java_class_name/) |  |

### See Also

* assembly [Aspose.BarCode](../)

