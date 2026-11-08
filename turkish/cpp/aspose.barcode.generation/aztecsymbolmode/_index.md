---
title: "enum"
linktitle: "AztecSymbolMode"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " enum. C++'da Aztec sembol modunu belirtir."
type: docs
weight: 5400
url: /tr/cpp/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enum


Aztec sembol modunu belirtir.

```cpp
enum class AztecSymbolMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Otomatik | 0 | Aztec için en iyi sembolü (Compact veya Full-range) otomatik olarak seçmeyi belirtir. Bu varsayılan değerdir. |
| Compact | 1 | Aztec için Compact sembolünü belirtir. Aztec Compact sembolü yalnızca 1, 2, 3 veya 4 katmana izin verir. |
| FullRange | 2 | Aztec için Full-range sembolünü belirtir. Aztec Full-range sembolü 1'den 32'ye kadar katmana izin verir. |
| Rune | 3 | Aztec için Rune sembolünü belirtir. Aztec Runes, küçük ama belirgin makine tarafından okunabilir işaretler serisidir. Yalnızca 0'dan 255'e kadar sayı değerine izin verir. |

## Açıklamalar


Bu örnek, Aztec Symbol modunu nasıl değiştireceğinizi ve bir [BarCode](../../aspose.barcode/) görüntüsünü nasıl kaydedeceğinizi gösterir.
```cpp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.CodeText = "125";
    generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune;
    generator.Save("test.png");
}
    [VB.NET]
    Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.Aztec)
        generator.CodeText = "125"
        generator.Parameters.Barcode.Aztec.AztecSymbolMode = AztecSymbolMode.Rune
        generator.Save("test.png")
    End Using
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
