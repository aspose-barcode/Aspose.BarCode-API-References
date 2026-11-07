---
title: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters Klasse"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters Klasse. Speichert QR Structured Append-Informationen des erkannten Barcodes in C++."
type: docs
weight: 2900
url: /de/cpp/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class


Speichert eine [QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append-Information des erkannten Barcodes

```cpp
class QRExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_ErrorLevel](./get_errorlevel/)() const | Reed-Solomon-Fehlerkorrekturstufe des erkannten Barcodes. Von niedrig nach hoch: LevelL, LevelM, LevelQ, LevelH. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** ob alle Parameter nur Standardwerte haben |
| [get_MicroQRVersion](./get_microqrversion/)() const | Version des erkannten MicroQR-Codes. Von M1 bis M4. |
| [get_RectMicroQRVersion](./get_rectmicroqrversion/)() const | Version des erkannten RectMicroQR-Codes. Von R7x43 bis R17x139. |
| [get_StructuredAppendModeBarCodeIndex](./get_structuredappendmodebarcodeindex/)() const | Liefert den Index des [QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append-Modus-Barcodes. Der Index beginnt bei 0. Standardwert ist -1. |
| [get_StructuredAppendModeBarCodesQuantity](./get_structuredappendmodebarcodesquantity/)() const | Liefert die Menge der [QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append-Modus-Barcodes. Standardwert ist -1. |
| [get_StructuredAppendModeParityData](./get_structuredappendmodeparitydata/)() const | Liefert die Paritätsdaten des [QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append-Modus. Standardwert ist -1. |
| [get_Version](./get_version/)() const | Version des erkannten [QR](../../aspose.barcode.barcoderecognition.qr/) Codes. Von Version1 bis Version40. |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [QRExtendedParameters](./) zurück. |
## Hinweise


Dieses Beispiel zeigt, wie man [QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append-Daten erhält
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

## Siehe auch

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
