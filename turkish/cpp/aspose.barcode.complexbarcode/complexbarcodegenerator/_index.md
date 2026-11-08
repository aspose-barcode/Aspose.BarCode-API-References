---
title: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator class"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator class. C++'ta arka uç karmaşık barkod (örn. SwissQR) görüntüleri oluşturmak için ComplexBarcodeGenerator."
type: docs
weight: 300
url: /tr/cpp/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class


[ComplexBarcodeGenerator](./) for backend complex barcode (e.g. SwissQR) images generation.

```cpp
class ComplexBarcodeGenerator : public System::IDisposable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/)(System::SharedPtr\<IComplexCodetext\>) | Bir [ComplexBarcodeGenerator](./) örneği oluşturur. |
| [Dispose](./dispose/)() override | Kullanılan tüm kaynakları temizle. |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur. |
| [get_Parameters](./get_parameters/)() | [Generation](../../aspose.barcode.generation/) parametreler. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, Generation::BarCodeImageFormat) | Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur ve kaydeder. |
| [Save](./save/)(System::String, Generation::BarCodeImageFormat) | Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur ve kaydeder. |
| [Save](./save/)(System::String) | Mevcut ayarlar altında karmaşık barkod görüntüsü oluşturur ve kaydeder. |
## Açıklamalar


Bu örnek, bir SwissQR görüntüsü nasıl oluşturup kaydedileceğini gösterir.
```cpp
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

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
