---
title: "Class HIBCLICComplexCodetext"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "Aspose.BarCode.ComplexBarcode.HIBCLICComplexCodetext class. Basisklasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC LIC-code."
type: docs
weight: 560
url: /nl/net/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class

Basisklasse voor het coderen en decoderen van de in de HIBC LIC-code ingebedde tekst.

```csharp
public abstract class HIBCLICComplexCodetext : IComplexCodetext
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Haalt op of stelt het type barcode in. HIBC LIC-codetext kan worden gecodeerd met HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC en HIBCQRLIC coderingssoorten. Standaardwaarde: HIBCCode39LIC. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Haalt het barcode-type op. |
| abstract [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getconstructedcodetext/)() | Construeert codetext |
| abstract [InitFromString](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/initfromstring/)(string) | Initialiseert de instantie vanuit geconstrueerde codetext. |

## Voorbeelden

Dit voorbeeld laat zien hoe ruwe HIBC LIC-codetekst te decoderen naar een HIBCLICComplexCodetext‑instantie.

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

### Zie ook

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


