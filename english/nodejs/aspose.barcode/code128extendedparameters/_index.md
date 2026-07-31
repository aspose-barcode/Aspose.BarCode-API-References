---
title: "Code128ExtendedParameters Class"
linktitle: "Code128ExtendedParameters"
articleTitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Stores special data of Code128 recognized barcode Represents the recognized barcode's region and barcode angle"
type: docs
weight: 240
url: /nodejs/aspose.barcode/code128extendedparameters/
---

## Code128ExtendedParameters class

Stores special data of Code128 recognized barcode Represents the recognized barcode's region and barcode angle

```js
new Code128ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get code128 raw values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.CODE_128);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("Code128 Data Portions: " + result.getExtended().getCode128());
}
```

## Methods

| Name | Description |
| --- | --- |
| [equals(obj)](./equals/) | Returns a value indicating whether this instance is equal to a specified Code128ExtendedParameters value. |
| [getCode128DataPortions()](./getcode128dataportions/) | Gets Code128DataPortion array of recognized Code128 barcode Value of the Code128DataPortion. |
| [hashCode()](./hashcode/) | Returns the hash code for this instance. |
| [toString()](./tostring/) | Returns a human-readable string representation of this Code128ExtendedParameters. |
