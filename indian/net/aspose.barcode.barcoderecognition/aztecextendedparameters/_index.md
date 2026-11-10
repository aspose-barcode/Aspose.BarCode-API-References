---
title: "क्लास AztecExtendedParameters"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.BarCodeRecognition.AztecExtendedParameters क्लास। Aztec पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है"
type: docs
weight: 40
url: /hi/net/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class

Aztec पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है

```csharp
public sealed class AztecExtendedParameters : BaseExtendedParameters
```

## गुण

| नाम | विवरण |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | जाँचता है कि क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं। |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/aztecextendedparameters/isreaderinitialization/) { get; } | यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिककरण या बारकोड रीडर के पुनःप्रोग्रामिंग के निर्देश के रूप में व्याख्या करने के लिए किया जाता है या नहीं। डिफ़ॉल्ट मान false है। |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodeid/) { get; } | Aztec संरचित एपेंड मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान 0 है। |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodescount/) { get; } | Aztec संरचित एपेंड मोड बारकोड की गिनती प्राप्त करता है। डिफ़ॉल्ट मान 0 है। गिनती 1 से 26 के बीच का मान होना चाहिए। |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendfileid/) { get; } | Aztec संरचित एपेंड मोड का फ़ाइल ID प्राप्त करता है। डिफ़ॉल्ट मान खाली स्ट्रिंग है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/aztecextendedparameters/equals/)(object) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट `AztecExtendedParameters` मान के बराबर है या नहीं। |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/aztecextendedparameters/gethashcode/)() | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| override [ToString](../../aspose.barcode.barcoderecognition/aztecextendedparameters/tostring/)() | इस `AztecExtendedParameters` की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [operator ==](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_equality/) | एक मान लौटाता है जो दर्शाता है कि पहला `AztecExtendedParameters` मान दूसरे के बराबर है या नहीं। |
| [operator !=](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_inequality/) | एक मान लौटाता है जो दर्शाता है कि पहला `AztecExtendedParameters` मान दूसरे से अलग है या नहीं। |

## उदाहरण

यह नमूना दिखाता है कि Aztec कच्चे मान कैसे प्राप्त करें

```csharp
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

### और देखें

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


