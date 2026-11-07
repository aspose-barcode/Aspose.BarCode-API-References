---
title: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext क्लास"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext क्लास। C++ में HIBC PAS कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।"
type: docs
weight: 1100
url: /hi/cpp/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class


HIBC PAS कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।

```cpp
class HIBCPASCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [AddRecord](./addrecord/)(HIBCPASDataType, System::String) | नया रिकॉर्ड जोड़ता है |
| [AddRecord](./addrecord/)(System::SharedPtr\<HIBCPASRecord\>) | नया रिकॉर्ड जोड़ता है |
| [Clear](./clear/)() | रिकॉर्ड सूची को साफ़ करता है |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [HIBCPASCodetext](./) मान के बराबर है या नहीं। |
| [get_BarcodeType](./get_barcodetype/)() const | बारकोड प्रकार प्राप्त करता है। HIBC PAS कोडटेक्स्ट को HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS और HIBCQRPAS एन्कोड प्रकारों का उपयोग करके एन्कोड किया जा सकता है। डिफ़ॉल्ट मान: HIBCCode39PAS। |
| [get_DataLocation](./get_datalocation/)() const | डेटा स्थान की पहचान करता है। |
| [GetBarcodeType](./getbarcodetype/)() override | बारकोड प्रकार प्राप्त करता है। |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | कोडटेक्स्ट बनाता है |
| [GetHashCode](./gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [GetRecords](./getrecords/)() | रिकॉर्ड सूची प्राप्त करता है |
| [HIBCPASCodetext](./hibcpascodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | निर्मित कोडटेक्स्ट से इंस्टेंस को इनिशियलाइज़ करता है। |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | बारकोड प्रकार सेट करता है। HIBC PAS कोडटेक्स्ट को HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS और HIBCQRPAS एन्कोड प्रकारों का उपयोग करके एन्कोड किया जा सकता है। डिफ़ॉल्ट मान: HIBCCode39PAS। |
| [set_DataLocation](./set_datalocation/)(HIBCPASDataLocation) | डेटा स्थान की पहचान करता है। |
## टिप्पणियाँ


यह उदाहरण दिखाता है कि कैसे [HIBCPASCodetext](./) का उपयोग करके HIBC PAS को एन्कोड और डिकोड किया जाता है।
```cpp
[C#]
HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
complexCodetext.DataLocation = HIBCPASDataLocation.Patient;
complexCodetext.AddRecord(HIBCPASDataType.LabelerIdentificationCode, "A123");
complexCodetext.AddRecord(HIBCPASDataType.ManufacturerSerialNumber, "SERIAL123");
complexCodetext.BarcodeType = EncodeTypes.HIBCDataMatrixPAS;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.HIBCDataMatrixPAS))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
            HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.TryDecodeHIBCPAS(codetext);
        Console.WriteLine("Data location: {0}", readCodetext.DataLocation);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[0].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[0].Data);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[1].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[1].Data);

    }
}
```

## और देखें

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
