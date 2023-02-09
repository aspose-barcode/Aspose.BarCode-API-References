---
title: HIBCLICComplexCodetext
second_title: Aspose.BarCode .NET API संदर्भ के लिए
description: HIBC LIC कड में एम्बेड कए गए टेक्स्ट क एन्कडंग और डकड करने के लए बेस क्लस
type: docs
weight: 380
url: /hi/net/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class

HIBC LIC कोड में एम्बेड किए गए टेक्स्ट को एन्कोडिंग और डिकोड करने के लिए बेस क्लास।

```csharp
public abstract class HIBCLICComplexCodetext : IComplexCodetext
```

## गुण

| नाम | विवरण |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | बारकोड प्रकार प्राप्त या सेट करता है। HIBC LIC कोडटेक्स्ट को HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC और HIBCQRLIC एन्कोड प्रकारों का उपयोग करके एन्कोड किया जा सकता है। डिफ़ॉल्ट मान: HIBCCode39LIC. |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | बारकोड प्रकार प्राप्त करता है। |
| abstract [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getconstructedcodetext/)() | कोडटेक्स्ट बनाता है |
| abstract [InitFromString](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/initfromstring/)(string) | निर्मित कोडटेक्स्ट से उदाहरण आरंभ करता है। |

### उदाहरण

यह नमूना दिखाता है कि कच्चे HIBC एलआईसी कोडटेक्स्ट को HIBCLICComplexCodetext उदाहरण में कैसे डिकोड किया जाए।

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.HIBCAztecLIC))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        HIBCLICComplexCodetext resultHIBCLICComplexCodetext = ComplexCodetextReader.TryDecodeHIBCLIC(result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

### यह सभी देखें

* interface [IComplexCodetext](../icomplexcodetext/)
* नाम स्थान [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* सभा [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->