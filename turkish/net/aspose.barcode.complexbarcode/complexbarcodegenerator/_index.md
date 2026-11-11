---
title: "Sınıf ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.ComplexBarcode.ComplexBarcodeGenerator sınıfı. Arka uç karmaşık barkodları için ComplexBarcodeGenerator, örn. SwissQR görüntü oluşturma."
type: docs
weight: 510
url: /tr/net/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class

Arka uç karmaşık barkod (örn. SwissQR) görüntüleri oluşturmak için ComplexBarcodeGenerator.

```csharp
public sealed class ComplexBarcodeGenerator : Component
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [ComplexBarcodeGenerator](complexbarcodegenerator/)(IComplexCodetext) | ComplexBarcodeGenerator örneği oluşturur. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Parameters](../../aspose.barcode.complexbarcode/complexbarcodegenerator/parameters/) { get; } | Oluşturma parametreleri. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GenerateBarCodeImage](../../aspose.barcode.complexbarcode/complexbarcodegenerator/generatebarcodeimage/)() | Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_1)(string) | Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur ve kaydeder. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save)(Stream, BarCodeImageFormat) | Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur ve kaydeder. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save/#save_2)(string, BarCodeImageFormat) | Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur ve kaydeder. |

## Örnekler

Bu örnek, bir SwissQR görüntüsünün nasıl oluşturulup kaydedileceğini gösterir.

```csharp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // diğer alanları başlat
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


