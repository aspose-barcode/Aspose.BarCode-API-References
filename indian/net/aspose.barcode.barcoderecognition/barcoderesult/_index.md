---
title: "Class BarCodeResult"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeResult class. यह पहचाने गए बारकोड डेटा को संग्रहीत करता है जैसे SingleDecodeType प्रकार, String codetext, BarCodeRegionParameters क्षेत्र और अन्य पैरामीटर।"
type: docs
weight: 100
url: /hi/net/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class

पहचाने गए बारकोड डेटा को संग्रहीत करता है जैसे [`SingleDecodeType`](../singledecodetype/) प्रकार, String codetext, [`BarCodeRegionParameters`](../barcoderegionparameters/) क्षेत्र और अन्य पैरामीटर।

```csharp
public sealed class BarCodeResult : ICloneable, IEquatable<BarCodeResult>
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [BarCodeResult](barcoderesult/)(BarCodeResult) | `BarCodeResult` क्लास की एक कॉपी बनाता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [CodeBytes](../../aspose.barcode.barcoderecognition/barcoderesult/codebytes/) { get; } | एन्कोडेड कोड बाइट्स प्राप्त करता है |
| [CodeText](../../aspose.barcode.barcoderecognition/barcoderesult/codetext/) { get; } | कोड टेक्स्ट प्राप्त करता है |
| [CodeType](../../aspose.barcode.barcoderecognition/barcoderesult/codetype/) { get; } | बारकोड प्रकार प्राप्त करता है |
| [CodeTypeName](../../aspose.barcode.barcoderecognition/barcoderesult/codetypename/) { get; } | बारकोड प्रकार का नाम प्राप्त करता है |
| [Confidence](../../aspose.barcode.barcoderecognition/barcoderesult/confidence/) { get; } | पहचाने गए बारकोड का पहचान विश्वसनीयता स्तर प्राप्त करता है |
| [Extended](../../aspose.barcode.barcoderecognition/barcoderesult/extended/) { get; } | पहचाने गए बारकोड के विस्तारित पैरामीटर प्राप्त करता है |
| [IsoSymbolQuality](../../aspose.barcode.barcoderecognition/barcoderesult/isosymbolquality/) { get; } | पहचाने गए बारकोड के लिए ISO/IEC प्रतीक गुणवत्ता मूल्यांकन परिणाम प्राप्त करता है। |
| [ReadingQuality](../../aspose.barcode.barcoderecognition/barcoderesult/readingquality/) { get; } | पढ़ने की गुणवत्ता प्राप्त करता है। 1D और डाक बारकोड के लिए काम करता है। |
| [Region](../../aspose.barcode.barcoderecognition/barcoderesult/region/) { get; } | बारकोड क्षेत्र प्राप्त करता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Clone](../../aspose.barcode.barcoderecognition/barcoderesult/clone/)() | `BarCodeResult` क्लास की एक प्रति बनाता है। |
| [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals)(BarCodeResult) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट `BarCodeResult` मान के बराबर है या नहीं। |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals_1)(object) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट `BarCodeResult` मान के बराबर है या नहीं। |
| [GetCodeText](../../aspose.barcode.barcoderecognition/barcoderesult/getcodetext/)(Encoding) | एन्कोडिंग के साथ कोड टेक्स्ट प्राप्त करता है। |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderesult/gethashcode/)() | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderesult/tostring/)() | इस `BarCodeResult` का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderesult/op_equality/) | एक मान लौटाता है जो दर्शाता है कि पहला `BarCodeResult` मान दूसरे के बराबर है या नहीं। |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderesult/op_inequality/) | एक मान लौटाता है जो दर्शाता है कि पहला `BarCodeResult` मान दूसरे से अलग है या नहीं। |

## उदाहरण

यह उदाहरण दिखाता है कि BarCodeResult कैसे प्राप्त किया जाए।

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
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
        Console.WriteLine("BarCode Angle: " + result.Region.Angle);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

### और देखें

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


