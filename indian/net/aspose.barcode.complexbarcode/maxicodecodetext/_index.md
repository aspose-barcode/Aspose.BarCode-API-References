---
title: "क्लास MaxiCodeCodetext"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.ComplexBarcode.MaxiCodeCodetext क्लास। MaxiCode कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए बेस क्लास"
type: docs
weight: 680
url: /hi/net/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class

MaxiCode कोड में एम्बेड किए गए टेक्स्ट को एन्कोड और डिकोड करने के लिए बेस क्लास।

```csharp
public abstract class MaxiCodeCodetext : IComplexCodetext
```

## गुण

| नाम | विवरण |
| --- | --- |
| [ECIEncoding](../../aspose.barcode.complexbarcode/maxicodecodetext/eciencoding/) { get; set; } | ECI एन्कोडिंग को प्राप्त करता है या सेट करता है। जब MaxiCodeEncodeMode ऑटो हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.complexbarcode/maxicodecodetext/encodemode/) { get; set; } | MaxiCode एन्कोड मोड को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: Auto. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/maxicodecodetext/getbarcodetype/)() | बारकोड प्रकार को प्राप्त करता है। |
| abstract [GetConstructedCodetext](../../aspose.barcode.complexbarcode/maxicodecodetext/getconstructedcodetext/)() | कोडटेक्स्ट बनाता है। |
| abstract [GetMode](../../aspose.barcode.complexbarcode/maxicodecodetext/getmode/)() | MaxiCode मोड प्राप्त करता है। |
| abstract [InitFromString](../../aspose.barcode.complexbarcode/maxicodecodetext/initfromstring/)(string) | निर्मित कोडटेक्स्ट से इंस्टेंस को प्रारंभ करता है। |

## उदाहरण

यह उदाहरण दिखाता है कि कच्चे MaxiCode कोडटेक्स्ट को MaxiCodeCodetext इंस्टेंस में कैसे डिकोड किया जाए।

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

### और देखें

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


