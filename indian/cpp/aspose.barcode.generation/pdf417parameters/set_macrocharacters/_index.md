---
title: "विधि"
linktitle: "set_MacroCharacters"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " विधि। Macro Characters 05 और 06 मान विशेष मोड में अधिक संक्षिप्त एन्कोडिंग प्राप्त करने के लिए उपयोग किए जाते हैं। केवल MicroPdf417 के साथ उपयोग किया जा सकता है और 916 तथा 917 MicroPdf417 मोड को एन्कोड करता है। डिफ़ॉल्ट मान: MacroCharacters.None C++ में।"
type: docs
weight: 4000
url: /hi/cpp/aspose.barcode.generation/pdf417parameters/set_macrocharacters/
---
## Pdf417Parameters::set_MacroCharacters method


Macro Characters 05 और 06 मान विशेष मोड में अधिक संक्षिप्त एन्कोडिंग प्राप्त करने के लिए उपयोग किए जाते हैं। केवल MicroPdf417 के साथ उपयोग किया जा सकता है और 916 तथा 917 MicroPdf417 मोड को एन्कोड करता है। डिफ़ॉल्ट मान: [MacroCharacters.None](../../barcodeclassifications/).

```cpp
void Aspose::BarCode::Generation::Pdf417Parameters::set_MacroCharacters(MacroCharacter value)
```

## टिप्पणियाँ


ये नमूने दिखाते हैं कि MicroPdf417 में Macro Characters को कैसे एन्कोड किया जाता है
```cpp
[C#]
//05 मैक्रो के साथ MicroPdf417 को एन्कोड करता है स्ट्रिंग: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//06 मैक्रो के साथ MicroPdf417 को एन्कोड करता है स्ट्रिंग: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## और देखें

* Enum [MacroCharacter](../../macrocharacter/)
* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
