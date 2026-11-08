---
title: "enum"
linktitle: "EnableChecksum"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "C++'da enum nasıl kullanılır?"
type: docs
weight: 6700
url: /tr/cpp/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enum




```cpp
enum class EnableChecksum
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Varsayılan | 0 | Eğer kontrol toplamı spesifikasyon tarafından gereklilik gösteriyorsa - eklenecektir. |
| Evet | 1 | Mümkünse her zaman kontrol toplamını kullan. |
| Hayır | 2 | Kontrol toplamını kullanma. |

## Açıklamalar


1D barkodlar için oluşturma sırasında kontrol toplamını etkinleştir.

Varsayılan, kontrol toplamı içermesi zorunlu olan sembolojiler için Evet, sadece mümkün olduğu durumlarda Hayır olarak değerlendirilir.

Kontrol toplamı hiç kullanılmaz: Codabar

Kontrol toplamı mümkündür: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Kontrol toplamı her zaman kullanılır: Diğer sembolojiler
## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
