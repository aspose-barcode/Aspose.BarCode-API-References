---
title: "enum"
linktitle: "AztecSymbolMode"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " enum. C++ में Aztec प्रतीक मोड को निर्दिष्ट करता है।"
type: docs
weight: 5400
url: /hi/cpp/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enum


Aztec प्रतीक मोड निर्दिष्ट करता है।

```cpp
enum class AztecSymbolMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| ऑटो | 0 | Aztec के लिए स्वचालित रूप से सबसे अच्छा प्रतीक (Compact या Full-range) चुनने को निर्दिष्ट करता है। यह डिफ़ॉल्ट मान है। |
| Compact | 1 | Aztec के लिए Compact प्रतीक को निर्दिष्ट करता है। Aztec Compact प्रतीक केवल 1, 2, 3 या 4 परतों की अनुमति देता है। |
| FullRange | 2 | Aztec के लिए Full-range प्रतीक को निर्दिष्ट करता है। Aztec Full-range प्रतीक 1 से 32 परतों तक की अनुमति देता है। |
| Rune | 3 | Aztec के लिए Rune प्रतीक को निर्दिष्ट करता है। Aztec Runes छोटे लेकिन विशिष्ट मशीन‑पठनीय चिह्नों की श्रृंखला हैं। यह केवल 0 से 255 तक की संख्यात्मक मान की अनुमति देता है। |

## टिप्पणियाँ


यह उदाहरण दिखाता है कि Aztec Symbol मोड को कैसे बदलें और एक [BarCode](../../aspose.barcode/) इमेज को सहेजें।
```cpp
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

## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
