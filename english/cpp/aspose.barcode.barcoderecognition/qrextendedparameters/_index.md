---
title: Aspose::BarCode::BarCodeRecognition::QRExtendedParameters class
linktitle: QRExtendedParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::QRExtendedParameters class. Stores a QR Structured Append information of recognized barcode in C++.'
type: docs
weight: 2600
url: /cpp/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class


Stores a QR Structured Append information of recognized barcode

```cpp
class QRExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Description |
| --- | --- |
| [get_ErrorLevel](./get_errorlevel/)() | Reed-Solomon error correction level of recognized barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() | **Tests** whether all parameters has only default values |
| [get_MicroQRVersion](./get_microqrversion/)() | Version of recognized MicroQR Code. From M1 to M4. |
| [get_QRErrorLevel](./get_qrerrorlevel/)() | Reed-Solomon error correction level of recognized barcode. From low to high: LevelL, LevelM, LevelQ, LevelH. |
| [get_QRStructuredAppendModeBarCodeIndex](./get_qrstructuredappendmodebarcodeindex/)() | Gets the index of the QR structured append mode barcode. Index starts from 0. Default value is -1. |
| [get_QRStructuredAppendModeBarCodesQuantity](./get_qrstructuredappendmodebarcodesquantity/)() | Gets the QR structured append mode barcodes quantity. Default value is -1. |
| [get_QRStructuredAppendModeParityData](./get_qrstructuredappendmodeparitydata/)() | Gets the QR structured append mode parity data. Default value is -1. |
| [get_QRVersion](./get_qrversion/)() | Version of recognized QR Code. From Version1 to Version40. |
| [get_RectMicroQRVersion](./get_rectmicroqrversion/)() | Version of recognized RectMicroQR Code. From R7x43 to R17x139. |
| [get_StructuredAppendModeBarCodeIndex](./get_structuredappendmodebarcodeindex/)() | Gets the index of the QR structured append mode barcode. Index starts from 0. Default value is -1. |
| [get_StructuredAppendModeBarCodesQuantity](./get_structuredappendmodebarcodesquantity/)() | Gets the QR structured append mode barcodes quantity. Default value is -1. |
| [get_StructuredAppendModeParityData](./get_structuredappendmodeparitydata/)() | Gets the QR structured append mode parity data. Default value is -1. |
| [get_Version](./get_version/)() | Version of recognized QR Code. From Version1 to Version40. |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [QRExtendedParameters](./). |
## Remarks


This sample shows how to get QR Structured Append data 
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex);
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex)
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData)
    Next
End Using
```

## See Also

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
