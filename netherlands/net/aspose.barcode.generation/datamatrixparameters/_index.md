---
title: "Klasse DataMatrixParameters"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.Generation.DataMatrixParameters klasse. DataMatrix-parameters"
type: docs
weight: 1220
url: /nl/net/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class

DataMatrix-parameters.

```csharp
public class DataMatrixParameters
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/datamatrixparameters/aspectratio/) { get; set; } | Hoogte/breedteverhouding van 2D BarCode-module. |
| [EccType](../../aspose.barcode.generation/datamatrixparameters/ecctype/) { get; set; } | Haalt een Datamatrix ECC-type op of stelt deze in. Standaardwaarde: DataMatrixEccType.Ecc200. |
| [ECIEncoding](../../aspose.barcode.generation/datamatrixparameters/eciencoding/) { get; set; } | Haalt of stelt ECI-codering in. Wordt gebruikt wanneer EncodeMode Auto is. Standaardwaarde: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.generation/datamatrixparameters/encodemode/) { get; set; } | Encode-modus van Datamatrix-barcode. Standaardwaarde: EncodeMode.Auto. |
| [IsReaderProgramming](../../aspose.barcode.generation/datamatrixparameters/isreaderprogramming/) { get; set; } | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. Standaardwaarde: false |
| [MacroCharacters](../../aspose.barcode.generation/datamatrixparameters/macrocharacters/) { get; set; } | Macro Characters 05 en 06 waarden worden gebruikt om een compactere codering te verkrijgen in speciale modi. Kan alleen worden gebruikt met DataMatrixEccType.Ecc200 of DataMatrixEccType.EccAuto. Kan niet worden gebruikt met EncodeTypes.GS1DataMatrix Standaardwaarde: MacroCharacters.None. |
| [StructuredAppendBarcodeId](../../aspose.barcode.generation/datamatrixparameters/structuredappendbarcodeid/) { get; set; } | Barcode-ID voor Structured Append-modus van Datamatrix-barcode. Standaardwaarde: 0 |
| [StructuredAppendBarcodesCount](../../aspose.barcode.generation/datamatrixparameters/structuredappendbarcodescount/) { get; set; } | Aantal barcodes voor Structured Append-modus van Datamatrix-barcode. Standaardwaarde: 0 |
| [StructuredAppendFileId](../../aspose.barcode.generation/datamatrixparameters/structuredappendfileid/) { get; set; } | Bestands-ID voor Structured Append-modus van Datamatrix-barcode. Standaardwaarde: 0 |
| [Version](../../aspose.barcode.generation/datamatrixparameters/version/) { get; set; } | Haalt of stelt een Datamatrix-symboolgrootte in. Standaardwaarde: Version.Auto. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/datamatrixparameters/tostring/)() | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze `DataMatrixParameters`. |

### Zie ook

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


