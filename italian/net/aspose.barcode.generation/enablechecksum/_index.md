---
title: EnableChecksum
second_title: Riferimento all'API Aspose.BarCode per .NET
description: Abilita checksum durante la generazione per codici a barre 1D.
type: docs
weight: 710
url: /it/net/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enumeration

Abilita checksum durante la generazione per codici a barre 1D.

L'impostazione predefinita viene considerata Sì per le simbologie che devono contenere checksum, No laddove possibile solo il checksum.

Checksum mai utilizzato: Codabar

Checksum possibile: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Checksum sempre utilizzato: Simbologie di riposo

```csharp
public enum EnableChecksum
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Default | `0` | Se il checksum è richiesto dalle specifiche, verrà allegato. |
| Yes | `1` | Usa sempre il checksum se possibile. |
| No | `2` | Non utilizzare il checksum. |

### Guarda anche

* spazio dei nomi [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* assemblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
