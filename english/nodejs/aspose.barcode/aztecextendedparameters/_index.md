---
title: "AztecExtendedParameters"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Stores special data of Aztec recognized barcode This sample shows how to get Aztec raw values let generator = new BarcodeGenerator(EncodeTypes.AZTEC, \"12345\"); "
type: docs
weight: 60
url: /nodejs/aspose.barcode/aztecextendedparameters/
---

## AztecExtendedParameters class

Stores special data of Aztec recognized barcode This sample shows how to get Aztec raw values let generator = new BarcodeGenerator(EncodeTypes.AZTEC, "12345"); generator.save("test.png", BarcodeImageFormat.PNG);

```js
new AztecExtendedParameters()
```

**Example:**

```js
BarCodeReader reader = new BarCodeReader("test.png", null, DecodeType.AZTEC);
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

## Methods

| Name | Description |
| --- | --- |
| [equals(obj)](#equals) | Returns a value indicating whether this instance is equal to a specified `AztecExtendedParameters` value. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Gets the ID of the Aztec structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. D |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Gets the Aztec structured append mode barcodes count. Default value is 0. Count must be a value from 1 to 26. Value: The |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Gets the File ID of the Aztec structured append mode. Default value is empty string Value: The File ID of the Aztec stru |
| [hashCode()](#hashcode) | Returns the hash code for this instance. |
| [isReaderInitialization()](#isreaderinitialization) | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or |
| [toString()](#tostring) | Returns a human-readable string representation of this `AztecExtendedParameters`. |

### equals(obj) {#equals}

Returns a value indicating whether this instance is equal to a specified `AztecExtendedParameters` value.

| Parameter | Description |
| --- | --- |
| obj | An System.Object value to compare to this instance. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Gets the ID of the Aztec structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is 0. Value: The barcode ID of the Aztec structured append mode.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Gets the Aztec structured append mode barcodes count. Default value is 0. Count must be a value from 1 to 26. Value: The barcodes count of the Aztec structured append mode.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Gets the File ID of the Aztec structured append mode. Default value is empty string Value: The File ID of the Aztec structured append mode.

### hashCode() {#hashcode}

Returns the hash code for this instance.

**Returns:** 32-bit signed integer hash code.

### isReaderInitialization() {#isreaderinitialization}

Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false.

### toString() {#tostring}

Returns a human-readable string representation of this `AztecExtendedParameters`.

**Returns:** A string that represents this `AztecExtendedParameters`.
