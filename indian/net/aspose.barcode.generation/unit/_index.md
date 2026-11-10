---
title: "क्लास Unit"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.Unit क्लास। विभिन्न इकाइयों जैसे पिक्सेल, इंच आदि में आकार मान निर्दिष्ट करता है"
type: docs
weight: 1740
url: /hi/net/aspose.barcode.generation/unit/
---
## Unit class

विभिन्न इकाइयों (पिक्सेल, इंच, आदि) में आकार मान निर्दिष्ट करता है।

```csharp
public sealed class Unit
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Document](../../aspose.barcode.generation/unit/document/) { get; set; } | दस्तावेज़ इकाइयों में आकार मान प्राप्त करता है या सेट करता है। |
| [Inches](../../aspose.barcode.generation/unit/inches/) { get; set; } | इंच में आकार मान प्राप्त करता है या सेट करता है। |
| [Millimeters](../../aspose.barcode.generation/unit/millimeters/) { get; set; } | मिलीमीटर में आकार मान प्राप्त करता है या सेट करता है। |
| [Pixels](../../aspose.barcode.generation/unit/pixels/) { get; set; } | पिक्सेल में आकार मान प्राप्त करता है या सेट करता है। |
| [Point](../../aspose.barcode.generation/unit/point/) { get; set; } | पॉइंट में आकार मान प्राप्त करता है या सेट करता है। |
| [Resolution](../../aspose.barcode.generation/unit/resolution/) { get; } | रिज़ॉल्यूशन |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.barcode.generation/unit/equals/)(object) | निर्धारित करता है कि यह इंस्टेंस और एक निर्दिष्ट ऑब्जेक्ट, जो भी एक `Unit` ऑब्जेक्ट होना चाहिए, का मान समान है या नहीं। |
| override [GetHashCode](../../aspose.barcode.generation/unit/gethashcode/)() | इस ऑब्जेक्ट के लिए हैश कोड लौटाता है। |
| override [ToString](../../aspose.barcode.generation/unit/tostring/)() | इस `Unit` की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

## उदाहरण

यह उदाहरण दिखाता है कि BarCode छवि कैसे बनाएं और सहेजें।

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

### और देखें

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


