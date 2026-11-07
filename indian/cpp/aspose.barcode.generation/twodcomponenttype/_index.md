---
title: "enum"
linktitle: "TwoDComponentType"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " enum. C++ में 2D घटक का प्रकार।"
type: docs
weight: 8700
url: /hi/cpp/aspose.barcode.generation/twodcomponenttype/
---
## TwoDComponentType enum


2D घटक का प्रकार

```cpp
enum class TwoDComponentType
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| ऑटो | 0 | 2D घटक का प्रकार स्वचालित रूप से चुनें |
| CC_A | 1 | CC-A 2D घटक का प्रकार। यह MicroPDF417 का एक संरचनात्मक वैरिएंट है। |
| CC_B | 2 | CC-B 2D घटक का प्रकार। यह एक MicroPDF417 प्रतीक है। |
| CC_C | 3 | CC-C 2D घटक का प्रकार। यह एक PDF417 प्रतीक है। |

## टिप्पणियाँ


यह उदाहरण दिखाता है कि कैसे एक GS1 कॉम्पोज़िट बार छवि बनाएं और सहेजें। ध्यान दें कि 1D कोडटेक्स्ट और 2D कोडटेक्स्ट '/' प्रतीक द्वारा अलग किए गए हैं।
```cpp
[C#]
var codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
    using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
    {
    generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
    generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;

    // 2D घटक का आस्पेक्ट अनुपात
    generator.Parameters.Barcode.Pdf417.AspectRatio = 3;

    // 1D और 2D घटकों का X-डायमेंशन
    generator.Parameters.Barcode.XDimension.Pixels = 3;

    // 1D घटक की ऊँचाई
    generator.Parameters.Barcode.BarHeight.Pixels = 100;

    generator.Save("test.png");
}
```

## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
