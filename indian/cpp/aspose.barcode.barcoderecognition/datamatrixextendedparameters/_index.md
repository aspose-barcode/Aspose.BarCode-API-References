---
title: "Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters क्लास"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters क्लास। C++ में DataMatrix पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है।"
type: docs
weight: 1500
url: /hi/cpp/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class


[DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है

```cpp
class DataMatrixExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिककरण या बारकोड रीडर के पुनःप्रोग्रामिंग के निर्देशों के रूप में व्याख्या करने के लिए किया जाता है या नहीं। डिफ़ॉल्ट मान false है। |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) स्ट्रक्चर्ड अपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान -1 है। |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) स्ट्रक्चर्ड अपेंड मोड बारकोड की गिनती प्राप्त करता है। डिफ़ॉल्ट मान -1 है। गिनती 1 से 35 के बीच होनी चाहिए। |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) स्ट्रक्चर्ड अपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान -1 है। |
| [GetHashCode](./gethashcode/)() const override | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [ToString](./tostring/)() const override | इस [DataMatrixExtendedParameters](./) का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
## टिप्पणियाँ


यह उदाहरण दिखाता है कि कैसे [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) के कच्चे मान प्राप्त किए जाएँ
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

## और देखें

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
