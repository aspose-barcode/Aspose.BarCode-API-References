---
title: "enum"
linktitle: "EnableChecksum"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Hur man använder enum i C++."
type: docs
weight: 6700
url: /sv/cpp/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enum




```cpp
enum class EnableChecksum
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Standard | 0 | Om kontrollsumman krävs av specifikationen - kommer den att bifogas. |
| Ja | 1 | Använd alltid kontrollsumma om möjligt. |
| Nej | 2 | Använd inte kontrollsumma. |

## Anmärkningar


Aktivera kontrollsumma under generering för 1D-streckkoder.

Standard behandlas som Ja för symbologier som måste innehålla kontrollsumma, och som Nej där kontrollsumma endast är möjlig.

Kontrollsumma används aldrig: Codabar

Kontrollsumma är möjlig: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Kontrollsumma används alltid: Övriga symbologier
## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
