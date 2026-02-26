---
title: "DotCodeExtendedParameters Class"
linktitle: "DotCodeExtendedParameters"
articleTitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Stores special data of DotCode recognized barcode."
type: docs
weight: 1420
url: /nodejs/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class

Stores special data of DotCode recognized barcode

```javascript
public class DotCodeExtendedParameters : joint.BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/#constructor)(*object*) | Initializes a new instance of the DotCodeExtendedParameters class. |

## Methods

| Name | Description |
| --- | --- |
| [equals](./equals/)(*object*) | Returns a value indicating whether this instance is equal to a specified DotCodeExtendedParameters value. |
| [getDotCodeIsReaderInitialization](./getdotcodeisreaderinitialization/) | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false. |
| [getDotCodeStructuredAppendModeBarcodeId](./getdotcodestructuredappendmodebarcodeid/) |  |
| [getDotCodeStructuredAppendModeBarcodesCount](./getdotcodestructuredappendmodebarcodescount/) |  |
| [getStructuredAppendModeBarcodeId](./getstructuredappendmodebarcodeid/) | Value: The ID of the DotCode structured append mode barcode. |
| [getStructuredAppendModeBarcodesCount](./getstructuredappendmodebarcodescount/) | Value: The count of the DotCode structured append mode barcode. |
| [hashCode](./hashcode/) | Returns the hash code for this instance. |
| [init](./init/) |  |
| [isReaderInitialization](./isreaderinitialization/) | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false. |
| [toString](./tostring/) | Returns a human-readable string representation of this DotCodeExtendedParameters. |

## Examples

```javascript
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
generator.save("c:\\test.png", BarCodeImageFormat.PNG);
let reader = new BarCodeReader("c:\\test.png", null, DecodeType.DOT_CODE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
print("BarCode type: " + result.getCodeTypeName());
print("BarCode codetext: " + result.getCodeText());
print("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
print("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
}
```

### See Also

* assembly [Aspose.BarCode](../)

