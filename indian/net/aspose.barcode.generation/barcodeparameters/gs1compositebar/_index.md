---
title: "BarcodeParameters.GS1CompositeBar"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "BarcodeParameters गुण. GS1 Composite Bar पैरामीटर"
type: docs
weight: 180
url: /hi/net/aspose.barcode.generation/barcodeparameters/gs1compositebar/
---
## BarcodeParameters.GS1CompositeBar property

GS1 कॉम्पोज़िट बार पैरामीटर।

```csharp
public GS1CompositeBarParameters GS1CompositeBar { get; set; }
```

## उदाहरण

यह उदाहरण दिखाता है कि कैसे एक GS1 Composite Bar छवि बनाएं और सहेजें। ध्यान दें कि 1D codetext और 2D codetext प्रतीक '&#x7C;' द्वारा अलग किए गए हैं।

```csharp
[C#]
  var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
  using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
  {
      generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
      generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
      
      // 2D घटक का आस्पेक्ट अनुपात
      generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
          
      // 1D और 2D घटकों का X-डाइमेंशन
      generator.Parameters.Barcode.XDimension.Pixels = 3;
          
      // 1D घटक की ऊँचाई
      generator.Parameters.Barcode.BarHeight.Pixels = 100;
      
      generator.Save("test.png");
  }
```

### और देखें

* class [GS1CompositeBarParameters](../../gs1compositebarparameters/)
* class [BarcodeParameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


