---
title: "Enum EnableChecksum"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.EnableChecksum enum. Schakel controlegetal in tijdens generatie voor 1D‑barcodes"
type: docs
weight: 1280
url: /nl/net/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enumeration

Schakel controlesom in tijdens het genereren voor 1D-barcode.

Standaard wordt behandeld als Ja voor symbolen die een checksum moeten bevatten, en als Nee waar een checksum alleen mogelijk is.

Controlegetal nooit gebruikt: Codabar

Checksum is mogelijk: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Checksum altijd gebruikt: overige symbologieën

```csharp
public enum EnableChecksum
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Default | `0` | Als checksum vereist is volgens de specificatie - wordt deze toegevoegd. |
| Yes | `1` | Gebruik altijd checksum indien mogelijk. |
| No | `2` | Gebruik geen checksum. |

### Zie ook

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


