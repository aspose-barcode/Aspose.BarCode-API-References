---
title: "enum"
linktitle: "AztecSymbolMode"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " enum. Gibt den Aztec‑Symbolmodus in C++ an."
type: docs
weight: 5400
url: /de/cpp/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enum


Gibt den Aztec-Symbolmodus an.

```cpp
enum class AztecSymbolMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Auto | 0 | Gibt an, dass automatisch das beste Symbol (Compact oder Full-range) für Aztec ausgewählt wird. Dies ist der Standardwert. |
| Compact | 1 | Gibt das Compact‑Symbol für Aztec an. Das Aztec Compact‑Symbol erlaubt nur 1, 2, 3 oder 4 Ebenen. |
| FullRange | 2 | Gibt das Full-range‑Symbol für Aztec an. Das Aztec Full-range‑Symbol erlaubt von 1 bis 32 Ebenen. |
| Rune | 3 | Gibt das Rune‑Symbol für Aztec an. Aztec‑Runen sind eine Reihe kleiner, aber eindeutiger maschinenlesbarer Markierungen. Es erlaubt nur Zahlenwerte von 0 bis 255. |

## Hinweise


Dieses Beispiel zeigt, wie man den Aztec‑Symbolmodus ändert und ein [BarCode](../../aspose.barcode/) Bild speichert.
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

## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
