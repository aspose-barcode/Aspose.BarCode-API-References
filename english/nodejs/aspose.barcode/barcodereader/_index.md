---
title: "BarCodeReader Class"
linktitle: "BarCodeReader"
articleTitle: "BarCodeReader"
second_title: "Aspose.BarCode for Node.js via Java"
description: "BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes."
type: docs
weight: 90
url: /nodejs/aspose.barcode/barcodereader/
---

## BarCodeReader class

BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```js
new BarCodeReader(image, areas, decodeTypes)
```

Initializes a new instance of the BarCodeReader

| Parameter | Description |
| --- | --- |
| image | encoded as base64 string or path to image |
| areas | array of object by type Rectangle |
| decodeTypes | the array of objects by DecodeType |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader("test.png", null,  [DecodeType.CODE_39, DecodeType.CODE_128]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

## Methods

| Name | Description |
| --- | --- |
| [importFromXml(xmlFile)](./importfromxml/) *(static)* | Exports BarCode properties to the xml-file specified |
| [containsAny()](./containsany/) | Determines whether any of the given decode types is included into |
| [exportToXml(xmlFile)](./exporttoxml/) | Exports BarCode properties to the xml-file specified |
| [getBarCodeReadType()](./getbarcodereadtype/) | Gets the decode type of the input barcode decoding |
| [getBarcodeSettings()](./getbarcodesettings/) | The main BarCode decoding parameters. Contains parameters which make influence on recognized data. |
| [getFoundBarCodes()](./getfoundbarcodes/) | Gets recognized BarCodeResult array |
| [getFoundCount()](./getfoundcount/) | Gets recognized barcodes count |
| [getQualitySettings()](./getqualitysettings/) | QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by em |
| [getTimeout()](./gettimeout/) | Gets the timeout of recognition process in milliseconds. |
| [readBarCodes()](./readbarcodes/) | Reads BarCodeResult from the image. |
| [setBarCodeImage(imageResource, …areas)](./setbarcodeimage/) | Sets bitmap image and areas for recognition. Must be called before ReadBarCodes() method. |
| [setBarCodeReadType(…types)](./setbarcodereadtype/) | Sets SingleDecodeType type array for recognition. Must be called before readBarCodes() method. |
| [setQualitySettings()](./setqualitysettings/) | QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by em |
| [setTimeout(value)](./settimeout/) | Sets the timeout of recognition process in milliseconds. |
