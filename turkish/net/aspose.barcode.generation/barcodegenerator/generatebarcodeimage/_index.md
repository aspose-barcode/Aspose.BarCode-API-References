---
title: "BarcodeGenerator.GenerateBarCodeImage"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "BarcodeGenerator yöntemi. Mevcut ayarlar altında barkod görüntüsünü oluşturur"
type: docs
weight: 80
url: /tr/net/aspose.barcode.generation/barcodegenerator/generatebarcodeimage/
---
## BarcodeGenerator.GenerateBarCodeImage method

Mevcut ayarlar altında barkod görüntüsünü oluştur.

```csharp
public Bitmap GenerateBarCodeImage()
```

### Dönüş Değeri

Barkod görüntüsü. Bitmap'e bakın.

## Örnekler

Bu örnek, bir barkod görüntüsünün nasıl oluşturulup kaydedileceğini gösterir.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      Bitmap barcode = generator.GenerateBarCodeImage();
      barcode.Save("test.png");
  }
```

### Ayrıca Bakınız

* class [BarcodeGenerator](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


