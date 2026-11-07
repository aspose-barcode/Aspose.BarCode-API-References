---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext Klasse"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext Klasse. Klasse zum Kodieren und Dekodieren des in den HIBC LIC-Code eingebetteten Textes, der Primärdaten in C++ speichert."
type: docs
weight: 900
url: /de/cpp/aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
## HIBCLICPrimaryDataCodetext class


Klasse zum Kodieren und Dekodieren des in den HIBC‑LIC‑Code eingebetteten Textes, der primäre Daten speichert.

```cpp
class HIBCLICPrimaryDataCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [HIBCLICPrimaryDataCodetext](./)-Wert entspricht. |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | Liest den Barcode-Typ. HIBC LIC Codetext kann mit den Kodierungstypen HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC und HIBCQRLIC codiert werden. Standardwert: HIBCCode39LIC. |
| [get_Data](./get_data/)() const | Identifiziert primäre Daten. |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | Liest den Barcode-Typ. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Erstellt Codetext |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Initialisiert die Instanz aus dem erstellten Codetext. |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Setzt den Barcode-Typ. HIBC LIC Codetext kann mit den Kodierungstypen HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC und HIBCQRLIC codiert werden. Standardwert: HIBCCode39LIC. |
| [set_Data](./set_data/)(System::SharedPtr\<PrimaryData\>) | Identifiziert primäre Daten. |
## Hinweise


Dieses Beispiel zeigt, wie man HIBC LIC mit [HIBCLICPrimaryDataCodetext](./) kodiert und dekodiert.
```cpp
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

## Siehe auch

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
