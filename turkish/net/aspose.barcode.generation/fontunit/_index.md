---
title: "Sınıf FontUnit"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.FontUnit sınıfı. Metin için yazı tipi yüzü boyutu ve stil özniteliklerini içeren belirli bir biçimi tanımlar; boyut, Unit değer özelliğinde bulunur."
type: docs
weight: 1320
url: /tr/net/aspose.barcode.generation/fontunit/
---
## FontUnit class

Metin için belirli bir biçim tanımlar, font tipi, boyut ve stil özelliklerini içerir; burada boyut Unit değer özelliğinde belirtilir.

```csharp
public sealed class FontUnit
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [FamilyName](../../aspose.barcode.generation/fontunit/familyname/) { get; set; } | Bu Fontun yüz adını alır veya ayarlar. |
| [Size](../../aspose.barcode.generation/fontunit/size/) { get; } | Bu FontUnit'in boyutunu Unit değerinde alır veya ayarlar. |
| [Style](../../aspose.barcode.generation/fontunit/style/) { get; set; } | Bu FontUnit için stil bilgilerini alır veya ayarlar. |

## Örnekler

Bu örnek, bir BarCode görüntüsünün nasıl oluşturulup kaydedileceğini gösterir.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeTextStyle.Font.Style = FontStyle.Italic;
      generator.CodeTextStyle.Font.Size.Point = 18;
      generator.Save("test.png");
  }
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


