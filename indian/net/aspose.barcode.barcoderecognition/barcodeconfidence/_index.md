---
title: "एनम BarCodeConfidence"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.BarCodeRecognition.BarCodeConfidence एनम। पहचान विश्वास स्तर को सम्मिलित करता है"
type: docs
weight: 50
url: /hi/net/aspose.barcode.barcoderecognition/barcodeconfidence/
---
## BarCodeConfidence enumeration

मान्यता विश्वास स्तर को शामिल करता है

```csharp
public enum BarCodeConfidence
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| None | `0` | बारकोड की पहचान विश्वास जहाँ कोडटेक्स्ट सही ढंग से पहचाना नहीं गया या बारकोड को संभावित नकली के रूप में पहचाना गया |
| Moderate | `80` | बारकोड (मुख्यतः 1D बारकोड) की पहचान विश्वास जिसमें कमजोर चेकसम या बिना चेकसम के हो। यदि यह कम हो तो कोडटेक्स्ट में कुछ गलत पहचान या नकली पहचान हो सकती है |
| Strong | `100` | पहचान विश्वास जिसे Reed–Solomon जैसे BCH कोड्स से पुष्टि की गई है। पढ़े गए कोडटेक्स्ट में त्रुटियां या नकली पहचान नहीं होनी चाहिए |

## उदाहरण

यह उदाहरण दिखाता है कि BarCodeConfidence कैसे बदलता है, बारकोड प्रकार पर निर्भर करता है

```csharp
[C#]
//मध्यम विश्वास
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
    }
}

//मजबूत विश्वास
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Confidence: " + result.Confidence);
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality);
    }
}
[VB.NET]
'Moderate confidence
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using

'Strong confidence
Using generator As New BarcodeGenerator(EncodeTypes.QR, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Confidence: " + result.Confidence)
        Console.WriteLine("BarCode ReadingQuality: " + result.ReadingQuality)
    Next
End Using
```

### और देखें

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


