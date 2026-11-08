---
title: "metot"
linktitle: "GenerateBarCodeImage"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " method. Barkod görüntüsünü mevcut ayarlar altında C++ içinde oluşturun."
type: docs
weight: 800
url: /tr/cpp/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator::GenerateBarCodeImage method


Mevcut ayarlar altında barkod görüntüsünü oluştur.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::BarCode::Generation::BarcodeGenerator::GenerateBarCodeImage()
```


### ReturnValue

Barkod görüntüsü. Bakınız [Bitmap](../).
## Açıklamalar



Bu örnek, bir barkod görüntüsünün nasıl oluşturulup kaydedileceğini gösterir.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

## Ayrıca Bakınız

* Class [BarcodeGenerator](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
