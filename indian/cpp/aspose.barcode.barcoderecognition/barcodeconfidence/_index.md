---
title: "enum"
linktitle: "BarCodeConfidence"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " enum. C++ में पहचान विश्वास स्तर शामिल है।"
type: docs
weight: 3500
url: /hi/cpp/aspose.barcode.barcoderecognition/barcodeconfidence/
---
## BarCodeConfidence enum


मान्यता विश्वास स्तर शामिल करता है।

```cpp
enum class BarCodeConfidence : int32_t
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| None | 0 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) वह विश्वास जहाँ कोडटेक्स्ट सही ढंग से पहचाना नहीं गया या बारकोड को संभावित नकली के रूप में पहचाना गया। |
|  | Moderate | 80 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) वह विश्वास (मुख्यतः 1D बारकोड) जिसमें कमजोर चेकसम या बिना चेकसम के हो। इसमें कोडटेक्स्ट में कुछ गलत पहचान या यहाँ तक कि नकली पहचान भी हो सकती है if |

कम है |
| Strong | 100 | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) वह विश्वास जो Reed–Solomon जैसे BCH कोड्स से पुष्टि किया गया है। पढ़े गए कोडटेक्स्ट में त्रुटियाँ या नकली पहचान नहीं होनी चाहिए। |

## टिप्पणियाँ


यह उदाहरण दर्शाता है कि BarCodeConfidence कैसे बदलता है, बारकोड प्रकार के आधार पर।
```cpp
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

## और देखें

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
