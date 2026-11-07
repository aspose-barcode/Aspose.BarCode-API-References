---
title: "विधि"
linktitle: "GenerateBarCodeImage"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "विधि। C++ में वर्तमान सेटिंग्स के तहत बारकोड छवि उत्पन्न करें।"
type: docs
weight: 800
url: /hi/cpp/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator::GenerateBarCodeImage method


वर्तमान सेटिंग्स के तहत बारकोड छवि उत्पन्न करें।

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::BarCode::Generation::BarcodeGenerator::GenerateBarCodeImage()
```


### ReturnValue

बारकोड छवि। देखें [Bitmap](../).
## टिप्पणियाँ



यह नमूना दिखाता है कि बारकोड छवि कैसे बनाएं और सहेजें।
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

## और देखें

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
