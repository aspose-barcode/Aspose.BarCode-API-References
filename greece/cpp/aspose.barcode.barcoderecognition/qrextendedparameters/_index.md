---
title: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters class"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters class. Αποθηκεύει πληροφορίες QR Structured Append του αναγνωρισμένου barcode σε C++."
type: docs
weight: 2900
url: /el/cpp/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class


Αποθηκεύει μια [QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append πληροφορία του αναγνωρισμένου barcode

```cpp
class QRExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [get_ErrorLevel](./get_errorlevel/)() const | Επίπεδο διόρθωσης σφαλμάτων Reed-Solomon του αναγνωρισμένου barcode. Από χαμηλό προς υψηλό: LevelL, LevelM, LevelQ, LevelH. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** αν όλες οι παράμετροι έχουν μόνο τις προεπιλεγμένες τιμές |
| [get_MicroQRVersion](./get_microqrversion/)() const | Έκδοση του αναγνωρισμένου MicroQR Code. Από M1 έως M4. |
| [get_RectMicroQRVersion](./get_rectmicroqrversion/)() const | Έκδοση του αναγνωρισμένου RectMicroQR Code. Από R7x43 έως R17x139. |
| [get_StructuredAppendModeBarCodeIndex](./get_structuredappendmodebarcodeindex/)() const | Λαμβάνει το ευρετήριο του [QR](../../aspose.barcode.barcoderecognition.qr/) barcode σε λειτουργία structured append. Το ευρετήριο ξεκινά από 0. Η προεπιλεγμένη τιμή είναι -1. |
| [get_StructuredAppendModeBarCodesQuantity](./get_structuredappendmodebarcodesquantity/)() const | Λαμβάνει την ποσότητα των [QR](../../aspose.barcode.barcoderecognition.qr/) barcode σε λειτουργία structured append. Η προεπιλεγμένη τιμή είναι -1. |
| [get_StructuredAppendModeParityData](./get_structuredappendmodeparitydata/)() const | Λαμβάνει τα parity δεδομένα του [QR](../../aspose.barcode.barcoderecognition.qr/) σε λειτουργία structured append. Η προεπιλεγμένη τιμή είναι -1. |
| [get_Version](./get_version/)() const | Έκδοση του αναγνωρισμένου [QR](../../aspose.barcode.barcoderecognition.qr/) Code. Από Version1 έως Version40. |
| [GetHashCode](./gethashcode/)() const override | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [ToString](./tostring/)() const override | Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά αναπαράστασης αυτού του [QRExtendedParameters](./). |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να λάβετε τα δεδομένα [QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append
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

## Δείτε επίσης

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
