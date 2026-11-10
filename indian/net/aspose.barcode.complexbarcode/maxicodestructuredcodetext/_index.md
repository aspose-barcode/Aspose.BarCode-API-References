---
title: "क्लास MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.ComplexBarcode.MaxiCodeStructuredCodetext क्लास। मोड 2 और 3 के लिए MaxiCode कोड में एम्बेड किए गए टेक्स्ट को एन्कोड और डिकोड करने के लिए बेस क्लास"
type: docs
weight: 740
url: /hi/net/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class

मोड 2 और 3 के लिए MaxiCode कोड में एम्बेड किए गए टेक्स्ट को एन्कोड और डिकोड करने के लिए बेस क्लास।

```csharp
public abstract class MaxiCodeStructuredCodetext : MaxiCodeCodetext
```

## गुण

| नाम | विवरण |
| --- | --- |
| [CountryCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/countrycode/) { get; set; } | 3 अंकों का देश कोड पहचानता है। |
| [ECIEncoding](../../aspose.barcode.complexbarcode/maxicodecodetext/eciencoding/) { get; set; } | ECI एन्कोडिंग को प्राप्त करता है या सेट करता है। जब MaxiCodeEncodeMode ऑटो हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.complexbarcode/maxicodecodetext/encodemode/) { get; set; } | MaxiCode एन्कोड मोड को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: Auto. |
| [PostalCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/postalcode/) { get; set; } | डाक कोड की पहचान करता है। मोड 2 में 9 अंक या मोड 3 में 6 अल्फ़ान्यूमेरिक प्रतीक होना चाहिए। |
| [SecondMessage](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/secondmessage/) { get; set; } | बारकोड के दूसरे संदेश की पहचान करता है। |
| [ServiceCategory](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/servicecategory/) { get; set; } | 3 अंकों की सेवा श्रेणी की पहचान करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/equals/)(object) | `MaxiCodeStructuredCodetext` मान के साथ यह इंस्टेंस समान है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/maxicodecodetext/getbarcodetype/)() | बारकोड प्रकार को प्राप्त करता है। |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/getconstructedcodetext/)() | कोडटेक्स्ट बनाता है। |
| override [GetHashCode](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/gethashcode/)() | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| abstract [GetMode](../../aspose.barcode.complexbarcode/maxicodecodetext/getmode/)() | MaxiCode मोड प्राप्त करता है। |
| override [InitFromString](../../aspose.barcode.complexbarcode/maxicodestructuredcodetext/initfromstring/)(string) | निर्मित कोडटेक्स्ट से इंस्टेंस को प्रारंभ करता है। |

## उदाहरण

यह उदाहरण दिखाता है कि कच्चे MaxiCode कोडटेक्स्ट को MaxiCodeStructuredCodetext इंस्टेंस में कैसे डिकोड किया जाए।

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeStructuredCodetext){
            MaxiCodeStructuredCodetext maxiCodeStructuredCodetext = (MaxiCodeStructuredCodetext)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
        }
    }
}
```

### और देखें

* class [MaxiCodeCodetext](../maxicodecodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


