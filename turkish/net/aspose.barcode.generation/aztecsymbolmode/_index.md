---
title: "Enum AztecSymbolMode"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.AztecSymbolMode enum. Aztec sembol modunu belirtir."
type: docs
weight: 970
url: /tr/net/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enumeration

Aztec sembol modunu belirtir.

```csharp
public enum AztecSymbolMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Auto | `0` | Aztec için en iyi sembolü (Compact veya Full-range) otomatik olarak seçmeyi belirtir. Bu varsayılan değerdir. |
| Compact | `1` | Aztec için Compact sembolünü belirtir. Aztec Compact sembolü yalnızca 1, 2, 3 veya 4 katmana izin verir. |
| FullRange | `2` | Aztec için Full-range sembolünü belirtir. Aztec Full-range sembolü 1'den 32'ye kadar katmana izin verir. |
| Rune | `3` | Aztec için Rune sembolünü belirtir. Aztec Runes, küçük ama belirgin makine tarafından okunabilir işaretler serisidir. Yalnızca 0'dan 255'e kadar sayı değerine izin verir. |

## Örnekler

Bu örnek, Aztec Symbol modunu nasıl değiştireceğinizi ve bir BarCode görüntüsü nasıl kaydedeceğinizi gösterir.

```csharp
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

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


