---
title: "क्लास FontUnit"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.FontUnit क्लास। टेक्स्ट के लिए एक विशिष्ट फ़ॉर्मेट को परिभाषित करता है जिसमें फ़ॉन्ट फ़ेस आकार और शैली गुण शामिल हैं जहाँ आकार Unit मान प्रॉपर्टी में होता है।"
type: docs
weight: 1320
url: /hi/net/aspose.barcode.generation/fontunit/
---
## FontUnit class

पाठ के लिए एक विशिष्ट फ़ॉर्मेट परिभाषित करता है, जिसमें फ़ॉन्ट फ़ेस, आकार, और शैली गुण शामिल हैं जहाँ आकार यूनिट वैल्यू प्रॉपर्टी में है।

```csharp
public sealed class FontUnit
```

## गुण

| नाम | विवरण |
| --- | --- |
| [FamilyName](../../aspose.barcode.generation/fontunit/familyname/) { get; set; } | इस फ़ॉन्ट का फ़ेस नाम प्राप्त करता है या सेट करता है। |
| [Size](../../aspose.barcode.generation/fontunit/size/) { get; } | इस FontUnit का आकार Unit मान में प्राप्त करता है या सेट करता है। |
| [Style](../../aspose.barcode.generation/fontunit/style/) { get; set; } | इस FontUnit के लिए शैली जानकारी प्राप्त करता है या सेट करता है। |

## उदाहरण

यह उदाहरण दिखाता है कि BarCode छवि कैसे बनाएं और सहेजें।

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

### और देखें

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


