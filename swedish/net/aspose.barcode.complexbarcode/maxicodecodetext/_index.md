---
title: "Klass MaxiCodeCodetext"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.ComplexBarcode.MaxiCodeCodetext-klass. Bas-klass för kodning och avkodning av text som är inbäddad i MaxiCode‑koden"
type: docs
weight: 680
url: /sv/net/aspose.barcode.complexbarcode/maxicodecodetext/
---
## MaxiCodeCodetext class

Bas-klass för kodning och avkodning av text som är inbäddad i MaxiCode‑koden.

```csharp
public abstract class MaxiCodeCodetext : IComplexCodetext
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ECIEncoding](../../aspose.barcode.complexbarcode/maxicodecodetext/eciencoding/) { get; set; } | Hämtar eller anger ECI-kodning. Används när MaxiCodeEncodeMode är Auto. Standardvärde: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.complexbarcode/maxicodecodetext/encodemode/) { get; set; } | Hämtar eller anger ett MaxiCode-kodningsläge. Standardvärde: Auto. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/maxicodecodetext/getbarcodetype/)() | Hämtar streckkodstyp. |
| abstract [GetConstructedCodetext](../../aspose.barcode.complexbarcode/maxicodecodetext/getconstructedcodetext/)() | Skapar kodtext |
| abstract [GetMode](../../aspose.barcode.complexbarcode/maxicodecodetext/getmode/)() | Hämtar MaxiCode-läge. |
| abstract [InitFromString](../../aspose.barcode.complexbarcode/maxicodecodetext/initfromstring/)(string) | Initierar objektet från konstruerad kodtext. |

## Exempel

Detta exempel visar hur man avkodar rå MaxiCode‑kodtext till en MaxiCodeCodetext‑instans.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.MaxiCode))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.TryDecodeMaxiCode(result.Extended.MaxiCode.MaxiCodeMode, result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("MaxiCode mode: " + resultMaxiCodeCodetext.GetMode());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

### Se även

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


