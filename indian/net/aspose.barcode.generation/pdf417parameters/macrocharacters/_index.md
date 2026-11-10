---
title: "Pdf417Parameters.MacroCharacters"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Pdf417Parameters प्रॉपर्टी। Macro Characters 05 और 06 मान विशेष मोड में अधिक संक्षिप्त एन्कोडिंग प्राप्त करने के लिए उपयोग किए जाते हैं। केवल MicroPdf417 के साथ उपयोग किया जा सकता है और 916 तथा 917 MicroPdf417 मोड को एन्कोड करता है। डिफ़ॉल्ट मान MacroCharacters.None"
type: docs
weight: 90
url: /hi/net/aspose.barcode.generation/pdf417parameters/macrocharacters/
---
## Pdf417Parameters.MacroCharacters property

Macro Characters 05 और 06 मानों का उपयोग विशेष मोड्स में अधिक संक्षिप्त एन्कोडिंग प्राप्त करने के लिए किया जाता है। केवल MicroPdf417 के साथ उपयोग किया जा सकता है और 916 तथा 917 MicroPdf417 मोड्स को एन्कोड करता है। डिफ़ॉल्ट मान: MacroCharacters.None.

```csharp
public MacroCharacter MacroCharacters { get; set; }
```

## उदाहरण

ये नमूने दिखाते हैं कि MicroPdf417 में Macro Characters को कैसे एन्कोड किया जाए।

```csharp
[C#]
//05 मैक्रो के साथ MicroPdf417 को एन्कोड करता है, स्ट्रिंग: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//06 मैक्रो के साथ MicroPdf417 को एन्कोड करता है, स्ट्रिंग: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

### और देखें

* enum [MacroCharacter](../../macrocharacter/)
* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


