---
title: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext klasse"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext klasse. Klasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC PAS-code in C++."
type: docs
weight: 1100
url: /nl/cpp/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class


Klasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC PAS‑code.

```cpp
class HIBCPASCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [AddRecord](./addrecord/)(HIBCPASDataType, System::String) | Voegt nieuw record toe |
| [AddRecord](./addrecord/)(System::SharedPtr\<HIBCPASRecord\>) | Voegt nieuw record toe |
| [Clear](./clear/)() | Leegt de lijst met records |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [HIBCPASCodetext](./) waarde. |
| [get_BarcodeType](./get_barcodetype/)() const | Haalt het type barcode op. HIBC PAS-codetext kan worden gecodeerd met behulp van HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS en HIBCQRPAS coderings types. Standaardwaarde: HIBCCode39PAS. |
| [get_DataLocation](./get_datalocation/)() const | Identificeert de gegevenslocatie. |
| [GetBarcodeType](./getbarcodetype/)() override | Haalt het type barcode op. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construeert codetext |
| [GetHashCode](./gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| [GetRecords](./getrecords/)() | Haalt de lijst met records op |
| [HIBCPASCodetext](./hibcpascodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Initialiseert instantie vanuit geconstrueerde codetext. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Stelt het type barcode in. HIBC PAS-codetext kan worden gecodeerd met behulp van HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS en HIBCQRPAS coderings types. Standaardwaarde: HIBCCode39PAS. |
| [set_DataLocation](./set_datalocation/)(HIBCPASDataLocation) | Identificeert de gegevenslocatie. |
## Opmerkingen


Dit voorbeeld toont hoe HIBC PAS te coderen en decoderen met behulp van [HIBCPASCodetext](./).
```cpp
[C#]
HIBCPASComplexCodetext complexCodetext = new HIBCPASComplexCodetext();
complexCodetext.DataLocation = HIBCPASDataLocation.Patient;
complexCodetext.AddRecord(HIBCPASDataType.LabelerIdentificationCode, "A123");
complexCodetext.AddRecord(HIBCPASDataType.ManufacturerSerialNumber, "SERIAL123");
complexCodetext.BarcodeType = EncodeTypes.HIBCDataMatrixPAS;
using (ComplexBarcodeGenerator generator = new ComplexBarcodeGenerator(complexCodetext))
{
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.HIBCDataMatrixPAS))
    {
        reader.ReadBarCodes();
        string codetext = reader.FoundBarCodes[0].CodeText;
            HIBCPASComplexCodetext readCodetext = ComplexCodetextReader.TryDecodeHIBCPAS(codetext);
        Console.WriteLine("Data location: {0}", readCodetext.DataLocation);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[0].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[0].Data);
        Console.Write("Data type: {0}. ", readCodetext.GetRecords()[1].DataType);
        Console.WriteLine("Data: {0}", readCodetext.GetRecords()[1].Data);

    }
}
```

## Zie ook

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
