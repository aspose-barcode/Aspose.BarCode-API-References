---
title: SingleDecodeType
second_title: Aspose.BarCode .NET API संदर्भ के लिए
description: एकल डकड प्रकर उदहरण प्रप्त करने के लए डकड प्रकर देखें
type: docs
weight: 290
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
| [TypeIndex](../../aspose.barcode.barcoderecognition/singledecodetype/typeindex/) { get; } | डिकोड प्रकार का एक सूचकांक प्राप्त करता है |
| [TypeName](../../aspose.barcode.barcoderecognition/singledecodetype/typename/) { get; } | डिकोड टाइप का नाम प्राप्त करता है |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [Parse](../../aspose.barcode.barcoderecognition/singledecodetype/parse/)(string) | SingleDecodeType के नाम के स्ट्रिंग प्रस्तुतिकरण को उसके उदाहरण में कनवर्ट करता है. |
| override [ContainsAny](../../aspose.barcode.barcoderecognition/singledecodetype/containsany/)(params BaseDecodeType[]) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट सूची में शामिल है या नहीं। |
| [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(BaseDecodeType) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट के बराबर है या नहीं[`BaseDecodeType`](../basedecodetype/) मान. |
| virtual [Equals](../../aspose.barcode.barcoderecognition/basedecodetype/equals/)(MultyDecodeType) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट के बराबर है या नहीं[`MultyDecodeType`](../multydecodetype/) मान. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_3)(object) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट के बराबर है या नहीं`SingleDecodeType` मान. |
| override [Equals](../../aspose.barcode.barcoderecognition/singledecodetype/equals/#equals_2)(SingleDecodeType) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट के बराबर है या नहीं`SingleDecodeType` मान. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/singledecodetype/gethashcode/)() | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)() | SingleDecodeType के उदाहरण को इसके समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। स्ट्रिंग प्रारूप है: "इंडेक्स: -1; नाम: कोई नहीं"। |
| override [ToString](../../aspose.barcode.barcoderecognition/singledecodetype/tostring/)() | दिए गए SingleDecodeType का नाम एक स्ट्रिंग के रूप में लौटाता है। |
| static [GetString](../../aspose.barcode.barcoderecognition/singledecodetype/getstring/)(SingleDecodeType) | SingleDecodeType के उदाहरण को इसके समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। स्ट्रिंग प्रारूप है: "इंडेक्स: -1; नाम: कोई नहीं"। |

### उदाहरण

यह नमूना दिखाता है कि एकल डिकोड प्रकार का उदाहरण कैसे प्राप्त करें।

```csharp
[C#]
SingleDecodeType singleType = DecodeType.QR 
 
[VB.NET]
Dim singleType As SingleDecodeType 
singleType = DecodeType.QR
```

### यह सभी देखें

* class [BaseDecodeType](../basedecodetype/)
* नाम स्थान [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* सभा [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
