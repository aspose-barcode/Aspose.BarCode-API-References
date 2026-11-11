---
title: "Enum EnableChecksum"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.EnableChecksum enum. 1D barkodlar için oluşturma sırasında sağlama toplamını etkinleştir"
type: docs
weight: 1280
url: /tr/net/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enumeration

1D barkodlar için oluşturma sırasında sağlamayı etkinleştir.

Varsayılan, sağlama toplamı içermesi gereken sembolojiler için Evet, sadece mümkün olduğu durumlarda Hayır olarak değerlendirilir.

Sağlama toplamı hiç kullanılmaz: Codabar

Kontrol toplamı mümkündür: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Kontrol toplamı her zaman kullanılır: Diğer sembolojiler

```csharp
public enum EnableChecksum
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Default | `0` | Eğer kontrol toplamı spesifikasyon tarafından gerektiriliyorsa - eklenecektir. |
| Yes | `1` | Mümkünse her zaman kontrol toplamı kullanın. |
| No | `2` | Kontrol toplamı kullanmayın. |

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


