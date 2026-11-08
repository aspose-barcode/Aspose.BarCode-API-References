---
title: "Aspose::BarCode::Generation::FontUnit sınıfı"
linktitle: "FontUnit"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::Generation::FontUnit sınıfı. Metin için belirli bir biçim tanımlar; font tipi, boyutu ve stil özelliklerini içerir ve boyut C++'da Unit değer özelliğinde bulunur."
type: docs
weight: 2500
url: /tr/cpp/aspose.barcode.generation/fontunit/
---
## FontUnit class


Metin için belirli bir biçim tanımlar; font tipi, boyutu ve stil özelliklerini içerir ve boyut [Unit](../unit/) değer özelliğinde bulunur.

```cpp
class FontUnit : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_FamilyName](./get_familyname/)() const | Bu Font'un yüz adını alır. |
| [get_Size](./get_size/)() const | Bu [FontUnit](./) öğesinin [Unit](../unit/) değerindeki boyutunu alır. |
| [get_Style](./get_style/)() const | Bu [FontUnit](./) için stil bilgilerini alır. |
| [set_FamilyName](./set_familyname/)(System::String) | Bu Yazı tipinin yüz adını ayarlar. |
| [set_Style](./set_style/)(System::Drawing::FontStyle) | Bu [FontUnit](./) için stil bilgilerini ayarlar. |
## Açıklamalar


Bu örnek, bir [BarCode](../../aspose.barcode/) görüntüsünün nasıl oluşturulup kaydedileceğini gösterir.
```cpp
[C#]
      using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
