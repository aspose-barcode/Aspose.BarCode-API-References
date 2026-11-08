---
title: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters klass"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters klass. Lagrar en QR Structured Append‑information för igenkänd streckkod i C++."
type: docs
weight: 2900
url: /sv/cpp/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class


Lagrar en [QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append‑information för igenkänd streckkod

```cpp
class QRExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_ErrorLevel](./get_errorlevel/)() const | Reed‑Solomon felkorrigeringsnivå för igenkänd streckkod. Från låg till hög: LevelL, LevelM, LevelQ, LevelH. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Testar** om alla parametrar endast har standardvärden |
| [get_MicroQRVersion](./get_microqrversion/)() const | Version av igenkänd MicroQR‑kod. Från M1 till M4. |
| [get_RectMicroQRVersion](./get_rectmicroqrversion/)() const | Version av igenkänd RectMicroQR‑kod. Från R7x43 till R17x139. |
| [get_StructuredAppendModeBarCodeIndex](./get_structuredappendmodebarcodeindex/)() const | Hämtar indexet för [QR](../../aspose.barcode.barcoderecognition.qr/) strukturerat append‑läge streckkod. Indexet startar från 0. Standardvärdet är -1. |
| [get_StructuredAppendModeBarCodesQuantity](./get_structuredappendmodebarcodesquantity/)() const | Hämtar antalet [QR](../../aspose.barcode.barcoderecognition.qr/) strukturerade append‑läge streckkoder. Standardvärdet är -1. |
| [get_StructuredAppendModeParityData](./get_structuredappendmodeparitydata/)() const | Hämtar paritetsdata för [QR](../../aspose.barcode.barcoderecognition.qr/) strukturerat append‑läge. Standardvärdet är -1. |
| [get_Version](./get_version/)() const | Version av igenkänd [QR](../../aspose.barcode.barcoderecognition.qr/)‑kod. Från Version1 till Version40. |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av detta [QRExtendedParameters](./). |
## Anmärkningar


Detta exempel visar hur man får [QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append‑data.
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

## Se även

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
