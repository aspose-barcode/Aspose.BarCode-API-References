---
title: QRExtendedParameters Class
linktitle: QRExtendedParameters
articleTitle: QRExtendedParameters
second_title: Aspose.BarCode for Node.js via Java
description: Stores a QR Structured Append information of recognized barcode.
type: docs
weight: 1280
url: /nodejs/qrextendedparameters/
---
## QRExtendedParameters class

Stores a QR Structured Append information of recognized barcode

```javascript
public class QRExtendedParameters : joint.BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [QRExtendedParameters](./qrextendedparameters/#constructor)(*object*) | Initializes a new instance of the QRExtendedParameters class. |

## Methods

| Name | Description |
| --- | --- |
| [equals](./equals/)(*object*) | Returns a value indicating whether this instance is equal to a specified QRExtendedParameters value. |
| [getErrorLevel](./geterrorlevel/) | Reed-Solomon error correction level of recognized barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. |
| [getMicroQRVersion](./getmicroqrversion/) | Version of recognized MicroQR Code. From M1 to M4. |
| [getQRErrorLevel](./getqrerrorlevel/) | Reed-Solomon error correction level of recognized barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. |
| [getQRStructuredAppendModeBarCodeIndex](./getqrstructuredappendmodebarcodeindex/) | Gets the index of the QR structured append mode barcode. Index starts from 0. Default value is -1.Value: The quantity of the QR structured append mode barcode. |
| [getQRStructuredAppendModeBarCodesQuantity](./getqrstructuredappendmodebarcodesquantity/) | Gets the QR structured append mode barcodes quantity. Default value is -1.Value: The quantity of the QR structured append mode barcode. |
| [getQRStructuredAppendModeParityData](./getqrstructuredappendmodeparitydata/) | Gets the QR structured append mode parity data. Default value is -1.Value: The index of the QR structured append mode barcode. |
| [getQRVersion](./getqrversion/) | Version of recognized QR Code. From Version1 to Version40. |
| [getRectMicroQRVersion](./getrectmicroqrversion/) | Version of recognized RectMicroQR Code. From R7x43 to R17x139. |
| [getStructuredAppendModeBarCodeIndex](./getstructuredappendmodebarcodeindex/) | Value: The quantity of the QR structured append mode barcode. |
| [getStructuredAppendModeBarCodesQuantity](./getstructuredappendmodebarcodesquantity/) | Value: The quantity of the QR structured append mode barcode. |
| [getStructuredAppendModeParityData](./getstructuredappendmodeparitydata/) | Value: The index of the QR structured append mode barcode. |
| [getVersion](./getversion/) | Version of recognized QR Code. From Version1 to Version40. |
| [hashCode](./hashcode/) | Returns the hash code for this instance. |
| [init](./init/) |  |
| [isEmpty](./isempty/) |  |
| [toString](./tostring/) | Returns a human-readable string representation of this QRExtendedParameters. |

## Examples

```javascript
//This sample shows how to get QR Structured Append data
let reader = new BarCodeReader("test.png", null,  DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode Type: " + result.getCodeTypeName());
console.log("BarCode CodeText: " + result.getCodeText());
console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
console.log("QR Structured Append Index: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodeIndex());
console.log("QR Structured Append ParityData: " + result.getExtended().getQR().getQRStructuredAppendModeParityData());
}
```

### See Also

* assembly [Aspose.BarCode](../)

