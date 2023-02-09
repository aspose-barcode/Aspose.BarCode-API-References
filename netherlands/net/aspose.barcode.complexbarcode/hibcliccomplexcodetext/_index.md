---
title: HIBCLICComplexCodetext
second_title: Aspose.BarCode voor .NET API-referentie
description: Basisklasse voor het coderen en decoderen van de tekst die is ingesloten in de HIBC LICcode.
type: docs
weight: 380
url: /nl/net/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class

Basisklasse voor het coderen en decoderen van de tekst die is ingesloten in de HIBC LIC-code.

```csharp
public abstract class HIBCLICComplexCodetext : IComplexCodetext
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Haalt of stelt het streepjescodetype in. HIBC LIC-codetekst kan worden gecodeerd met de coderingstypen HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC en HIBCQRLIC. Standaardwaarde: HIBCCode39LIC. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Krijgt streepjescodetype. |
| abstract [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getconstructedcodetext/)() | Construeert codetekst |
| abstract [InitFromString](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/initfromstring/)(string) | Initialiseert instantie van geconstrueerde codetekst. |

### Voorbeelden

Dit voorbeeld laat zien hoe u onbewerkte HIBC LIC-codetekst kunt decoderen naar HIBCLICComplexCodetext-instantie.

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
* naamruimte [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* montage [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->