---
title: "Klass DotCodeExtendedParameters"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.BarCodeRecognition.DotCodeExtendedParameters-klass. Lagrar speciella data för DotCode‑erkänd streckkod"
type: docs
weight: 250
url: /sv/net/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class

Lagrar speciella data för DotCode‑erkänd streckkod

```csharp
public sealed class DotCodeExtendedParameters : BaseExtendedParameters
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Testar om alla parametrar endast har standardvärden |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/isreaderinitialization/) { get; } | Indikerar om kod används för att instruera läsaren att tolka följande data som instruktioner för initiering eller omprogrammering av streckkodsläsaren. Standardvärdet är falskt. |
| [StructuredAppendModeBarcodeId](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/structuredappendmodebarcodeid/) { get; } | Hämtar ID för DotCode strukturerat append‑läge streckkod. ID startar från 1 och måste vara mindre än eller lika med antalet streckkoder. Standardvärdet är -1. |
| [StructuredAppendModeBarcodesCount](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/structuredappendmodebarcodescount/) { get; } | Hämtar antalet DotCode strukturerade append‑läge streckkoder. Standardvärdet är -1. Antalet måste vara ett värde mellan 1 och 35. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/equals/)(object) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `DotCodeExtendedParameters`‑värde. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/gethashcode/)() | Returnerar hashkoden för detta objekt. |
| override [ToString](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/tostring/)() | Returnerar en människoläsbar strängrepresentation av detta `DotCodeExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/op_equality/) | Returnerar ett värde som indikerar om det första `DotCodeExtendedParameters`‑värdet är lika med det andra. |
| [operator !=](../../aspose.barcode.barcoderecognition/dotcodeextendedparameters/op_inequality/) | Returnerar ett värde som indikerar om det första `DotCodeExtendedParameters`‑värdet är olika från det andra. |

## Exempel

Detta exempel visar hur man hämtar råvärden för DotCode

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DotCode))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DotCode barcode ID: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodeId);
        Console.WriteLine("DotCode barcodes count: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodesCount);
    }
}
```

### Se även

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


