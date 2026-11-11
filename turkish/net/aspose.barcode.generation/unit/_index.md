---
title: "Sınıf Unit"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.Unit sınıfı. Boyut değerini farklı birimlerde (Piksel, İnç vb.) belirtir"
type: docs
weight: 1740
url: /tr/net/aspose.barcode.generation/unit/
---
## Unit class

Boyut değerini farklı birimlerde (Piksel, İnç vb.) belirtir.

```csharp
public sealed class Unit
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Document](../../aspose.barcode.generation/unit/document/) { get; set; } | Belge birimlerinde boyut değerini alır veya ayarlar. |
| [Inches](../../aspose.barcode.generation/unit/inches/) { get; set; } | İnç cinsinden boyut değerini alır veya ayarlar. |
| [Millimeters](../../aspose.barcode.generation/unit/millimeters/) { get; set; } | Milimetre cinsinden boyut değerini alır veya ayarlar. |
| [Pixels](../../aspose.barcode.generation/unit/pixels/) { get; set; } | Piksel cinsinden boyut değerini alır veya ayarlar. |
| [Point](../../aspose.barcode.generation/unit/point/) { get; set; } | Punto cinsinden boyut değerini alır veya ayarlar. |
| [Resolution](../../aspose.barcode.generation/unit/resolution/) { get; } | Çözünürlük |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.barcode.generation/unit/equals/)(object) | Bu örnek ile belirtilen nesnenin, aynı zamanda bir `Unit` nesnesi olması koşuluyla, aynı değere sahip olup olmadığını belirler. |
| override [GetHashCode](../../aspose.barcode.generation/unit/gethashcode/)() | Bu nesne için karma kodunu döndürür. |
| override [ToString](../../aspose.barcode.generation/unit/tostring/)() | `Unit` nesnesinin insan tarafından okunabilir dize temsili döndürür. |

## Örnekler

Bu örnek, bir BarCode görüntüsünün nasıl oluşturulup kaydedileceğini gösterir.

```csharp
[C#]
  using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.Parameters.Barcode.BarHeight.Millimeters = 10;
      generator.Save("test.png");
  }
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


