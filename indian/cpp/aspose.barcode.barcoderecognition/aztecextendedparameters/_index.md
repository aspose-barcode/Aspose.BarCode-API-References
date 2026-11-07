---
title: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters class"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters class. C++ में पहचाने गए Aztec बारकोड का विशेष डेटा संग्रहीत करता है।"
type: docs
weight: 300
url: /hi/cpp/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class


Aztec पहचाने गए बारकोड के विशेष डेटा को संग्रहीत करता है।

```cpp
class AztecExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिककरण या बारकोड रीडर के पुनःप्रोग्रामिंग के निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। डिफ़ॉल्ट मान false है। |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Aztec संरचित अपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान 0 है। |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Aztec संरचित अपेंड मोड बारकोड की गिनती प्राप्त करता है। डिफ़ॉल्ट मान 0 है। गिनती 1 से 26 के बीच का मान होना चाहिए। |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Aztec संरचित अपेंड मोड का फ़ाइल ID प्राप्त करता है। डिफ़ॉल्ट मान खाली स्ट्रिंग है। |
| [GetHashCode](./gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [ToString](./tostring/)() const override | इस [AztecExtendedParameters](./) का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
## टिप्पणियाँ


यह उदाहरण दिखाता है कि कैसे Aztec कच्चे मान प्राप्त किए जाएँ।
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

## और देखें

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
