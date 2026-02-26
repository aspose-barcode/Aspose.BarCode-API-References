---
title: BarCodeReader Class
linktitle: BarCodeReader
articleTitle: BarCodeReader
second_title: Aspose.BarCode for Node.js via Java
description: "BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes."
type: docs
weight: 1260
url: /nodejs/barcodereader/
---
## BarCodeReader class

BarCodeReader encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```javascript
public class BarCodeReader : joint.BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [BarCodeReader](./barcodereader/#constructor)(*object, object, object*) | Initializes a new instance of the BarCodeReader. |

## Methods

| Name | Description |
| --- | --- |
| [abort](./abort/) |  |
| [construct](./construct/)(*object*) |  |
| [containsAny](./containsany/)(*object*) | Determines whether any of the given decode types is included into. |
| [convertToString](./converttostring/)(*object*) | internal. |
| [exportToXml](./exporttoxml/)(*object*) | Exports BarCode properties to the xml-file specified. |
| [getBarCodeDecodeType](./getbarcodedecodetype/) | Gets the decode type of the input barcode decoding. |
| [getBarcodeSettings](./getbarcodesettings/) | The main BarCode decoding parameters. Contains parameters which make influence on recognized data. |
| [getFoundBarCodes](./getfoundbarcodes/) | Gets recognized BarCodeResult array. |
| [getFoundCount](./getfoundcount/) | Gets recognized barcodes count. |
| [getQualitySettings](./getqualitysettings/) | QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality. |
| [getTimeout](./gettimeout/) | Gets the timeout of recognition process in milliseconds. |
| [importFromXml](./importfromxml/)(*object*) | Exports BarCode properties to the xml-file specified. |
| [init](./init/) |  |
| [javaClassName](./javaclassname/) |  |
| [readBarCodes](./readbarcodes/) | Reads BarCodeResult from the image. |
| [setBarCodeImage](./setbarcodeimage/)(*object, object*) | Sets bitmap image and areas for recognition. Must be called before ReadBarCodes() method. |
| [setBarCodeReadType](./setbarcodereadtype/)(*object*) | Sets SingleDecodeType type array for recognition. Must be called before readBarCodes() method. |
| [setQualitySettings](./setqualitysettings/)(*object*) | QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality. |
| [setTimeout](./settimeout/)(*object*) | Sets the timeout of recognition process in milliseconds. |

## Fields

| Name | Description |
| --- | --- |
| [barcodeSettings](./barcodesettings/) |  |
| [qualitySettings](./qualitysettings/) |  |
| [recognizedResults](./recognizedresults/) |  |

## Examples

```javascript
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

### See Also

* assembly [Aspose.BarCode](../)

