---
title: "Aspose::BarCode::Generation::Unit sınıfı"
linktitle: "Unit"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::Generation::Unit sınıfı. C++'da farklı birimlerde (Piksel, İnç, vb.) boyut değerini belirtir."
type: docs
weight: 5000
url: /tr/cpp/aspose.barcode.generation/unit/
---
## Unit class


Farklı birimlerde (Piksel, İnç vb.) boyut değerini belirtir.

```cpp
class Unit : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Bu örnek ile belirtilen nesnenin, aynı zamanda bir [Unit](./) nesnesi olması koşuluyla, aynı değere sahip olup olmadığını belirler. |
| [get_Document](./get_document/)() | Belge birimlerinde boyut değerini alır. |
| [get_Inches](./get_inches/)() | İnç cinsinden boyut değerini alır. |
| [get_Millimeters](./get_millimeters/)() | Milimetre cinsinden boyut değerini alır. |
| [get_Pixels](./get_pixels/)() | Piksel cinsinden boyut değerini alır. |
| [get_Point](./get_point/)() | Punto cinsinden boyut değerini alır. |
| [get_Resolution](./get_resolution/)() const | Çözünürlük |
| [GetHashCode](./gethashcode/)() const override | Bu nesne için karma kodunu döndürür. |
| [set_Document](./set_document/)(float) | Belge birimlerinde boyut değerini ayarlar. |
| [set_Inches](./set_inches/)(float) | İnç cinsinden boyut değerini ayarlar. |
| [set_Millimeters](./set_millimeters/)(float) | Milimetre cinsinden boyut değerini ayarlar. |
| [set_Pixels](./set_pixels/)(float) | Piksel cinsinden boyut değerini ayarlar. |
| [set_Point](./set_point/)(float) | Punto cinsinden boyut değerini ayarlar. |
| [ToString](./tostring/)() const override | Bu [Unit](./) nesnesinin insan tarafından okunabilir bir dize temsili döndürür. |
## Açıklamalar


Bu örnek, bir [BarCode](../../aspose.barcode/) görüntüsünün nasıl oluşturulup kaydedileceğini gösterir.
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
