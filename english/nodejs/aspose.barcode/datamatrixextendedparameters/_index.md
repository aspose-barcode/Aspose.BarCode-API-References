---
title: "DataMatrixExtendedParameters"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Stores special data of DataMatrix recognized barcode This sample shows how to get DataMatrix raw values let generator = new BarcodeGenerator(EncodeTypes.DATA_MA"
type: docs
weight: 350
url: /nodejs/aspose.barcode/datamatrixextendedparameters/
---

## DataMatrixExtendedParameters class

Stores special data of DataMatrix recognized barcode This sample shows how to get DataMatrix raw values let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345")) generator.save("test.png", BarcodeImageFormat.PNG); let reader = new BarCodeReader("test.png", null, DecodeType.DATA_MATRIX)) let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode type: " + result.getCodeTypeName()); console.log("BarCode codetext: " + result.getCodeText()); console.log("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId()); console.log("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount()); console.log("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId()); console.log("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming()); }

```js
new DataMatrixExtendedParameters()
```

## Methods

| Name | Description |
| --- | --- |
| [equals(obj)](#equals) | Returns a value indicating whether this instance is equal to a specified `DataMatrixExtendedParameters` value. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Gets the ID of the DataMatrix structured append mode barcode. ID starts from 1 and must be less or equal to barcodes cou |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Gets the DataMatrix structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35. Valu |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Gets the ID of the DataMatrix structured append mode barcode. ID starts from 1 and must be less or equal to barcodes cou |
| [hashCode()](#hashcode) | Returns the hash code for this instance. |
| [isReaderProgramming()](#isreaderprogramming) | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or |
| [toString()](#tostring) | Returns a human-readable string representation of this `DataMatrixExtendedParameters`. |

### equals(obj) {#equals}

Returns a value indicating whether this instance is equal to a specified `DataMatrixExtendedParameters` value.

| Parameter | Description |
| --- | --- |
| obj | An System.Object value to compare to this instance. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Gets the ID of the DataMatrix structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1. Value: The ID of the DataMatrix structured append mode barcode.

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Gets the DataMatrix structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35. Value: The count of the DataMatrix structured append mode barcode.

### getStructuredAppendFileId() {#getstructuredappendfileid}

Gets the ID of the DataMatrix structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1. Value: The ID of the DataMatrix structured append mode barcode.

### hashCode() {#hashcode}

Returns the hash code for this instance.

**Returns:** A 32-bit signed integer hash code.

### isReaderProgramming() {#isreaderprogramming}

Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false.

### toString() {#tostring}

Returns a human-readable string representation of this `DataMatrixExtendedParameters`.

**Returns:** A string that represents this `DataMatrixExtendedParameters`.
