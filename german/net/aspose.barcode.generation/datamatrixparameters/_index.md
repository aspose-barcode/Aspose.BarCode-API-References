---
title: "Klasse DataMatrixParameters"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.Generation.DataMatrixParameters Klasse. DataMatrix-Parameter"
type: docs
weight: 1220
url: /de/net/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class

DataMatrix-Parameter.

```csharp
public class DataMatrixParameters
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/datamatrixparameters/aspectratio/) { get; set; } | Höhen/Breiten-Verhältnis des 2D‑BarCode‑Moduls. |
| [EccType](../../aspose.barcode.generation/datamatrixparameters/ecctype/) { get; set; } | Liest oder setzt einen Datamatrix ECC-Typ. Standardwert: DataMatrixEccType.Ecc200. |
| [ECIEncoding](../../aspose.barcode.generation/datamatrixparameters/eciencoding/) { get; set; } | Liest oder setzt die ECI-Kodierung. Wird verwendet, wenn EncodeMode auf Auto steht. Standardwert: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.generation/datamatrixparameters/encodemode/) { get; set; } | Kodiermodus des Datamatrix-Barcodes. Standardwert: EncodeMode.Auto. |
| [IsReaderProgramming](../../aspose.barcode.generation/datamatrixparameters/isreaderprogramming/) { get; set; } | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. Standardwert: false |
| [MacroCharacters](../../aspose.barcode.generation/datamatrixparameters/macrocharacters/) { get; set; } | Macro-Zeichen 05 und 06 werden verwendet, um eine kompaktere Kodierung in speziellen Modi zu erhalten. Können nur mit DataMatrixEccType.Ecc200 oder DataMatrixEccType.EccAuto verwendet werden. Können nicht mit EncodeTypes.GS1DataMatrix verwendet werden. Standardwert: MacroCharacters.None. |
| [StructuredAppendBarcodeId](../../aspose.barcode.generation/datamatrixparameters/structuredappendbarcodeid/) { get; set; } | Barcode-ID für den Structured-Append-Modus des Datamatrix-Barcodes. Standardwert: 0 |
| [StructuredAppendBarcodesCount](../../aspose.barcode.generation/datamatrixparameters/structuredappendbarcodescount/) { get; set; } | Anzahl der Barcodes für den Structured-Append-Modus des Datamatrix-Barcodes. Standardwert: 0 |
| [StructuredAppendFileId](../../aspose.barcode.generation/datamatrixparameters/structuredappendfileid/) { get; set; } | Datei-ID für den Structured-Append-Modus des Datamatrix-Barcodes. Standardwert: 0 |
| [Version](../../aspose.barcode.generation/datamatrixparameters/version/) { get; set; } | Liest oder setzt die Größe eines Datamatrix-Symbols. Standardwert: Version.Auto. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/datamatrixparameters/tostring/)() | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses `DataMatrixParameters` zurück. |

### Siehe auch

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


