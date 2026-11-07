---
title: "enum"
linktitle: "MacroCharacter"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " enum. मैक्रो कैरेक्टर 05 और 06 मान विशेष मोड में अधिक संक्षिप्त एन्कोडिंग प्राप्त करने के लिए उपयोग किए जाते हैं। 05 मैक्रो कैरेक्टर को \"[)>\\u001E05\\u001D\" डिकोडेड डेटा हेडर और \"\\u001E\\u0004\" डिकोडेड डेटा ट्रेलर के रूप में अनुवादित किया जाता है। 06 मैक्रो कैरेक्टर को \"[)>\\u001E06\\u001D\" डिकोडेड डेटा हेडर और \"\\u001E\\u0004\" डिकोडेड डेटा ट्रेलर के रूप में C++ में अनुवादित किया जाता है।"
type: docs
weight: 7300
url: /hi/cpp/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enum


विशेष मोड में अधिक संक्षिप्त एन्कोडिंग प्राप्त करने के लिए मैक्रो कैरेक्टर 05 और 06 मानों का उपयोग किया जाता है। 05 मैक्रो कैरेक्टर को डिकोडेड डेटा हेडर के रूप में \"[)>\\u001E05\\u001D\" और डिकोडेड डेटा ट्रेलर के रूप में \"\\u001E\\u0004\" में अनुवादित किया जाता है। 06 मैक्रो कैरेक्टर को डिकोडेड डेटा हेडर के रूप में \"[)>\\u001E06\\u001D\" और डिकोडेड डेटा ट्रेलर के रूप में \"\\u001E\\u0004\" में अनुवादित किया जाता है।

```cpp
enum class MacroCharacter
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| कोई नहीं | 0 | बारकोड डेटा में कोई भी मैक्रो कैरेक्टर नहीं जोड़े जाते हैं। |
| Macro05 | 5 | 05 मैक्रो कैरेक्टर को बारकोड डेटा में पहली स्थिति में जोड़ा जाता है। GS1 डेटा आइडेंटिफायर ISO 15434 कैरेक्टर को "[)>\u001E05\u001D" डिकोडेड डेटा हेडर और "\u001E\u0004" डिकोडेड डेटा ट्रेलर के रूप में अनुवादित किया जाता है। |
| Macro06 | 6 | 06 मैक्रो कैरेक्टर को बारकोड डेटा में पहली स्थिति में जोड़ा जाता है। ASC MH10 डेटा आइडेंटिफायर ISO 15434 कैरेक्टर को "[)>\u001E06\u001D" डिकोडेड डेटा हेडर और "\u001E\u0004" डिकोडेड डेटा ट्रेलर के रूप में अनुवादित किया जाता है। |

## टिप्पणियाँ


ये नमूने दिखाते हैं कि माइक्रोपीडीएफ४१७ और डेटामैट्रिक्स में मैक्रो कैरेक्टर कैसे एन्कोड करें।
```cpp
[C#]
//ISO 15434 फ़ॉर्मेट में इस प्रकार का "(10)123ABC(10)123ABC" ऑटो-आइडेंटिफ़ाइड GS1 संदेश उत्पन्न करने के लिए आपको चाहिए:
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "10123ABC\u001D10123ABC");
generator.Parameters.Barcode.DataMatrix.MacroCharacters = MacroCharacter.Macro05;
BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1DataMatrix);
foreach (BarCodeResult result in reader.ReadBarCodes())
    Console.WriteLine("BarCode CodeText: " + result.CodeText);

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

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
