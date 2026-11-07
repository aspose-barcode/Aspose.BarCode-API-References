---
title: "विधि"
linktitle: "get_GS1CompositeBar"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " मेथड। GS1 Composite Bar पैरामीटर C++ में।"
type: docs
weight: 2500
url: /hi/cpp/aspose.barcode.generation/barcodeparameters/get_gs1compositebar/
---
## BarcodeParameters::get_GS1CompositeBar method


GS1 कॉम्पोजिट बार पैरामीटर।

```cpp
System::SharedPtr<GS1CompositeBarParameters> Aspose::BarCode::Generation::BarcodeParameters::get_GS1CompositeBar() const
```

## टिप्पणियाँ


यह उदाहरण दिखाता है कि कैसे एक GS1 Composite Bar छवि बनाएं और सहेजें। ध्यान दें कि 1D कोडटेक्स्ट और 2D कोडटेक्स्ट '|' प्रतीक द्वारा अलग किए गए हैं।
```cpp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
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

* Class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* Class [BarcodeParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
