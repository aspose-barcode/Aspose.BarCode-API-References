---
title: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode2 क्लास"
linktitle: "MaxiCodeCodetextMode2"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::ComplexBarcode::MaxiCodeCodetextMode2 क्लास. C++ में मोड 2 के लिए MaxiCode कोड में एम्बेड किए गए टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।"
type: docs
weight: 1700
url: /hi/cpp/aspose.barcode.complexbarcode/maxicodecodetextmode2/
---
## MaxiCodeCodetextMode2 class


मोड 2 के लिए MaxiCode कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास.

```cpp
class MaxiCodeCodetextMode2 : public Aspose::BarCode::ComplexBarcode::MaxiCodeStructuredCodetext
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [Equals](../maxicodestructuredcodetext/equals/)(System::SharedPtr\<System::Object\>) override | एक मान लौटाता है जो यह दर्शाता है कि यह इंस्टेंस निर्दिष्ट [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/) मान के बराबर है या नहीं। |
| [get_CountryCode](../maxicodestructuredcodetext/get_countrycode/)() const | 3 अंकों वाला देश कोड पहचानता है। |
| [get_ECIEncoding](../maxicodecodetext/get_eciencoding/)() const | ECI एन्कोडिंग प्राप्त करता है। जब MaxiCodeEncodeMode ऑटो हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [get_EncodeMode](../maxicodecodetext/get_encodemode/)() const | MaxiCode एन्कोड मोड प्राप्त करता है। डिफ़ॉल्ट मान: ऑटो। |
| [get_PostalCode](../maxicodestructuredcodetext/get_postalcode/)() const | डाक कोड पहचानता है। मोड 2 में 9 अंकों या मोड 3 में 6 अल्फ़ान्यूमेरिक प्रतीकों का होना आवश्यक है। |
| [get_SecondMessage](../maxicodestructuredcodetext/get_secondmessage/)() const | बारकोड का दूसरा संदेश पहचानता है। |
| [get_ServiceCategory](../maxicodestructuredcodetext/get_servicecategory/)() const | 3 अंकों वाली सेवा श्रेणी पहचानता है। |
| [GetBarcodeType](../maxicodecodetext/getbarcodetype/)() override | बारकोड प्रकार प्राप्त करता है। |
| [GetConstructedCodetext](../maxicodestructuredcodetext/getconstructedcodetext/)() override | कोडटेक्स्ट बनाता है |
| [GetHashCode](../maxicodestructuredcodetext/gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [GetMode](./getmode/)() const override | MaxiCode मोड प्राप्त करता है। |
| [InitFromString](../maxicodestructuredcodetext/initfromstring/)(System::String) override | निर्मित कोडटेक्स्ट से इंस्टेंस को इनिशियलाइज़ करता है। |
| [MaxiCodeCodetext](../maxicodecodetext/maxicodecodetext/)() |  |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/)() |  |
| [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/maxicodestructuredcodetext/)() |  |
| [set_CountryCode](../maxicodestructuredcodetext/set_countrycode/)(int32_t) | 3 अंकों वाला देश कोड पहचानता है। |
| [set_ECIEncoding](../maxicodecodetext/set_eciencoding/)(Generation::ECIEncodings) | ECI एन्कोडिंग सेट करता है। जब MaxiCodeEncodeMode ऑटो हो तो उपयोग किया जाता है। डिफ़ॉल्ट मान: ISO-8859-1 |
| [set_EncodeMode](../maxicodecodetext/set_encodemode/)(Generation::MaxiCodeEncodeMode) | MaxiCode एन्कोड मोड सेट करता है। डिफ़ॉल्ट मान: ऑटो। |
| [set_PostalCode](../maxicodestructuredcodetext/set_postalcode/)(System::String) | डाक कोड पहचानता है। मोड 2 में 9 अंकों या मोड 3 में 6 अल्फ़ान्यूमेरिक प्रतीकों का होना आवश्यक है। |
| [set_SecondMessage](../maxicodestructuredcodetext/set_secondmessage/)(System::SharedPtr\<MaxiCodeSecondMessage\>) | बारकोड का दूसरा संदेश पहचानता है। |
| [set_ServiceCategory](../maxicodestructuredcodetext/set_servicecategory/)(int32_t) | 3 अंकों वाली सेवा श्रेणी पहचानता है। |
## टिप्पणियाँ


यह नमूना दिखाता है कि मोड 2 के लिए MaxiCode कोडटेक्स्ट को कैसे एन्कोड और डिकोड किया जाता है।
```cpp
[C#]
//मोड 2 के साथ मानक दूसरा संदेश
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//मोड 2 के साथ संरचित दूसरा संदेश
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//मानक दूसरे संदेश के साथ कच्चे कोडटेक्स्ट का डिकोडिंग
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode2){
            MaxiCodeCodetextMode2 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode2)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
            if (maxiCodeStructuredCodetext.SecondMessage is MaxiCodeStandardSecondMessage){
                MaxiCodeStandardSecondMessage secondMessage = (MaxiCodeStandardSecondMessage)maxiCodeStructuredCodetext.SecondMessage;
                Console.WriteLine("Message: " + secondMessage.Message);
            }
        }
    }
}
//संरचित दूसरे संदेश के साथ कच्चे कोडटेक्स्ट का डिकोडिंग
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        if (resultMaxiCodeCodetext is MaxiCodeCodetextMode2){
            MaxiCodeCodetextMode2 maxiCodeStructuredCodetext = (MaxiCodeCodetextMode2)resultMaxiCodeCodetext;
            Console.WriteLine("BarCode Type: " + maxiCodeStructuredCodetext.PostalCode);
            Console.WriteLine("MaxiCode mode: " + maxiCodeStructuredCodetext.CountryCode);
            Console.WriteLine("BarCode CodeText: " + maxiCodeStructuredCodetext.ServiceCategory);
            if (maxiCodeStructuredCodetext.SecondMessage is MaxiCodeStructuredSecondMessage){
                MaxiCodeStructuredSecondMessage secondMessage = (MaxiCodeStructuredSecondMessage)maxiCodeStructuredCodetext.SecondMessage;
                Console.WriteLine("Message:");
                foreach (var identifier in secondMessage.Identifiers){
                    Console.WriteLine(identifier);
                }
            }
        }
    }
}
```

## और देखें

* Class [MaxiCodeStructuredCodetext](../maxicodestructuredcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
