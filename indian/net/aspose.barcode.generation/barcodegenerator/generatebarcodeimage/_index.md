---
title: "BarcodeGenerator.GenerateBarCodeImage"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "BarcodeGenerator मेथड। वर्तमान सेटिंग्स के तहत बारकोड छवि उत्पन्न करें"
type: docs
weight: 80
url: /hi/net/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator.GenerateBarCodeImage method

वर्तमान सेटिंग्स के तहत बारकोड छवि उत्पन्न करें।

```csharp
public Bitmap GenerateBarCodeImage()
```

### वापसी मान

बारकोड छवि। देखें Bitmap।

## उदाहरण

यह उदाहरण दिखाता है कि बारकोड छवि कैसे बनाएं और सहेजें।

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

### और देखें

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


