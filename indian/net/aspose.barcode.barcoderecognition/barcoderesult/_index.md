---
title: BarCodeResult
second_title: Aspose.BarCode .NET API संदर्भ के लिए
description: स्टर जैसे मन्यत प्रप्त बरकड डेटSingleDecodeType./singledecodetype/ प्रकरString कडटेक्स्ट BarCodeRegionParameters./barcoderegionparameters/ क्षेत्र और अन्य पैरमटर
type: docs
weight: 90
url: /hi/net/aspose.barcode.barcoderecognition/barcoderesult/
---
## BarCodeResult class

स्टोर जैसे मान्यता प्राप्त बारकोड डेटा[`SingleDecodeType`](../singledecodetype/) प्रकार,String कोडटेक्स्ट, [`BarCodeRegionParameters`](../barcoderegionparameters/) क्षेत्र और अन्य पैरामीटर

```csharp
public sealed class BarCodeResult : ICloneable, IEquatable<BarCodeResult>
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [BarCodeResult](barcoderesult/)(BarCodeResult) | की एक प्रति बनाता है`BarCodeResult` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [CodeBytes](../../aspose.barcode.barcoderecognition/barcoderesult/codebytes/) { get; } | एन्कोडेड कोड बाइट प्राप्त करता है |
| [CodeText](../../aspose.barcode.barcoderecognition/barcoderesult/codetext/) { get; } | कोड पाठ प्राप्त करता है |
| [CodeType](../../aspose.barcode.barcoderecognition/barcoderesult/codetype/) { get; } | बारकोड प्रकार प्राप्त करता है |
| [CodeTypeName](../../aspose.barcode.barcoderecognition/barcoderesult/codetypename/) { get; } | बारकोड प्रकार का नाम प्राप्त करता है |
| [Confidence](../../aspose.barcode.barcoderecognition/barcoderesult/confidence/) { get; } | मान्यता प्राप्त बारकोड का मान्यता आत्मविश्वास स्तर प्राप्त करता है |
| [Extended](../../aspose.barcode.barcoderecognition/barcoderesult/extended/) { get; } | मान्यता प्राप्त बारकोड के विस्तारित पैरामीटर प्राप्त करता है |
| [ReadingQuality](../../aspose.barcode.barcoderecognition/barcoderesult/readingquality/) { get; } | पढ़ने की गुणवत्ता प्राप्त करता है। 1D और पोस्टल बारकोड के लिए काम करता है। |
| [Region](../../aspose.barcode.barcoderecognition/barcoderesult/region/) { get; } | बारकोड क्षेत्र प्राप्त करता है |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [Clone](../../aspose.barcode.barcoderecognition/barcoderesult/clone/)() | की प्रतिलिपि बनाता है`BarCodeResult` वर्ग. |
| [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals)(BarCodeResult) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट के बराबर है या नहीं`BarCodeResult` मान. |
| override [Equals](../../aspose.barcode.barcoderecognition/barcoderesult/equals/#equals_1)(object) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट के बराबर है या नहीं`BarCodeResult` मान. |
| [GetCodeText](../../aspose.barcode.barcoderecognition/barcoderesult/getcodetext/)(Encoding) | एन्कोडिंग के साथ कोड टेक्स्ट प्राप्त करता है। |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/barcoderesult/gethashcode/)() | इस उदाहरण के लिए हैश कोड लौटाता है। |
| override [ToString](../../aspose.barcode.barcoderecognition/barcoderesult/tostring/)() | इसका एक मानव-पठनीय स्ट्रिंग प्रतिनिधित्व देता है`BarCodeResult` . |
| [operator ==](../../aspose.barcode.barcoderecognition/barcoderesult/op_equality/) | एक मान लौटाता है जो दर्शाता है कि पहला है या नहीं`BarCodeResult` मान दूसरे के बराबर है. |
| [operator !=](../../aspose.barcode.barcoderecognition/barcoderesult/op_inequality/) | एक मान लौटाता है जो दर्शाता है कि यह पहला है या नहीं`BarCodeResult` मान दूसरे से अलग है. |

### उदाहरण

यह नमूना दिखाता है कि BarCodeResult कैसे प्राप्त करें।

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
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
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
        Console.WriteLine("BarCode Angle: " + result.Region.Angle)
    Next
End Using
```

### यह सभी देखें

* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* सभा [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->