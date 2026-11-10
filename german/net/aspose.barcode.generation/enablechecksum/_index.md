---
title: "Enum EnableChecksum"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.EnableChecksum enum. Aktivieren Sie die Prüfsumme während der Generierung für 1D‑Strichcodes"
type: docs
weight: 1280
url: /de/net/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enumeration

Prüfsumme während der Erzeugung für 1D-Barcodes aktivieren.

Standard wird als Ja behandelt für Symbologien, die eine Prüfsumme enthalten müssen, und als Nein, wo eine Prüfsumme nur möglich ist.

Prüfsumme wird nie verwendet: Codabar

Prüfsumme ist möglich: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Prüfsumme wird immer verwendet: übrige Symbologien

```csharp
public enum EnableChecksum
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Default | `0` | Wenn die Prüfsumme gemäß der Spezifikation erforderlich ist, wird sie angehängt. |
| Yes | `1` | Verwenden Sie die Prüfsumme immer, wenn möglich. |
| No | `2` | Verwenden Sie keine Prüfsumme. |

### Siehe auch

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


