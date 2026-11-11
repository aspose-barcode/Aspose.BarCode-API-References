---
title: "Klasse DataMatrixExtendedParameters"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.BarCodeRecognition.DataMatrixExtendedParameters klasse. Slaat speciale gegevens van herkende DataMatrix-barcode op"
type: docs
weight: 220
url: /nl/net/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class

Slaat speciale gegevens op van de herkende DataMatrix barcode

```csharp
public sealed class DataMatrixExtendedParameters : BaseExtendedParameters
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Test of alle parameters alleen standaardwaarden hebben |
| [IsReaderProgramming](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/isreaderprogramming/) { get; } | Geeft aan of de code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcode-lezer. Standaardwaarde is false. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodeid/) { get; } | Haalt de ID op van de DataMatrix structured append-modusbarcode. De ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is -1. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodescount/) { get; } | Haalt het aantal barcodes op van de DataMatrix structured append-modus. Standaardwaarde is -1. Het aantal moet een waarde tussen 1 en 35 zijn. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendfileid/) { get; } | Haalt de ID op van de DataMatrix structured append-modusbarcode. De ID begint bij 1 en moet kleiner of gelijk zijn aan het aantal barcodes. Standaardwaarde is -1. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/equals/)(object) | Geeft een waarde terug die aangeeft of deze instantie gelijk is aan een opgegeven `DataMatrixExtendedParameters`-waarde. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/gethashcode/)() | Retourneert de hashcode voor deze instantie. |
| override [ToString](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/tostring/)() | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze `DataMatrixExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_equality/) | Retourneert een waarde die aangeeft of de eerste `DataMatrixExtendedParameters`-waarde gelijk is aan de tweede. |
| [operator !=](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_inequality/) | Retourneert een waarde die aangeeft of de eerste `DataMatrixExtendedParameters`-waarde verschilt van de tweede. |

## Voorbeelden

Dit voorbeeld toont hoe u de ruwe DataMatrix-waarden kunt ophalen

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

### Zie ook

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


