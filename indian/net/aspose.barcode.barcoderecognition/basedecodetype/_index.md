---
title: "क्लास BaseDecodeType"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.BarCodeRecognition.BaseDecodeType क्लास। MultiDecodeType और SingleDecodeType के लिए बेस क्लास"
type: docs
weight: 130
url: /hi/net/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class

MultiDecodeType और SingleDecodeType के लिए बेस क्लास।

```csharp
public abstract class BaseDecodeType : IEquatable<BaseDecodeType>
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| abstract [ContainsAny](../../aspose.barcode.barcoderecognition/basedecodetype/containsany/)(params BaseDecodeType[]) | निर्धारित करता है कि दिए गए डिकोड प्रकारों में से कोई भी शामिल है या नहीं |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals)(BaseDecodeType) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट `BaseDecodeType` मान के बराबर है या नहीं। |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_1)(MultiDecodeType) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [`MultiDecodeType`](../multidecodetype/) मान के बराबर है या नहीं। |
| override [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_3)(object) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट `BaseDecodeType` मान के बराबर है या नहीं। |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/#equals_2)(SingleDecodeType) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [`SingleDecodeType`](../singledecodetype/) मान के बराबर है या नहीं। |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/basedecodetype/gethashcode/)() | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse)(string, out BaseDecodeType) | BaseDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है, ठोस प्रकार निर्धारित करने के बाद। एक रिटर्न वैल्यू दर्शाता है कि रूपांतरण सफल हुआ या विफल। |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_1)(string, out MultiDecodeType) | MultiDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू दर्शाता है कि रूपांतरण सफल हुआ या विफल। |
| static [TryParse](../../aspose.barcode.barcoderecognition/basedecodetype/tryparse/#tryparse_2)(string, out SingleDecodeType) | SingleDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू दर्शाता है कि रूपांतरण सफल हुआ या विफल। |

## उदाहरण

यह उदाहरण दिखाता है कि BaseDecodeType को SingleDecodeType और MultiDecodeType के साथ कैसे उपयोग किया जाए

```csharp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

### और देखें

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


