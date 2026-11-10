---
title: "क्लास QRExtendedParameters"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.BarCodeRecognition.QRExtendedParameters क्लास। पहचाने गए बारकोड की QR Structured Append जानकारी संग्रहीत करता है।"
type: docs
weight: 350
url: /hi/net/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class

पहचाने गए बारकोड की QR Structured Append जानकारी को संग्रहीत करता है

```csharp
public sealed class QRExtendedParameters : BaseExtendedParameters
```

## गुण

| नाम | विवरण |
| --- | --- |
| [ErrorLevel](../../aspose.barcode.barcoderecognition/qrextendedparameters/errorlevel/) { get; } | पहचाने गए बारकोड का Reed-Solomon त्रुटि सुधार स्तर। निम्न से उच्च: LevelL, LevelM, LevelQ, LevelH। |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | जाँचता है कि क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं। |
| [MicroQRVersion](../../aspose.barcode.barcoderecognition/qrextendedparameters/microqrversion/) { get; } | पहचाने गए MicroQR कोड का संस्करण। M1 से M4 तक। |
| [RectMicroQRVersion](../../aspose.barcode.barcoderecognition/qrextendedparameters/rectmicroqrversion/) { get; } | पहचाने गए RectMicroQR कोड का संस्करण। R7x43 से R17x139 तक। |
| [StructuredAppendModeBarCodeIndex](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodebarcodeindex/) { get; } | QR Structured Append मोड बारकोड का सूचकांक प्राप्त करता है। सूचकांक 0 से शुरू होता है। डिफ़ॉल्ट मान -1 है। |
| [StructuredAppendModeBarCodesQuantity](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodebarcodesquantity/) { get; } | QR Structured Append मोड बारकोड की मात्रा प्राप्त करता है। डिफ़ॉल्ट मान -1 है। |
| [StructuredAppendModeParityData](../../aspose.barcode.barcoderecognition/qrextendedparameters/structuredappendmodeparitydata/) { get; } | QR Structured Append मोड पैरिटी डेटा प्राप्त करता है। डिफ़ॉल्ट मान -1 है। |
| [Version](../../aspose.barcode.barcoderecognition/qrextendedparameters/version/) { get; } | पहचाने गए QR कोड का संस्करण। Version1 से Version40 तक। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/qrextendedparameters/equals/)(object) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट `QRExtendedParameters` मान के बराबर है या नहीं। |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/qrextendedparameters/gethashcode/)() | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| override [ToString](../../aspose.barcode.barcoderecognition/qrextendedparameters/tostring/)() | इस `QRExtendedParameters` की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [operator ==](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_equality/) | पहले `QRExtendedParameters` मान के दूसरे के बराबर होने को दर्शाने वाला मान लौटाता है। |
| [operator !=](../../aspose.barcode.barcoderecognition/qrextendedparameters/op_inequality/) | पहले `QRExtendedParameters` मान के दूसरे से अलग होने को दर्शाने वाला मान लौटाता है। |

## उदाहरण

यह उदाहरण दिखाता है कि QR Structured Append डेटा कैसे प्राप्त करें।

```csharp
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

### और देखें

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


