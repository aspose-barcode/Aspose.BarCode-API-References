---
title: "Klasse HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.ComplexBarcode.HIBCLICPrimaryDataCodetext Klasse. Klasse zum Codieren und Dekodieren des in den HIBC LIC-Code eingebetteten Textes, der Primärdaten speichert"
type: docs
weight: 580
url: /de/net/aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
## HIBCLICPrimaryDataCodetext class

Klasse zum Codieren und Dekodieren des in den HIBC‑LIC‑Code eingebetteten Textes, der Primärdaten speichert.

```csharp
public class HIBCLICPrimaryDataCodetext : HIBCLICComplexCodetext
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [HIBCLICPrimaryDataCodetext](hibclicprimarydatacodetext/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Liest oder setzt den Barcode‑Typ. HIBC‑LIC‑Codetext kann mit den Kodierungstypen HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC und HIBCQRLIC kodiert werden. Standardwert: HIBCCode39LIC. |
| [Data](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/data/) { get; set; } | Identifiziert primäre Daten. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/equals/)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `HIBCLICPrimaryDataCodetext`-Wert entspricht. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Liest den Barcode‑Typ. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/getconstructedcodetext/)() | Erstellt den Codetext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/gethashcode/)() | Gibt den Hash‑Code für diese Instanz zurück. |
| override [InitFromString](../../aspose.barcode.complexbarcode/hibclicprimarydatacodetext/initfromstring/)(string) | Initialisiert die Instanz aus dem erstellten Codetext. |

## Beispiele

Dieses Beispiel zeigt, wie man HIBC LIC mit HIBCLICPrimaryDataCodetext kodiert und dekodiert.

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

### Siehe auch

* class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


