---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext क्लास"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext क्लास। HIBC LIC कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए बेस क्लास C++ में।"
type: docs
weight: 800
url: /hi/cpp/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class


HIBC LIC कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए बेस क्लास।

```cpp
class HIBCLICComplexCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_BarcodeType](./get_barcodetype/)() const | बारकोड प्रकार प्राप्त करता है। HIBC LIC कोडटेक्स्ट को HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC और HIBCQRLIC एन्कोड प्रकारों का उपयोग करके एन्कोड किया जा सकता है। डिफ़ॉल्ट मान: HIBCCode39LIC। |
| [GetBarcodeType](./getbarcodetype/)() override | बारकोड प्रकार प्राप्त करता है। |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | कोडटेक्स्ट बनाता है |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/)() |  |
| virtual [InitFromString](./initfromstring/)(System::String) | निर्मित कोडटेक्स्ट से इंस्टेंस को इनिशियलाइज़ करता है। |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | बारकोड प्रकार सेट करता है। HIBC LIC कोडटेक्स्ट को HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC और HIBCQRLIC एन्कोड प्रकारों का उपयोग करके एन्कोड किया जा सकता है। डिफ़ॉल्ट मान: HIBCCode39LIC। |
## टिप्पणियाँ


यह उदाहरण दिखाता है कि कैसे कच्चे HIBC LIC कोडटेक्स्ट को [HIBCLICComplexCodetext](./) उदाहरण में डिकोड किया जाए।
```cpp
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

## और देखें

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
