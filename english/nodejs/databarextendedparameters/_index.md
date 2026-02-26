---
title: DataBarExtendedParameters Class
linktitle: DataBarExtendedParameters
articleTitle: DataBarExtendedParameters
second_title: Aspose.BarCode for Node.js via Java
description: Stores a DataBar additional information of recognized barcode.
type: docs
weight: 1370
url: /nodejs/databarextendedparameters/
---
## DataBarExtendedParameters class

Stores a DataBar additional information of recognized barcode

```javascript
public class DataBarExtendedParameters : joint.BaseJavaClass
```

## Methods

| Name | Description |
| --- | --- |
| [equals](./equals/)(*object*) | Returns a value indicating whether this instance is equal to a specified DataBarExtendedParameters value. |
| [hashCode](./hashcode/) | Returns the hash code for this instance. |
| [init](./init/) |  |
| [is2DCompositeComponent](./is2dcompositecomponent/) | Gets the DataBar 2D composite component flag. Default value is false. |
| [toString](./tostring/) | Returns a human-readable string representation of this [`DataBarExtendedParameters`](..//databarextendedparameters/). |

## Examples

```javascript
let reader = new BarCodeReader("c:\\test.png", DecodeType.DATABAR_OMNI_DIRECTIONAL);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode Type: " + result.getCodeTypeName());
console.log("BarCode CodeText: " + result.getCodeText());
console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
}
```

### See Also

* assembly [Aspose.BarCode](../)

