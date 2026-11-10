---
title: "क्लास SingleDecodeType"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.BarCodeRecognition.SingleDecodeType क्लास। सिंगल डिकोड प्रकार। इंस्टेंस प्राप्त करने के लिए डिकोड प्रकार देखें"
type: docs
weight: 390
url: /hi/net/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class

एकल डिकोड प्रकार। उदाहरण प्राप्त करने के लिए डिकोड प्रकार देखें।

```csharp
public sealed class SingleDecodeType : BaseDecodeType, IEquatable<SingleDecodeType>
```

## गुण

| नाम | विवरण |
| --- | --- |
| [TypeIndex](../../aspose.barcode.barcoderecognition/singledecodetype/typeindex/) { get; } | डिकोड प्रकार का इंडेक्स प्राप्त करता है |
| [TypeName](../../aspose.barcode.barcoderecognition/singledecodetype/typename/) { get; } | डिकोड प्रकार का नाम प्राप्त करता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [Parse](../../aspose.barcode.barcoderecognition/singledecodetype/parse/)(string) | SingleDecodeType के नाम की स्ट्रिंग प्रतिनिधित्व को उसके इंस्टेंस में परिवर्तित करता है। |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/singledecodetype/containsany/)(params BaseDecodeType[]) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट सूची में शामिल है या नहीं। |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट [`BaseDecodeType`](../basedecodetype/) मान के बराबर है या नहीं। |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_1)(MultiDecodeType) | एक मान लौटाता है जो दर्शाता है कि निर्दिष्ट [`MultiDecodeType`](../multidecodetype/) संग्रह में केवल यह डिकोड प्रकार है या नहीं। |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_3)(object) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट `SingleDecodeType` मान के बराबर है या नहीं। |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_2)(SingleDecodeType) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट `SingleDecodeType` मान के बराबर है या नहीं। |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/singledecodetype/gethashcode/)() | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)() | SingleDecodeType के इंस्टेंस को उसके समकक्ष स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। स्ट्रिंग फ़ॉर्मेट है: "Index:-1; Name:None"। |
| override [ToString](../../aspose.barcode.barcoderecognition/singledecodetype/tostring/)() | दिए गए SingleDecodeType का नाम स्ट्रिंग के रूप में लौटाता है। |
| static [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)(SingleDecodeType) | SingleDecodeType के इंस्टेंस को उसके समकक्ष स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। स्ट्रिंग फ़ॉर्मेट है: "Index:-1; Name:None"। |

## उदाहरण

यह नमूना दिखाता है कि सिंगल डिकोड प्रकार का इंस्टेंस कैसे प्राप्त करें।

```csharp
[C#]
SingleDecodeType singleType = DecodeType.QR 
 
[VB.NET]
Dim singleType As SingleDecodeType 
singleType = DecodeType.QR
```

### और देखें

* class [BaseDecodeType](../basedecodetype/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


