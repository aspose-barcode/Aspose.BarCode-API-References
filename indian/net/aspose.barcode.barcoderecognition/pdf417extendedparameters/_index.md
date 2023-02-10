---
title: Pdf417ExtendedParameters
second_title: Aspose.BarCode .NET API संदर्भ के लिए
description: मन्यत प्रप्त बरकड क MacroPdf417 मेटडेट जनकर संग्रहत करत है
type: docs
weight: 240
url: /hi/net/aspose.barcode.barcoderecognition/pdf417extendedparameters/
---
## Pdf417ExtendedParameters class

मान्यता प्राप्त बारकोड की MacroPdf417 मेटाडेटा जानकारी संग्रहीत करता है

```csharp
public sealed class Pdf417ExtendedParameters : BaseExtendedParameters
```

## गुण

| नाम | विवरण |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | परीक्षण करता है कि सभी पैरामीटर में केवल डिफ़ॉल्ट मान हैं या नहीं |
| [MacroPdf417Addressee](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417addressee/) { get; } | मैक्रो PDF417 पता पाने वाले का नाम (वैकल्पिक)। |
| [MacroPdf417Checksum](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417checksum/) { get; } | मैक्रो PDF417 चेकसम (वैकल्पिक)। |
| [MacroPdf417FileID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417fileid/) { get; } | बारकोड की फ़ाइल आईडी प्राप्त करता है, जो केवल MacroPdf417 के साथ उपलब्ध है। |
| [MacroPdf417FileName](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filename/) { get; } | मैक्रो PDF417 फ़ाइल नाम (वैकल्पिक)। |
| [MacroPdf417FileSize](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417filesize/) { get; } | मैक्रो PDF417 फ़ाइल आकार (वैकल्पिक)। |
| [MacroPdf417SegmentID](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentid/) { get; } | बारकोड का सेगमेंट आईडी प्राप्त करता है, जो केवल MacroPdf417 के साथ उपलब्ध है। |
| [MacroPdf417SegmentsCount](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417segmentscount/) { get; } | मैक्रो pdf417 बारकोड सेगमेंट काउंट प्राप्त करता है। डिफ़ॉल्ट मान -1 है। |
| [MacroPdf417Sender](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417sender/) { get; } | मैक्रो PDF417 प्रेषक का नाम (वैकल्पिक)। |
| [MacroPdf417Terminator](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417terminator/) { get; } | इंगित करता है कि खंड मैक्रो PDF417 फ़ाइल का अंतिम खंड है या नहीं। |
| [MacroPdf417TimeStamp](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/macropdf417timestamp/) { get; } | मैक्रो PDF417 टाइम स्टैम्प (वैकल्पिक)। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/equals/)(object) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट के बराबर है या नहीं`Pdf417ExtendedParameters` मान. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/gethashcode/)() | इस उदाहरण के लिए हैश कोड लौटाता है। |
| override [ToString](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/tostring/)() | इसका एक मानव-पठनीय स्ट्रिंग प्रतिनिधित्व देता है`Pdf417ExtendedParameters` . |
| [operator ==](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_equality/) | एक मान लौटाता है जो दर्शाता है कि पहला है या नहीं`Pdf417ExtendedParameters` मान दूसरे के बराबर है. |
| [operator !=](../../aspose.barcode.barcoderecognition/pdf417extendedparameters/op_inequality/) | एक मान लौटाता है जो दर्शाता है कि यह पहला है या नहीं`Pdf417ExtendedParameters` मान दूसरे से अलग है. |

### उदाहरण

यह नमूना दिखाता है कि मैक्रो Pdf417 मेटाडेटा कैसे प्राप्त करें

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345"))
{
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2;
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1;
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MacroPdf417))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID);
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount);
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.MacroPdf417, "12345")
    generator.Parameters.Barcode.Pdf417.Pdf417MacroFileID = 10
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentsCount = 2
    generator.Parameters.Barcode.Pdf417.Pdf417MacroSegmentID = 1
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.MacroPdf417)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Macro Pdf417 FileID: " + result.Extended.Pdf417.MacroPdf417FileID)
        Console.WriteLine("Macro Pdf417 Segments: " + result.Extended.Pdf417.MacroPdf417SegmentsCount)
        Console.WriteLine("Macro Pdf417 SegmentID: " + result.Extended.Pdf417.MacroPdf417SegmentID)
    Next
End Using
```

### यह सभी देखें

* class [BaseExtendedParameters](../baseextendedparameters/)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* सभा [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
