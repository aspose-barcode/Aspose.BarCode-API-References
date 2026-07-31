---
title: "OneDExtendedParameters Class"
linktitle: "OneDExtendedParameters"
articleTitle: "OneDExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Stores special data of 1D recognized barcode like separate codetext and checksum"
type: docs
weight: 720
url: /nodejs/aspose.barcode/onedextendedparameters/
---

## OneDExtendedParameters class

Stores special data of 1D recognized barcode like separate codetext and checksum

```js
new OneDExtendedParameters()
```

**Example:**

```js
//This sample shows how to get 1D barcode value and checksum
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.EAN_13);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Value: " + result.getExtended().getOneD().getValue());
   console.log("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

## Methods

| Name | Description |
| --- | --- |
| [equals(obj)](./equals/) | Returns a value indicating whether this instance is equal to a specified OneDExtendedParameters value. |
| [getCheckSum()](./getchecksum/) | Gets the checksum for 1D barcodes. Value: The checksum for 1D barcode. |
| [getValue()](./getvalue/) | Gets the codetext of 1D barcodes without checksum. Value: The codetext of 1D barcodes without checksum. |
| [hashCode()](./hashcode/) | Returns the hash code for this instance. |
| [isEmpty()](./isempty/) | Tests whether all parameters has only default values Value: Returns `true ` if all parameters has only default values; o |
| [toString()](./tostring/) | Returns a human-readable string representation of this OneDExtendedParameters. |
