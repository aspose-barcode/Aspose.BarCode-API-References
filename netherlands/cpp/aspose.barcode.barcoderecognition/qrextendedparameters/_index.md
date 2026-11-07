---
title: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters class"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters class. Slaat QR Structured Append-informatie van herkende barcode op in C++."
type: docs
weight: 2900
url: /nl/cpp/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class


Slaat een [QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append-informatie van herkende barcode op

```cpp
class QRExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_ErrorLevel](./get_errorlevel/)() const | Reed-Solomon-foutcorrectieniveau van herkende barcode. Van laag naar hoog: LevelL, LevelM, LevelQ, LevelH. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Test** of alle parameters alleen standaardwaarden hebben |
| [get_MicroQRVersion](./get_microqrversion/)() const | Versie van herkende MicroQR Code. Van M1 tot M4. |
| [get_RectMicroQRVersion](./get_rectmicroqrversion/)() const | Versie van herkende RectMicroQR Code. Van R7x43 tot R17x139. |
| [get_StructuredAppendModeBarCodeIndex](./get_structuredappendmodebarcodeindex/)() const | Haalt de index op van de [QR](../../aspose.barcode.barcoderecognition.qr/) gestructureerde append-modus barcode. Index begint bij 0. Standaardwaarde is -1. |
| [get_StructuredAppendModeBarCodesQuantity](./get_structuredappendmodebarcodesquantity/)() const | Haalt de hoeveelheid [QR](../../aspose.barcode.barcoderecognition.qr/) gestructureerde append-modus barcodes op. Standaardwaarde is -1. |
| [get_StructuredAppendModeParityData](./get_structuredappendmodeparitydata/)() const | Haalt de pariteitsgegevens van de [QR](../../aspose.barcode.barcoderecognition.qr/) gestructureerde append-modus op. Standaardwaarde is -1. |
| [get_Version](./get_version/)() const | Versie van herkende [QR](../../aspose.barcode.barcoderecognition.qr/) Code. Van Version1 tot Version40. |
| [GetHashCode](./gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| [ToString](./tostring/)() const override | Retourneert een menselijk leesbare tekenreeksrepresentatie van dit [QRExtendedParameters](./). |
## Opmerkingen


Dit voorbeeld laat zien hoe je [QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append-gegevens kunt ophalen.
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

## Zie ook

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
