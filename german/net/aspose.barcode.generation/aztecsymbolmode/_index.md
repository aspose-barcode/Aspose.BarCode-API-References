---
title: AztecSymbolMode
second_title: Aspose.BarCode für .NET-API-Referenz
description: Gibt den aztekischen Symbolmodus an.
type: docs
weight: 460
url: /de/net/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enumeration

Gibt den aztekischen Symbolmodus an.

```csharp
public enum AztecSymbolMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | `0` | Legt fest, dass automatisch das beste Symbol (Compact oder Fullrange) für Aztec ausgewählt wird. Dies ist der Standardwert. |
| Compact | `1` | Gibt das Compact-Symbol für Aztec an. Aztec Compact-Symbol erlaubt nur 1, 2, 3 oder 4 Ebenen. |
| FullRange | `2` | Spezifiziert das Full-Range-Symbol für Aztec. Aztec Full-Range-Symbol erlaubt 1 bis 32 Layer. |
| Rune | `3` | Gibt das Runensymbol für Azteken an. Azteken-Runen sind eine Reihe kleiner, aber eindeutiger, maschinenlesbarer Zeichen. Es erlaubt nur Zahlenwerte von 0 bis 255. |

### Beispiele

Dieses Beispiel zeigt, wie man den Azteken-Symbolmodus ändert und ein Barcode-Bild speichert.

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

* namensraum [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* Montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
