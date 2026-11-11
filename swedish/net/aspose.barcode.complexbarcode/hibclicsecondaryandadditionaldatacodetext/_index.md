---
title: "Klass HIBCLICSecondaryAndAdditionalDataCodetext"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Aspose.BarCode.ComplexBarcode.HIBCLICSecondaryAndAdditionalDataCodetext-klass. Klass för kodning och avkodning av texten som är inbäddad i HIBC LIC-koden som lagrar sekundär data"
type: docs
weight: 590
url: /sv/net/aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/
---
## HIBCLICSecondaryAndAdditionalDataCodetext class

Klass för kodning och avkodning av texten som är inbäddad i HIBC LIC-koden som lagrar sekundär data.

```csharp
public class HIBCLICSecondaryAndAdditionalDataCodetext : HIBCLICComplexCodetext
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [HIBCLICSecondaryAndAdditionalDataCodetext](hibclicsecondaryandadditionaldatacodetext/)() | Standardkonstruktören. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Hämtar eller anger streckkodstyp. HIBC LIC-kodtext kan kodas med HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC och HIBCQRLIC kodningstyper. Standardvärde: HIBCCode39LIC. |
| [Data](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/data/) { get; set; } | Identifierar sekundär och ytterligare kompletterande data. |
| [LinkCharacter](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/linkcharacter/) { get; set; } | Identifierar länktecken. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/equals/)(object) | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat `HIBCLICSecondaryAndAdditionalDataCodetext`-värde. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Hämtar streckkodstyp. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/getconstructedcodetext/)() | Skapar kodtext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/gethashcode/)() | Returnerar hashkoden för detta objekt. |
| override [InitFromString](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/initfromstring/)(string) | Initierar objektet från konstruerad kodtext. |

## Exempel

Detta exempel visar hur man kodar och avkodar HIBC LIC med HIBCLICSecondaryAndAdditionalDataCodetext.

```csharp
[C#]
HIBCLICSecondaryAndAdditionalDataCodetext complexCodetext = new HIBCLICSecondaryAndAdditionalDataCodetext();
complexCodetext.BarcodeType = EncodeTypes.HIBCQRLIC;
complexCodetext.LinkCharacter = 'L';
complexCodetext.Data = new SecondaryAndAdditionalData();
complexCodetext.Data.ExpiryDate = DateTime.Now;
complexCodetext.Data.ExpiryDateFormat = HIBCLICDateFormat.MMDDYY;
complexCodetext.Data.Quantity = 30;
complexCodetext.Data.LotNumber = "LOT123";
complexCodetext.Data.SerialNumber = "SERIAL123";
complexCodetext.Data.DateOfManufacture = DateTime.Now;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    Bitmap image = generator.GenerateBarCodeImage();
    using (BarCodeReader reader = new BarCodeReader(image, DecodeType.HIBCQRLIC))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
        HIBCLICSecondaryAndAdditionalDataCodetext result = (HIBCLICSecondaryAndAdditionalDataCodetext)ComplexCodetextReader.TryDecodeHIBCLIC(codetext);
        Console.WriteLine("Expiry date: " + result.Data.ExpiryDate);
        Console.WriteLine("Quantity: " + result.Data.Quantity);
        Console.WriteLine("Lot number: " + result.Data.LotNumber);
        Console.WriteLine("Serial number: " + result.Data.SerialNumber);
        Console.WriteLine("Date of manufacture: " + result.Data.DateOfManufacture);
    }
}
```

### Se även

* class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


