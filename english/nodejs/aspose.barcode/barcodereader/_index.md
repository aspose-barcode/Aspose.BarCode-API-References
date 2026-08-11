---
title: "BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
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
| [importFromXml(xmlFile)](#importfromxml) *(static)* | Exports BarCode properties to the xml-file specified |
| [containsAny()](#containsany) | Determines whether any of the given decode types is included into |
| [exportToXml(xmlFile)](#exporttoxml) | Exports BarCode properties to the xml-file specified |
| [getBarCodeReadType()](#getbarcodereadtype) | Gets the decode type of the input barcode decoding |
| [getBarcodeSettings()](#getbarcodesettings) | The main BarCode decoding parameters. Contains parameters which make influence on recognized data. |
| [getFoundBarCodes()](#getfoundbarcodes) | Gets recognized BarCodeResult array |
| [getFoundCount()](#getfoundcount) | Gets recognized barcodes count |
| [getQualitySettings()](#getqualitysettings) | QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by em |
| [getTimeout()](#gettimeout) | Gets the timeout of recognition process in milliseconds. |
| [readBarCodes()](#readbarcodes) | Reads BarCodeResult from the image. |
| [setBarCodeImage(imageResource, …areas)](#setbarcodeimage) | Sets bitmap image and areas for recognition. Must be called before ReadBarCodes() method. |
| [setBarCodeReadType(…types)](#setbarcodereadtype) | Sets SingleDecodeType type array for recognition. Must be called before readBarCodes() method. |
| [setQualitySettings()](#setqualitysettings) | QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by em |
| [setTimeout(value)](#settimeout) | Sets the timeout of recognition process in milliseconds. |

### importFromXml(xmlFile) (static) {#importfromxml}

Exports BarCode properties to the xml-file specified

| Parameter | Description |
| --- | --- |
| xmlFile | The name of the file |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### containsAny() {#containsany}

Determines whether any of the given decode types is included into

| Parameter | Description |
| --- | --- |
| ...decodeTypes | Types to verify. |

**Returns:** bool Value is a true if any types are included into.

### exportToXml(xmlFile) {#exporttoxml}

Exports BarCode properties to the xml-file specified

| Parameter | Description |
| --- | --- |
| xmlFile | The name of the file |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### getBarCodeReadType() {#getbarcodereadtype}

Gets the decode type of the input barcode decoding

**Returns:** *

### getBarcodeSettings() {#getbarcodesettings}

The main BarCode decoding parameters. Contains parameters which make influence on recognized data.

**Returns:** The main BarCode decoding parameters

### getFoundBarCodes() {#getfoundbarcodes}

Gets recognized BarCodeResult array

**Returns:** recognized BarCodeResult array

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " +  reader.getFoundBarCodes()[i].getCodeText());
```

### getFoundCount() {#getfoundcount}

Gets recognized barcodes count

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
Value: The recognized barcodes count
```

### getQualitySettings() {#getqualitysettings}

QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality.

**Returns:** QualitySettings to configure recognition quality and speed.

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader

let reader = new BarCodeReader("test.png", null, null);
 //set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### getTimeout() {#gettimeout}

Gets the timeout of recognition process in milliseconds.

**Returns:** The timeout.

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### readBarCodes() {#readbarcodes}

Reads BarCodeResult from the image.

**Returns:** Returns array of recognized `BarCodeResult`s on the image. If nothing is recognized, zero array is returned.

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
```

### setBarCodeImage(imageResource, …areas) {#setbarcodeimage}

Sets bitmap image and areas for recognition. Must be called before ReadBarCodes() method.

| Parameter | Description |
| --- | --- |
| imageResource | The image for recognition. |
| areas | areas list for recognition |

**Throws:** BarcodeException

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let bmp = "test.png";
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
var img = new Image();
img.src = 'path_to_image';
width = img.width;
height = img.height;
reader.setBarCodeImage(bmp, new Rectangle[] { new Rectangle(0, 0, width, height) });
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setBarCodeReadType(…types) {#setbarcodereadtype}

Sets SingleDecodeType type array for recognition. Must be called before readBarCodes() method.

| Parameter | Description |
| --- | --- |
| types | The SingleDecodeType type array to read. |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.setBarCodeImage("test.png");
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setQualitySettings() {#setqualitysettings}

QualitySettings allows to configure recognition quality and speed manually. You can quickly set up QualitySettings by embedded presets: HighPerformance, NormalQuality, HighQuality, MaxBarCodes or you can manually configure separate options. Default value of QualitySettings is NormalQuality.

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setTimeout(value) {#settimeout}

Sets the timeout of recognition process in milliseconds.

| Parameter | Description |
| --- | --- |
| value | The timeout. |

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```
