---
title: DataMatrixEncodeMode
second_title: Aspose.BarCode voor .NET API-referentie
description: De coderingsmodus van de DataMatrixencoder standaard ingesteld op Auto
type: docs
weight: 880
url: /nl/net/aspose.barcode.generation/datamatrixencodemode/
---
## DataMatrixEncodeMode enumeration

De coderingsmodus van de DataMatrix-encoder, standaard ingesteld op Auto

```csharp
public enum DataMatrixEncodeMode
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Auto | `0` | Kies automatisch de beste coderingsmodus voor Datamatrix-codering |
| ASCII | `1` | Codeert één alfanumeriek of twee numerieke tekens per byte |
| Full | `6` | Codeer 8 bit waarden |
| Custom | `7` | Codeer met de codering gespecificeerd in BarcodeGenerator.Parameters.Barcode.DataMatrix.CodeTextEncoding |
| C40 | `8` | Gebruikt C40-codering. Codeert alfanumerieke hoofdletters, kleine letters en speciale tekens |
| Text | `9` | Gebruikt tekstcodering. Codeert alfanumerieke kleine letters, hoofdletters en speciale tekens |
| EDIFACT | `10` | Gebruikt EDIFACT-codering. Gebruikt zes bits per teken, codeert cijfers, hoofdletters en veel leestekens, maar biedt geen ondersteuning voor kleine letters. |
| ANSIX12 | `11` | Gebruikt ANSI X12-codering. |
| ExtendedCodetext | `12` | ExtendedCodetext-modus maakt het mogelijk om handmatig van coderingsschema's in codetekst te wisselen. |

### Zie ook

* naamruimte [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->