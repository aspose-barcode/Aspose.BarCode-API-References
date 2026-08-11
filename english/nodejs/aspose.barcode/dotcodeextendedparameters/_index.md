---
title: "DotCodeExtendedParameters"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Stores special data of DotCode recognized barcode This sample shows how to get DotCode raw values"
type: docs
weight: 380
url: /nodejs/aspose.barcode/dotcodeextendedparameters/
---

## DotCodeExtendedParameters class

Stores special data of DotCode recognized barcode This sample shows how to get DotCode raw values

```js
new DotCodeExtendedParameters()
```

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
generator.save("test.png", BarCodeImageFormat.PNG);

let reader = new BarCodeReader("test.png", null, DecodeType.DOT_CODE);
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

## Methods

| Name | Description |
| --- | --- |
| [equals(obj)](#equals) | Returns a value indicating whether this instance is equal to a specified `DotCodeExtendedParameters` value. |
| [getDotCodeIsReaderInitialization()](#getdotcodeisreaderinitialization) ~~(deprecated)~~ | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or |
| [getDotCodeStructuredAppendModeBarcodeId()](#getdotcodestructuredappendmodebarcodeid) ~~(deprecated)~~ | Gets the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getdotcodestructuredappendmodebarcodescount) ~~(deprecated)~~ | Gets the DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35. Value:  |
| [getStructuredAppendModeBarcodeId()](#getstructuredappendmodebarcodeid) | Gets the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. |
| [getStructuredAppendModeBarcodesCount()](#getstructuredappendmodebarcodescount) | Gets the DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35. Value:  |
| [hashCode()](#hashcode) | Returns the hash code for this instance. |
| [isReaderInitialization()](#isreaderinitialization) | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or |
| [toString()](#tostring) | Returns a human-readable string representation of this `DotCodeExtendedParameters`. |

### equals(obj) {#equals}

Returns a value indicating whether this instance is equal to a specified `DotCodeExtendedParameters` value.

| Parameter | Description |
| --- | --- |
| obj | An System.Object value to compare to this instance. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDotCodeIsReaderInitialization() {#getdotcodeisreaderinitialization}

> **Deprecated.** See method description for replacement.

Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false.

### getDotCodeStructuredAppendModeBarcodeId() {#getdotcodestructuredappendmodebarcodeid}

> **Deprecated.** See method description for replacement.

Gets the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1. Value: The ID of the DotCode structured append mode barcode.

### getDotCodeStructuredAppendModeBarcodesCount() {#getdotcodestructuredappendmodebarcodescount}

> **Deprecated.** See method description for replacement.

Gets the DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35. Value: The count of the DotCode structured append mode barcode.

### getStructuredAppendModeBarcodeId() {#getstructuredappendmodebarcodeid}

Gets the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1. Value: The ID of the DotCode structured append mode barcode.

**Returns:** the ID of the DotCode structured append mode barcode.

### getStructuredAppendModeBarcodesCount() {#getstructuredappendmodebarcodescount}

Gets the DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35. Value: The count of the DotCode structured append mode barcode.

**Returns:** the DotCode structured append mode barcodes count.

### hashCode() {#hashcode}

Returns the hash code for this instance.

**Returns:** A 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false.

### toString() {#tostring}

Returns a human-readable string representation of this `DotCodeExtendedParameters`.

**Returns:** A string that represents this `DotCodeExtendedParameters`.
