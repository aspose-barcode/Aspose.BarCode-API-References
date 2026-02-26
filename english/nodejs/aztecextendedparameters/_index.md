---
title: "AztecExtendedParameters Class"
linktitle: "AztecExtendedParameters"
articleTitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Stores special data of Aztec recognized barcode."
type: docs
weight: 1450
url: /nodejs/aztecextendedparameters/
---
## AztecExtendedParameters class

Stores special data of Aztec recognized barcode

```javascript
public class AztecExtendedParameters : joint.BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [AztecExtendedParameters](./aztecextendedparameters/#constructor)(*object*) | Initializes a new instance of the AztecExtendedParameters class. |

## Methods

| Name | Description |
| --- | --- |
| [equals](./equals/)(*object*) | Returns a value indicating whether this instance is equal to a specified AztecExtendedParameters value. |
| [getStructuredAppendBarcodeId](./getstructuredappendbarcodeid/) |  |
| [getStructuredAppendBarcodesCount](./getstructuredappendbarcodescount/) |  |
| [getStructuredAppendFileId](./getstructuredappendfileid/) |  |
| [hashCode](./hashcode/) | Returns the hash code for this instance. |
| [init](./init/) |  |
| [isReaderInitialization](./isreaderinitialization/) | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false. |
| [toString](./tostring/) | Returns a human-readable string representation of this AztecExtendedParameters. |

## Examples

BarCodeReader reader = new BarCodeReader("test.png", null, DecodeType.AZTEC);

```javascript
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode type: " + result.getCodeTypeName());
console.log("BarCode codetext: " + result.getCodeText());
console.log("Aztec barcode ID: " + result.getExtended().getAztec().getStructuredAppendBarcodeId());
console.log("Aztec barcodes count: " + result.getExtended().getAztec().getStructuredAppendBarcodesCount());
console.log("Aztec file ID: " + result.getExtended().getAztec().getStructuredAppendFileId());
console.log("Aztec is reader initialization: " + result.getExtended().getAztec().isReaderInitialization());
}
</pre>
</pre></blockquote></hr></p>
```

### See Also

* assembly [Aspose.BarCode](../)

