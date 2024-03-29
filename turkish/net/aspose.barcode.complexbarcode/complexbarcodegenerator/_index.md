---
title: ComplexBarcodeGenerator
second_title: Aspose.BarCode for .NET API Referansı
description: Arka uç karmaşık barkodu ör. SwissQR görüntüleri oluşturmak için ComplexBarcodeGenerator.
type: docs
weight: 330
url: /tr/net/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class

Arka uç karmaşık barkodu (ör. SwissQR) görüntüleri oluşturmak için ComplexBarcodeGenerator.

```csharp
public sealed class ComplexBarcodeGenerator : Component
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ComplexBarcodeGenerator](complexbarcodegenerator)(IComplexCodetext) | ComplexBarcodeGenerator. örneğini oluşturur |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Parameters](../../aspose.barcode.complexbarcode/complexbarcodegenerator/parameters) { get; } | Nesil parametreleri. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [GenerateBarCodeImage](../../aspose.barcode.complexbarcode/complexbarcodegenerator/generatebarcodeimage)() | Geçerli ayarlar altında karmaşık barkod görüntüsü oluşturur. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save#save_1)(string) | Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur ve kaydeder. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save#save)(Stream, BarCodeImageFormat) | Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur ve kaydeder. |
| [Save](../../aspose.barcode.complexbarcode/complexbarcodegenerator/save#save_2)(string, BarCodeImageFormat) | Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur ve kaydeder. |

### Örnekler

Bu örnek, bir SwissQR görüntüsünün nasıl oluşturulacağını ve kaydedileceğini gösterir.

```csharp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // kalan alanları başlat
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

### Ayrıca bakınız

* ad alanı [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode)
* toplantı [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
