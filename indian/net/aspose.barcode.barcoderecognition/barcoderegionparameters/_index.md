---
title: "क्लास BarCodeRegionParameters"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeRegionParameters क्लास। पहचाने गए बारकोड क्षेत्रों और बारकोड कोण का प्रतिनिधित्व करता है"
type: docs
weight: 90
url: /hi/net/aspose.barcode.barcoderecognition/barcoderegionparameters/
---
## BarCodeRegionParameters class

पहचाने गए बारकोड का क्षेत्र और बारकोड कोण दर्शाता है

```csharp
public sealed class BarCodeRegionParameters
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Angle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/angle/) { get; } | बारकोड का कोण प्राप्त करता है (0-360)। |
| [Points](../../aspose.barcode.barcoderecognition/barcoderegionparameters/points/) { get; } | बारकोड क्षेत्र को सीमित करने वाले पॉइंट्स एरे को प्राप्त करता है |
| [Quadrangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/quadrangle/) { get; } | बारकोड क्षेत्र को सीमित करने वाला [`Quadrangle`](../quadrangle/) प्राप्त करता है |
| [Rectangle](../../aspose.barcode.barcoderecognition/barcoderegionparameters/rectangle/) { get; } | बारकोड क्षेत्र को सीमित करने वाला Rectangle प्राप्त करता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderegionparameters/equals/)(object) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट `BarCodeRegionParameters` मान के बराबर है या नहीं। |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderegionparameters/gethashcode/)() | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderegionparameters/tostring/)() | इस `BarCodeRegionParameters` की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_equality/) | एक मान लौटाता है जो दर्शाता है कि पहला `BarCodeRegionParameters` मान दूसरे के बराबर है या नहीं। |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderegionparameters/op_inequality/) | एक मान लौटाता है जो दर्शाता है कि पहला `BarCodeRegionParameters` मान दूसरे से अलग है या नहीं। |

## उदाहरण

यह उदाहरण दिखाता है कि बारकोड कोण और सीमित क्वाड्रैंगल मान कैसे प्राप्त करें

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
        Console.WriteLine("BarCode Quadrangle: " + result.Region.Quadrangle)
    Next
End Using
```

### और देखें

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


