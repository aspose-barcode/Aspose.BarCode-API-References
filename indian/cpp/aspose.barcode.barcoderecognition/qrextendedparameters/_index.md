---
title: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters क्लास"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters क्लास। मान्यता प्राप्त बारकोड की QR स्ट्रक्चर्ड अपेंड जानकारी C++ में संग्रहीत करता है।"
type: docs
weight: 2900
url: /hi/cpp/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class


मान्यता प्राप्त बारकोड की [QR](../../aspose.barcode.barcoderecognition.qr/) स्ट्रक्चर्ड अपेंड जानकारी संग्रहीत करता है

```cpp
class QRExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_ErrorLevel](./get_errorlevel/)() const | मान्यता प्राप्त बारकोड का Reed-Solomon त्रुटि सुधार स्तर। निम्न से उच्च: LevelL, LevelM, LevelQ, LevelH। |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं |
| [get_MicroQRVersion](./get_microqrversion/)() const | मान्यता प्राप्त MicroQR कोड का संस्करण। M1 से M4 तक। |
| [get_RectMicroQRVersion](./get_rectmicroqrversion/)() const | मान्यता प्राप्त RectMicroQR कोड का संस्करण। R7x43 से R17x139 तक। |
| [get_StructuredAppendModeBarCodeIndex](./get_structuredappendmodebarcodeindex/)() const | इस [QR](../../aspose.barcode.barcoderecognition.qr/) स्ट्रक्चर्ड अपेंड मोड बारकोड का सूचकांक प्राप्त करता है। सूचकांक 0 से शुरू होता है। डिफ़ॉल्ट मान -1 है। |
| [get_StructuredAppendModeBarCodesQuantity](./get_structuredappendmodebarcodesquantity/)() const | इस [QR](../../aspose.barcode.barcoderecognition.qr/) स्ट्रक्चर्ड अपेंड मोड बारकोड की मात्रा प्राप्त करता है। डिफ़ॉल्ट मान -1 है। |
| [get_StructuredAppendModeParityData](./get_structuredappendmodeparitydata/)() const | इस [QR](../../aspose.barcode.barcoderecognition.qr/) स्ट्रक्चर्ड अपेंड मोड पैरिटी डेटा प्राप्त करता है। डिफ़ॉल्ट मान -1 है। |
| [get_Version](./get_version/)() const | मान्यता प्राप्त [QR](../../aspose.barcode.barcoderecognition.qr/) कोड का संस्करण। Version1 से Version40 तक। |
| [GetHashCode](./gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [ToString](./tostring/)() const override | इस [QRExtendedParameters](./) की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
## टिप्पणियाँ


यह नमूना दिखाता है कि कैसे [QR](../../aspose.barcode.barcoderecognition.qr/) स्ट्रक्चर्ड अपेंड डेटा प्राप्त किया जाए
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

## और देखें

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
