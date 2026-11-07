---
title: "enum"
linktitle: "EnableChecksum"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Hoe gebruik je enum in C++."
type: docs
weight: 6700
url: /nl/cpp/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enum




```cpp
enum class EnableChecksum
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Standaard | 0 | Als checksum vereist is volgens de specificatie - wordt deze toegevoegd. |
| Ja | 1 | Gebruik altijd checksum indien mogelijk. |
| Nee | 2 | Gebruik geen checksum. |

## Opmerkingen


Schakel checksum in tijdens het genereren voor 1D-streepjescodes.

Standaard wordt behandeld als Ja voor symbologieën die een checksum moeten bevatten, en als Nee waar checksum alleen mogelijk is.

Checksum wordt nooit gebruikt: Codabar

Checksum is mogelijk: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Checksum altijd gebruikt: overige symbologieën
## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
