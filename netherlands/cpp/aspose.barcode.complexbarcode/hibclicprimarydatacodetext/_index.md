---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext klasse"
linktitle: "HIBCLICPrimaryDataCodetext"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICPrimaryDataCodetext klasse. Klasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC LIC-code die primaire gegevens opslaat in C++."
type: docs
weight: 900
url: /nl/cpp/aspose.barcode.complexbarcode/hibclicprimarydatacodetext/
---
## HIBCLICPrimaryDataCodetext class


Klasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC LIC‑code die primaire gegevens opslaat.

```cpp
class HIBCLICPrimaryDataCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [HIBCLICPrimaryDataCodetext](./) waarde. |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | Haalt het type barcode op. HIBC LIC codetext kan worden gecodeerd met behulp van HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC en HIBCQRLIC codeertypen. Standaardwaarde: HIBCCode39LIC. |
| [get_Data](./get_data/)() const | Identificeert primaire gegevens. |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | Haalt het type barcode op. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construeert codetext |
| [GetHashCode](./gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Initialiseert instantie vanuit geconstrueerde codetext. |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Stelt het type barcode in. HIBC LIC codetext kan worden gecodeerd met behulp van HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC en HIBCQRLIC codeertypen. Standaardwaarde: HIBCCode39LIC. |
| [set_Data](./set_data/)(System::SharedPtr\<PrimaryData\>) | Identificeert primaire gegevens. |
## Opmerkingen


Dit voorbeeld toont hoe HIBC LIC te coderen en decoderen met behulp van [HIBCLICPrimaryDataCodetext](./).
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

## Zie ook

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
