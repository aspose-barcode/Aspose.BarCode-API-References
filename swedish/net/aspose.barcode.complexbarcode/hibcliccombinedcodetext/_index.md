---
title: "Klass HIBCLICCombinedCodetext"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.ComplexBarcode.HIBCLICCombinedCodetext-klass. Klass för kodning och avkodning av text som är inbäddad i HIBC LIC‑koden som lagrar primär och sekundär data"
type: docs
weight: 550
url: /sv/net/aspose.barcode.complexbarcode/hibcliccombinedcodetext/
---
## HIBCLICCombinedCodetext class

Klass för kodning och avkodning av text som är inbäddad i HIBC LIC‑koden som lagrar primär och sekundär data.

```csharp
public class HIBCLICCombinedCodetext : HIBCLICComplexCodetext
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [HIBCLICCombinedCodetext](hibcliccombinedcodetext/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Hämtar eller anger streckkodstyp. HIBC LIC-kodtext kan kodas med HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC och HIBCQRLIC kodningstyper. Standardvärde: HIBCCode39LIC. |
| [PrimaryData](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/primarydata/) { get; set; } | Identifierar primär data. |
| [SecondaryAndAdditionalData](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/secondaryandadditionaldata/) { get; set; } | Identifierar sekundär och ytterligare kompletterande data. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/equals/)(object) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `HIBCLICCombinedCodetext`‑värde. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Hämtar streckkodstyp. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/getconstructedcodetext/)() | Skapar kodtext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/gethashcode/)() | Returnerar hashkoden för detta objekt. |
| override [InitFromString](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/initfromstring/)(string) | Initierar objektet från konstruerad kodtext. |

## Exempel

Detta exempel visar hur man kodar och avkodar HIBC LIC med HIBCLICCombinedCodetext.

```csharp
[C#]
HIBCLICCombinedCodetext combinedCodetext = new HIBCLICCombinedCodetext();
combinedCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
combinedCodetext.PrimaryData = new PrimaryData();
combinedCodetext.PrimaryData.ProductOrCatalogNumber = "12345";
combinedCodetext.PrimaryData.LabelerIdentificationCode = "A999";
combinedCodetext.PrimaryData.UnitOfMeasureID = 1;
combinedCodetext.SecondaryAndAdditionalData = new SecondaryAndAdditionalData();
combinedCodetext.SecondaryAndAdditionalData.ExpiryDate = DateTime.Now;
combinedCodetext.SecondaryAndAdditionalData.ExpiryDateFormat = HIBCLICDateFormat.MMDDYY;
combinedCodetext.SecondaryAndAdditionalData.Quantity = 30;
combinedCodetext.SecondaryAndAdditionalData.LotNumber = "LOT123";
combinedCodetext.SecondaryAndAdditionalData.SerialNumber = "SERIAL123";
combinedCodetext.SecondaryAndAdditionalData.DateOfManufacture = DateTime.Now;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(combinedCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICCombinedCodetext result = (HIBCLICCombinedCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Product or catalog number: " + result.PrimaryData.ProductOrCatalogNumber);
        Console.WriteLine("Labeler identification code: " + result.PrimaryData.LabelerIdentificationCode);
        Console.WriteLine("Unit of measure ID: " + result.PrimaryData.UnitOfMeasureID);
        Console.WriteLine("Expiry date: " + result.SecondaryAndAdditionalData.ExpiryDate);
        Console.WriteLine("Quantity: " + result.SecondaryAndAdditionalData.Quantity);
        Console.WriteLine("Lot number: " + result.SecondaryAndAdditionalData.LotNumber);
        Console.WriteLine("Serial number: " + result.SecondaryAndAdditionalData.SerialNumber);
        Console.WriteLine("Date of manufacture: " + result.SecondaryAndAdditionalData.DateOfManufacture);
    }
}
```

### Se även

* class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


