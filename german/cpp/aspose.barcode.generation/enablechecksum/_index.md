---
title: "enum"
linktitle: "EnableChecksum"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Wie man das enum in C++ verwendet."
type: docs
weight: 6700
url: /de/cpp/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enum




```cpp
enum class EnableChecksum
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Standard | 0 | Wenn die Prüfsumme gemäß der Spezifikation erforderlich ist, wird sie angehängt. |
| Ja | 1 | Verwenden Sie die Prüfsumme immer, wenn möglich. |
| Nein | 2 | Verwenden Sie die Prüfsumme nicht. |

## Hinweise


Aktivieren Sie die Prüfsumme während der Erzeugung für 1D‑Barcodes.

Standard wird als Ja behandelt für Symbologien, die zwingend eine Prüfsumme enthalten, und als Nein, wo eine Prüfsumme nur optional ist.

Prüfsumme wird nie verwendet: Codabar

Prüfsumme ist möglich: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Prüfsumme wird immer verwendet: übrige Symbologien
## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
