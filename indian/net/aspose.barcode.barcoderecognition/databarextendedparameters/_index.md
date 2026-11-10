---
title: "क्लास DataBarExtendedParameters"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.BarCodeRecognition.DataBarExtendedParameters क्लास। पहचाने गए बारकोड की DataBar अतिरिक्त जानकारी संग्रहीत करता है।"
type: docs
weight: 210
url: /hi/net/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class

पहचाने गए बारकोड की DataBar अतिरिक्त जानकारी संग्रहीत करता है

```csharp
public sealed class DataBarExtendedParameters : BaseExtendedParameters
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Is2DCompositeComponent](../../aspose.barcode.barcoderecognition/databarextendedparameters/is2dcompositecomponent/) { get; } | DataBar 2D कॉम्पोजिट कंपोनेंट फ़्लैग प्राप्त करता है। डिफ़ॉल्ट मान false है। |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | जाँचता है कि क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/databarextendedparameters/equals/)(object) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट `DataBarExtendedParameters` मान के बराबर है या नहीं। |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/databarextendedparameters/gethashcode/)() | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| override [ToString](../../aspose.barcode.barcoderecognition/databarextendedparameters/tostring/)() | इस `DataBarExtendedParameters` की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [operator ==](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_equality/) | एक मान लौटाता है जो दर्शाता है कि पहला `DataBarExtendedParameters` मान दूसरे के बराबर है या नहीं। |
| [operator !=](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_inequality/) | एक मान लौटाता है जो दर्शाता है कि पहला `DataBarExtendedParameters` मान दूसरे से अलग है या नहीं। |

## उदाहरण

यह उदाहरण दिखाता है कि DataBar अतिरिक्त जानकारी कैसे प्राप्त करें।

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DatabarOmniDirectional))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.DatabarOmniDirectional)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
    Next
End Using
```

### और देखें

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


