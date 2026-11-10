---
title: "Enum AztecSymbolMode"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.AztecSymbolMode enum. Aztec प्रतीक मोड निर्दिष्ट करता है।"
type: docs
weight: 970
url: /hi/net/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enumeration

एज़टेक प्रतीक मोड निर्दिष्ट करता है।

```csharp
public enum AztecSymbolMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Auto | `0` | Aztec के लिए स्वचालित रूप से सबसे अच्छा प्रतीक (कॉम्पैक्ट या फुल-रेंज) चुनने के लिए निर्दिष्ट करता है। यह डिफ़ॉल्ट मान है। |
| Compact | `1` | Aztec के लिए कॉम्पैक्ट प्रतीक निर्दिष्ट करता है। Aztec कॉम्पैक्ट प्रतीक केवल 1, 2, 3 या 4 लेयर की अनुमति देता है। |
| FullRange | `2` | Aztec के लिए फुल-रेंज प्रतीक निर्दिष्ट करता है। Aztec फुल-रेंज प्रतीक 1 से 32 लेयर तक की अनुमति देता है। |
| Rune | `3` | Aztec के लिए रूने प्रतीक निर्दिष्ट करता है। Aztec रून्स छोटे लेकिन विशिष्ट मशीन-पठनीय चिह्नों की श्रृंखला हैं। यह केवल 0 से 255 तक की संख्यात्मक मान की अनुमति देता है। |

## उदाहरण

यह नमूना दिखाता है कि Aztec Symbol मोड को कैसे बदलें और BarCode छवि को सहेजें।

```csharp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.CodeText = "125";
    generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune;
    generator.Save("test.png");
}
[VB.NET]
Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec)
    generator.CodeText = "125"
    generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune
    generator.Save("test.png")
End Using
```

### और देखें

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


