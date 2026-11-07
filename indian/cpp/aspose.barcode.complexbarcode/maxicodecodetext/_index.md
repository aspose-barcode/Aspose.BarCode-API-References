---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext क्लास"
linktitle: "MaxiCodeCodetext"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext क्लास। MaxiCode कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए बेस क्लास C++ में।"
type: docs
weight: 1600
url: /hi/cpp/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class


MaxiCode कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए बेस क्लास.

```cpp
class MaxiCodeCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | ECI एन्कोडिंग प्राप्त करता है। जब MaxiCodeEncodeMode ऑटो हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | MaxiCode एन्कोड मोड प्राप्त करता है। डिफ़ॉल्ट मान: ऑटो। |
| [GetBarcodeType](./getbarcodetype/)() override | बारकोड प्रकार प्राप्त करता है। |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | कोडटेक्स्ट बनाता है |
| virtual [GetMode](./getmode/)() const | MaxiCode मोड प्राप्त करता है। |
| virtual [InitFromString](./initfromstring/)(System::String) | निर्मित कोडटेक्स्ट से इंस्टेंस को इनिशियलाइज़ करता है। |
| [MaxiCodeCodetext](./maxicodecodetext/)() |  |
| [set_ECIEncoding](./set_eciencoding/)(Generation::ECIEncodings) | ECI एन्कोडिंग सेट करता है। जब MaxiCodeEncodeMode ऑटो हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(Generation::MaxiCodeEncodeMode) | MaxiCode एन्कोड मोड सेट करता है। डिफ़ॉल्ट मान: ऑटो। |
## टिप्पणियाँ


यह उदाहरण दर्शाता है कि कैसे कच्चे MaxiCode कोडटेक्स्ट को [MaxiCodeCodetext](./) इंस्टेंस में डिकोड किया जाता है।
```cpp
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

## और देखें

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
