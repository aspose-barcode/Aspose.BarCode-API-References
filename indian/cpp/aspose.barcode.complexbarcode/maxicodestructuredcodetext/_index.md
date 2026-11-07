---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext क्लास"
linktitle: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext क्लास. C++ में मोड 2 और 3 के लिए MaxiCode कोड में एम्बेड किए गए टेक्स्ट को एन्कोड और डिकोड करने के लिए बेस क्लास।"
type: docs
weight: 2200
url: /hi/cpp/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---
## MaxiCodeStructuredCodetext class


मोड 2 और 3 के लिए MaxiCode कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए बेस क्लास.

```cpp
class MaxiCodeStructuredCodetext : public Aspose::BarCode::ComplexBarcode::MaxiCodeCodetext
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [MaxiCodeStructuredCodetext](./) मान के बराबर है या नहीं। |
| [get_CountryCode](./get_countrycode/)() const | 3 अंकों वाला देश कोड पहचानता है। |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | ECI एन्कोडिंग प्राप्त करता है। जब MaxiCodeEncodeMode ऑटो हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | MaxiCode एन्कोड मोड प्राप्त करता है। डिफ़ॉल्ट मान: ऑटो। |
| [get_PostalCode](./get_postalcode/)() const | डाक कोड पहचानता है। मोड 2 में 9 अंकों या मोड 3 में 6 अल्फ़ान्यूमेरिक प्रतीकों का होना आवश्यक है। |
| [get_SecondMessage](./get_secondmessage/)() const | बारकोड का दूसरा संदेश पहचानता है। |
| [get_ServiceCategory](./get_servicecategory/)() const | 3 अंकों वाली सेवा श्रेणी पहचानता है। |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | बारकोड प्रकार प्राप्त करता है। |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | कोडटेक्स्ट बनाता है |
| [GetHashCode](./gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| virtual [GetMode](../maxicodecodetext/getmode/)() const | MaxiCode मोड प्राप्त करता है। |
| [InitFromString](./initfromstring/)(System::String) override | निर्मित कोडटेक्स्ट से इंस्टेंस को इनिशियलाइज़ करता है। |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/)() |  |
| [set_CountryCode](./set_countrycode/)(int32_t) | 3 अंकों वाला देश कोड पहचानता है। |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | ECI एन्कोडिंग सेट करता है। जब MaxiCodeEncodeMode ऑटो हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | MaxiCode एन्कोड मोड सेट करता है। डिफ़ॉल्ट मान: ऑटो। |
| [set_PostalCode](./set_postalcode/)(System::String) | डाक कोड पहचानता है। मोड 2 में 9 अंकों या मोड 3 में 6 अल्फ़ान्यूमेरिक प्रतीकों का होना आवश्यक है। |
| [set_SecondMessage](./set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | बारकोड का दूसरा संदेश पहचानता है। |
| [set_ServiceCategory](./set_servicecategory/)(int32_t) | 3 अंकों वाली सेवा श्रेणी पहचानता है। |
## टिप्पणियाँ


यह उदाहरण दिखाता है कि कैसे कच्चे MaxiCode कोडटेक्स्ट को [MaxiCodeStructuredCodetext](./) इंस्टेंस में डिकोड किया जाए।
```cpp
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

## और देखें

* Class [MaxiCodeCodetext](../maxicodecodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
