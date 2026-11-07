---
title: "enum"
linktitle: "AztecSymbolMode"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " enum. Specifica la modalità simbolo Aztec in C++."
type: docs
weight: 5400
url: /it/cpp/aspose.barcode.generation/aztecsymbolmode/
---
## AztecSymbolMode enum


Specifica la modalità del simbolo Aztec.

```cpp
enum class AztecSymbolMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | 0 | Specifica di selezionare automaticamente il miglior simbolo (Compact o Full-range) per Aztec. Questo è il valore predefinito. |
| Compact | 1 | Specifica il simbolo Compact per Aztec. Il simbolo Aztec Compact consente solo 1, 2, 3 o 4 livelli. |
| FullRange | 2 | Specifica il simbolo Full-range per Aztec. Il simbolo Aztec Full-range consente da 1 a 32 livelli. |
| Rune | 3 | Specifica il simbolo Rune per Aztec. Le Rune Aztec sono una serie di piccoli ma distinti segni leggibili dalla macchina. Consente solo valori numerici da 0 a 255. |

## Osservazioni


Questo esempio mostra come modificare la modalità Aztec Symbol e salvare un'immagine [BarCode](../../aspose.barcode/).
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

## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
