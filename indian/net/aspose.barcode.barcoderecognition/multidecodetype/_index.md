---
title: "क्लास MultiDecodeType"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.BarCodeRecognition.MultiDecodeType क्लास। संयुक्त डिकोड प्रकार"
type: docs
weight: 320
url: /hi/net/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class

संयुक्त डिकोड प्रकार।

```csharp
public class MultiDecodeType : BaseDecodeType, IEquatable<MultiDecodeType>
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [MultiDecodeType](multidecodetype/#constructor)(params BaseDecodeType[]) | `MultiDecodeType` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [MultiDecodeType](multidecodetype/#constructor_1)(params SingleDecodeType[]) | `MultiDecodeType` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [GetSingleTypesCount](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypescount/) { get; } | एकल प्रकारों की संख्या लौटाता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Add](../../aspose.barcode.barcoderecognition/multidecodetype/add/)(SingleDecodeType) | MultiDecodeType में एक और [`SingleDecodeType`](../singledecodetype/) जोड़ता है। |
| [ContainsAll](../../aspose.barcode.barcoderecognition/multidecodetype/containsall/)(params BaseDecodeType[]) | जाँचें कि क्या यह बारकोड प्रकारों से सभी प्रकारों को शामिल करता है। |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/multidecodetype/containsany/)(params BaseDecodeType[]) | क्या यह किसी भी प्रकार को शामिल करता है |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [`BaseDecodeType`](../basedecodetype/) मान के बराबर है या नहीं। |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_1)(MultiDecodeType) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट `MultiDecodeType` मान के बराबर है या नहीं। |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_3)(object) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट `MultiDecodeType` मान के बराबर है या नहीं। |
| override [Equals](../../aspose.barcode.barcoderecognition/multidecodetype/equals/#equals_2)(SingleDecodeType) | एक मान लौटाता है जो दर्शाता है कि यह डिकोड प्रकार संग्रह केवल निर्दिष्ट [`SingleDecodeType`](../singledecodetype/) मान को ही शामिल करता है। |
| [Exclude](../../aspose.barcode.barcoderecognition/multidecodetype/exclude/)(SingleDecodeType) | `MultiDecodeType` से [`SingleDecodeType`](../singledecodetype/) को बाहर करता है और नया MultiDecodeType इंस्टेंस लौटाता है। |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/multidecodetype/gethashcode/)() | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [GetSingleTypes](../../aspose.barcode.barcoderecognition/multidecodetype/getsingletypes/)() | एकल प्रकारों की सूची का प्रतिनिधित्व करता है। |
| override [ToString](../../aspose.barcode.barcoderecognition/multidecodetype/tostring/)() | MultiDecodeType को स्ट्रिंग के रूप में दर्शाने वाला ओवरराइड किया गया मेथड। |
| static [TryParse](../../aspose.barcode.barcoderecognition/multidecodetype/tryparse/)(string, out MultiDecodeType) | MultiDecodeType की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। एक रिटर्न वैल्यू दर्शाता है कि रूपांतरण सफल हुआ या विफल। |

## उदाहरण

यह उदाहरण दिखाता है कि कैसे संयोजन MultiDecode प्रकार बनाएँ जो SingleDecodeType और MultiDecode प्रकारों को मिलाते हैं।

```csharp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType 
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

### और देखें

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


