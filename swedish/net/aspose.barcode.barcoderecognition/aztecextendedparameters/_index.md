---
title: "Klass AztecExtendedParameters"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.BarCodeRecognition.AztecExtendedParameters klass. Lagrar speciella data för Aztec‑igenkänd streckkod"
type: docs
weight: 40
url: /sv/net/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class

Lagrar speciella data för Aztec‑igenkänd streckkod

```csharp
public sealed class AztecExtendedParameters : BaseExtendedParameters
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Testar om alla parametrar endast har standardvärden |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/aztecextendedparameters/isreaderinitialization/) { get; } | Indikerar om kod används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. Standardvärdet är falskt. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodeid/) { get; } | Hämtar ID för Aztec‑strukturerat tilläggsläge‑streckkoden. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärdet är 0. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodescount/) { get; } | Hämtar antalet streckkoder för Aztec‑strukturerat tilläggsläge. Standardvärdet är 0. Antalet måste vara ett värde mellan 1 och 26. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendfileid/) { get; } | Hämtar fil‑ID för Aztec‑strukturerat tilläggsläge. Standardvärdet är en tom sträng |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/aztecextendedparameters/equals/)(object) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `AztecExtendedParameters`‑värde. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/aztecextendedparameters/gethashcode/)() | Returnerar hashkoden för detta objekt. |
| override [ToString](../../aspose.barcode.barcoderecognition/aztecextendedparameters/tostring/)() | Returnerar en människoläsbar strängrepresentation av detta `AztecExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_equality/) | Returnerar ett värde som indikerar om det första `AztecExtendedParameters`‑värdet är lika med det andra. |
| [operator !=](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_inequality/) | Returnerar ett värde som indikerar om det första `AztecExtendedParameters`‑värdet är annorlunda än det andra. |

## Exempel

Detta exempel visar hur man hämtar Aztec‑råvärden

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

### Se även

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


