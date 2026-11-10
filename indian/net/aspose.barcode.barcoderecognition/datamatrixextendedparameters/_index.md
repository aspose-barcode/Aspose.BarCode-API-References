---
title: "क्लास DataMatrixExtendedParameters"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "`Aspose.BarCode.BarCodeRecognition.DataMatrixExtendedParameters` क्लास। मान्यता प्राप्त DataMatrix बारकोड के विशेष डेटा संग्रहीत करता है।"
type: docs
weight: 220
url: /hi/net/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class

DataMatrix पहचाने गए बारकोड का विशेष डेटा संग्रहीत करता है

```csharp
public sealed class DataMatrixExtendedParameters : BaseExtendedParameters
```

## गुण

| नाम | विवरण |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | जाँचता है कि क्या सभी पैरामीटर केवल डिफ़ॉल्ट मान रखते हैं। |
| [IsReaderProgramming](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/isreaderprogramming/) { get; } | यह दर्शाता है कि कोड का उपयोग रीडर को निम्न डेटा को प्रारंभिककरण या बारकोड रीडर के पुनःप्रोग्रामिंग के निर्देश के रूप में व्याख्या करने के लिए किया जाता है या नहीं। डिफ़ॉल्ट मान false है। |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodeid/) { get; } | DataMatrix संरचित जोड़ मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान -1 है। |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodescount/) { get; } | DataMatrix संरचित जोड़ मोड बारकोड की संख्या प्राप्त करता है। डिफ़ॉल्ट मान -1 है। संख्या 1 से 35 के बीच होनी चाहिए। |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendfileid/) { get; } | DataMatrix संरचित जोड़ मोड बारकोड का ID प्राप्त करता है। ID 1 से शुरू होती है और बारकोड की संख्या से कम या बराबर होनी चाहिए। डिफ़ॉल्ट मान -1 है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/equals/)(object) | यह उदाहरण निर्दिष्ट `DataMatrixExtendedParameters` मान के बराबर होने को दर्शाने वाला मान लौटाता है। |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/gethashcode/)() | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| override [ToString](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/tostring/)() | इस `DataMatrixExtendedParameters` की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [operator ==](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_equality/) | पहले `DataMatrixExtendedParameters` मान के दूसरे के बराबर होने का संकेत देने वाला मान लौटाता है। |
| [operator !=](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_inequality/) | पहले `DataMatrixExtendedParameters` मान के दूसरे से भिन्न होने का संकेत देने वाला मान लौटाता है। |

## उदाहरण

यह उदाहरण दिखाता है कि DataMatrix कच्चे मान कैसे प्राप्त करें

```csharp
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

### और देखें

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


