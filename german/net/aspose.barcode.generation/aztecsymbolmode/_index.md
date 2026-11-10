---
title: "Enum AztecSymbolMode"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.AztecSymbolMode enum. Gibt den Aztec‑Symbolmodus an."
type: docs
weight: 970
url: /de/net/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enumeration

Gibt den Aztec-Symbolmodus an.

```csharp
public enum AztecSymbolMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | `0` | Gibt an, dass automatisch das beste Symbol (Compact oder Full-range) für Aztec ausgewählt wird. Dies ist der Standardwert. |
| Compact | `1` | Gibt das Compact‑Symbol für Aztec an. Das Aztec Compact‑Symbol erlaubt nur 1, 2, 3 oder 4 Ebenen. |
| FullRange | `2` | Gibt das Full-range‑Symbol für Aztec an. Das Aztec Full-range‑Symbol erlaubt von 1 bis 32 Ebenen. |
| Rune | `3` | Gibt das Rune‑Symbol für Aztec an. Aztec‑Runen sind eine Reihe kleiner, aber eindeutiger maschinenlesbarer Markierungen. Sie erlauben nur Zahlenwerte von 0 bis 255. |

## Beispiele

Dieses Beispiel zeigt, wie man den Aztec‑Symbol‑Modus ändert und ein BarCode‑Bild speichert.

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

### Siehe auch

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


