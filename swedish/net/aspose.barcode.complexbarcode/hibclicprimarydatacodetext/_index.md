---
title: "Klass HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.ComplexBarcode.HIBCLICPrimaryDataCodetext-klass. Klass för kodning och avkodning av texten som är inbäddad i HIBC LIC-koden som lagrar primärdata"
type: docs
weight: 580
url: /sv/net/aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
## HIBCLICPrimaryDataCodetext class

Klass för kodning och avkodning av texten som är inbäddad i HIBC LIC-koden som lagrar primärdata.

```csharp
public class HIBCLICPrimaryDataCodetext : HIBCLICComplexCodetext
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [HIBCLICPrimaryDataCodetext](hibclicprimarydatacodetext/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Hämtar eller anger streckkodstyp. HIBC LIC-kodtext kan kodas med HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC och HIBCQRLIC kodningstyper. Standardvärde: HIBCCode39LIC. |
| [Data](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/data/) { get; set; } | Identifierar primär data. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/equals/)(object) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `HIBCLICPrimaryDataCodetext`-värde. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Hämtar streckkodstyp. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/getconstructedcodetext/)() | Skapar kodtext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/gethashcode/)() | Returnerar hashkoden för detta objekt. |
| override [InitFromString](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/initfromstring/)(string) | Initierar objektet från konstruerad kodtext. |

## Exempel

Detta exempel visar hur man kodar och avkodar HIBC LIC med hjälp av HIBCLICPrimaryDataCodetext.

```csharp
[C#]
HIBCLICPrimaryDataCodetext complexCodetext  = new HIBCLICPrimaryDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.Data = new PrimaryData();
complexCodetext.Data.ProductOrCatalogNumber = "12345";
complexCodetext.Data.LabelerIdentificationCode = "A999";
complexCodetext.Data.UnitOfMeasureID = 1;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICPrimaryDataCodetext result = (HIBCLICPrimaryDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.Data.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.Data.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.Data.UnitOfMeasureID);
    }
}
```

### Se även

* class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


