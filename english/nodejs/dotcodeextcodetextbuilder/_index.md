---
title: DotCodeExtCodetextBuilder Class
linktitle: DotCodeExtCodetextBuilder
articleTitle: DotCodeExtCodetextBuilder
second_title: Aspose.BarCode for Node.js via Java
description: "Extended codetext generator for 2D DotCode barcodes for ExtendedCodetext Mode of DotCodeEncodeMode."
type: docs
weight: 740
url: /nodejs/dotcodeextcodetextbuilder/
---
## DotCodeExtCodetextBuilder class

Extended codetext generator for 2D DotCode barcodes for ExtendedCodetext Mode of DotCodeEncodeMode

```javascript
public class DotCodeExtCodetextBuilder : ExtCodetextBuilder
```

## Constructors

| Name | Description |
| --- | --- |
| [DotCodeExtCodetextBuilder](./dotcodeextcodetextbuilder/#constructor) | Initializes a new instance of the DotCodeExtCodetextBuilder class. |

## Methods

| Name | Description |
| --- | --- |
| [addECICodetext](../extcodetextbuilder/addecicodetext/)(*object, object*) | Adds codetext with Extended Channel Identifier. *(Inherited from ExtCodetextBuilder)* |
| [addFNC1FormatIdentifier](./addfnc1formatidentifier/) | Adds FNC1 format identifier to the extended codetext items. |
| [addFNC3ReaderInitialization](./addfnc3readerinitialization/) | Adds FNC3 reader initialization to the extended codetext items. |
| [addFNC3SymbolSeparator](./addfnc3symbolseparator/) | Adds FNC3 symbol separator to the extended codetext items. |
| [addPlainCodetext](../extcodetextbuilder/addplaincodetext/)(*object*) | Adds plain codetext to the extended codetext items. *(Inherited from ExtCodetextBuilder)* |
| [addStructuredAppendMode](./addstructuredappendmode/)(*object, object*) | Adds structured append mode to the extended codetext items. |
| [clear](../extcodetextbuilder/clear/) | Clears extended codetext items. *(Inherited from ExtCodetextBuilder)* |
| [getExtendedCodetext](./getextendedcodetext/) | Generates Extended codetext from the extended codetext list. |
| [init](./init/) |  |

## Fields

| Name | Description |
| --- | --- |
| [JAVA_CLASS_NAME](./java_class_name/) |  |

## Examples

```javascript
//Extended codetext mode
//create codetext
let textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.addFNC1FormatIdentifier();
textBuilder.addECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.addPlainCodetext("Plain text");
textBuilder.addFNC3SymbolSeparator();
textBuilder.addFNC3ReaderInitialization();
textBuilder.addPlainCodetext("Reader initialization info");
//generate codetext
let codetext = textBuilder.getExtendedCodetext();
//generate
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
generator.save("test.bmp", BarCodeImageFormat.BMP);
```

### See Also

* assembly [Aspose.BarCode](../)

