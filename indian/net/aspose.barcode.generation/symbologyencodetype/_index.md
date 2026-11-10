---
title: "क्लास SymbologyEncodeType"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.SymbologyEncodeType क्लास। सिम्बोलॉजी एन्कोड प्रकार। इंस्टेंस प्राप्त करने के लिए EncodeTypes देखें।"
type: docs
weight: 1710
url: /hi/net/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class

सिम्बोलॉजी एन्कोड प्रकार। उदाहरण प्राप्त करने के लिए EncodeTypes देखें।

```csharp
public class SymbologyEncodeType : BaseEncodeType
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Classification](../../aspose.barcode.generation/baseencodetype/classification/) { get; } | इस प्रतीक प्रणाली की वर्गीकरण प्राप्त करता है। |
| [TypeIndex](../../aspose.barcode.generation/baseencodetype/typeindex/) { get; } | एन्कोड प्रकार का सूचकांक प्राप्त करता है |
| [TypeName](../../aspose.barcode.generation/baseencodetype/typename/) { get; } | एन्कोड प्रकार का नाम प्राप्त करता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(BaseEncodeType) | एक मान लौटाता है जो यह दर्शाता है कि यह उदाहरण निर्दिष्ट [`BaseEncodeType`](../baseencodetype/) मान के बराबर है या नहीं। |
| override [Equals](../../aspose.barcode.generation/baseencodetype/equals/)(object) | एक मान लौटाता है जो यह दर्शाता है कि यह उदाहरण निर्दिष्ट [`BaseEncodeType`](../baseencodetype/) मान के बराबर है या नहीं। |
| override [GetHashCode](../../aspose.barcode.generation/baseencodetype/gethashcode/)() | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [GetString](../../aspose.barcode.generation/baseencodetype/getstring/)() | BaseEncodeType के उदाहरण को उसके समतुल्य स्ट्रिंग प्रतिनिधित्व में परिवर्तित करता है। स्ट्रिंग स्वरूप है: "Index:0; Name:Codabar"। |
| override [ToString](../../aspose.barcode.generation/baseencodetype/tostring/)() | दिए गए BaseEncodeType का नाम स्ट्रिंग के रूप में लौटाता है। |

## उदाहरण

यह उदाहरण दिखाता है कि SymbologyEncodeType क्लास का उदाहरण कैसे प्राप्त किया जाए।

```csharp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR 
 
[VB.NET]
Dim symbologyType As SymbologyEncodeType 
symbologyType = EncodeTypes.QR
```

### और देखें

* class [BaseEncodeType](../baseencodetype/)
* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


