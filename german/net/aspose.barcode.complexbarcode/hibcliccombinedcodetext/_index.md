---
title: "Klasse HIBCLICCombinedCodetext"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.ComplexBarcode.HIBCLICCombinedCodetext Klasse. Klasse zum Codieren und Dekodieren des in den HIBC-LIC-Code eingebetteten Textes, der primäre und sekundäre Daten speichert."
type: docs
weight: 550
url: /de/net/aspose.barcode.complexbarcode/hibcliccombinedcodetext/
---
## HIBCLICCombinedCodetext class

Klasse zum Kodieren und Dekodieren des in den HIBC‑LIC‑Code eingebetteten Textes, der primäre und sekundäre Daten speichert.

```csharp
public class HIBCLICCombinedCodetext : HIBCLICComplexCodetext
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [HIBCLICCombinedCodetext](hibcliccombinedcodetext/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Liest oder setzt den Barcode‑Typ. HIBC‑LIC‑Codetext kann mit den Kodierungstypen HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC und HIBCQRLIC kodiert werden. Standardwert: HIBCCode39LIC. |
| [PrimaryData](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/primarydata/) { get; set; } | Identifiziert primäre Daten. |
| [SecondaryAndAdditionalData](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/secondaryandadditionaldata/) { get; set; } | Identifiziert sekundäre und zusätzliche ergänzende Daten. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/equals/)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `HIBCLICCombinedCodetext`-Wert entspricht. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Liest den Barcode‑Typ. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/getconstructedcodetext/)() | Erstellt den Codetext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/gethashcode/)() | Gibt den Hash‑Code für diese Instanz zurück. |
| override [InitFromString](../../aspose.barcode.complexbarcode/hibcliccombinedcodetext/initfromstring/)(string) | Initialisiert die Instanz aus dem erstellten Codetext. |

## Beispiele

Dieses Beispiel zeigt, wie man HIBC LIC mit HIBCLICCombinedCodetext codiert und dekodiert.

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

### Siehe auch

* class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


