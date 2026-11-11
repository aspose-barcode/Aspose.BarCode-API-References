---
title: "Klass HIBCLICComplexCodetext"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.ComplexBarcode.HIBCLICComplexCodetext klass. Bas-klass för kodning och avkodning av text som är inbäddad i HIBC LIC-koden"
type: docs
weight: 560
url: /sv/net/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class

Bas-klass för kodning och avkodning av text som är inbäddad i HIBC LIC-koden.

```csharp
public abstract class HIBCLICComplexCodetext : IComplexCodetext
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Hämtar eller anger streckkodstyp. HIBC LIC-kodtext kan kodas med HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC och HIBCQRLIC kodningstyper. Standardvärde: HIBCCode39LIC. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Hämtar streckkodstyp. |
| abstract [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getconstructedcodetext/)() | Skapar kodtext |
| abstract [InitFromString](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/initfromstring/)(string) | Initierar objektet från konstruerad kodtext. |

## Exempel

Detta exempel visar hur man avkodar rå HIBC LIC-kodtext till en HIBCLICComplexCodetext-instans.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.HIBCAztecLIC))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        HIBCLICComplexCodetext resultHIBCLICComplexCodetext = ComplexCodetextReader.TryDecodeHIBCLIC(result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

### Se även

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


