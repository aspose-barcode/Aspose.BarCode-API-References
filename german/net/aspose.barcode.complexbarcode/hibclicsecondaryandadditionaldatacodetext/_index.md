---
title: "Klasse HIBCLICSecondaryAndAdditionalDataCodetext"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Aspose.BarCode.ComplexBarcode.HIBCLICSecondaryAndAdditionalDataCodetext Klasse. Klasse zum Kodieren und Dekodieren des in den HIBC‑LIC‑Code eingebetteten Textes, der Sekundärdaten speichert"
type: docs
weight: 590
url: /de/net/aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/
---
## HIBCLICSecondaryAndAdditionalDataCodetext class

Klasse zum Codieren und Dekodieren des in den HIBC‑LIC‑Code eingebetteten Textes, der Sekundärdaten speichert.

```csharp
public class HIBCLICSecondaryAndAdditionalDataCodetext : HIBCLICComplexCodetext
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [HIBCLICSecondaryAndAdditionalDataCodetext](hibclicsecondaryandadditionaldatacodetext/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/barcodetype/) { get; set; } | Liest oder setzt den Barcode‑Typ. HIBC‑LIC‑Codetext kann mit den Kodierungstypen HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC und HIBCQRLIC kodiert werden. Standardwert: HIBCCode39LIC. |
| [Data](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/data/) { get; set; } | Identifiziert sekundäre und zusätzliche Ergänzungsdaten. |
| [LinkCharacter](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/linkcharacter/) { get; set; } | Identifiziert das Verbindungszeichen. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/equals/)(object) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `HIBCLICSecondaryAndAdditionalDataCodetext`‑Wert gleich ist. |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/hibcliccomplexcodetext/getbarcodetype/)() | Liest den Barcode‑Typ. |
| override [GetConstructedCodetext](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/getconstructedcodetext/)() | Erstellt den Codetext |
| override [GetHashCode](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/gethashcode/)() | Gibt den Hash‑Code für diese Instanz zurück. |
| override [InitFromString](../../aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/initfromstring/)(string) | Initialisiert die Instanz aus dem erstellten Codetext. |

## Beispiele

Dieses Beispiel zeigt, wie man HIBC‑LIC mit HIBCLICSecondaryAndAdditionalDataCodetext kodiert und dekodiert.

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

### Siehe auch

* class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


