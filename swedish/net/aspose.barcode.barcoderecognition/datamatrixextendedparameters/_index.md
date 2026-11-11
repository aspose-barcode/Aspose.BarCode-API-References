---
title: "Klass DataMatrixExtendedParameters"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.BarCodeRecognition.DataMatrixExtendedParameters-klass. Lagrar speciella data för DataMatrix‑igenkänd streckkod"
type: docs
weight: 220
url: /sv/net/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class

Lagrar speciella data för DataMatrix‑igenkänd streckkod

```csharp
public sealed class DataMatrixExtendedParameters : BaseExtendedParameters
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Testar om alla parametrar endast har standardvärden |
| [IsReaderProgramming](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/isreaderprogramming/) { get; } | Indikerar om kod används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. Standardvärdet är falskt. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodeid/) { get; } | Hämtar ID för DataMatrix strukturerade tilläggsläge streckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärdet är -1. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodescount/) { get; } | Hämtar antalet DataMatrix strukturerade tilläggsläge streckkoder. Standardvärdet är -1. Antalet måste vara ett värde mellan 1 och 35. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendfileid/) { get; } | Hämtar ID för DataMatrix strukturerade tilläggsläge streckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärdet är -1. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/equals/)(object) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `DataMatrixExtendedParameters`-värde. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/gethashcode/)() | Returnerar hashkoden för detta objekt. |
| override [ToString](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/tostring/)() | Returnerar en människoläsbar strängrepresentation av detta `DataMatrixExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_equality/) | Returnerar ett värde som indikerar om det första `DataMatrixExtendedParameters`-värdet är lika med det andra. |
| [operator !=](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_inequality/) | Returnerar ett värde som indikerar om det första `DataMatrixExtendedParameters`-värdet är annorlunda än det andra. |

## Exempel

Detta exempel visar hur man hämtar råvärden för DataMatrix

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

### Se även

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


