---
title: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext klass"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext klass. Klass för kodning och avkodning av texten som är inbäddad i HIBC PAS-koden i C++."
type: docs
weight: 1100
url: /sv/cpp/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class


Klass för kodning och avkodning av texten som är inbäddad i HIBC PAS‑koden.

```cpp
class HIBCPASCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddRecord](./addrecord/)(HIBCPASDataType, System::String) | Lägger till ny post |
| [AddRecord](./addrecord/)(System::SharedPtr\<HIBCPASRecord\>) | Lägger till ny post |
| [Clear](./clear/)() | Rensar postlista |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat [HIBCPASCodetext](./)-värde. |
| [get_BarcodeType](./get_barcodetype/)() const | Hämtar streckkodstyp. HIBC PAS-kodtext kan kodas med HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS och HIBCQRPAS kodningstyper. Standardvärde: HIBCCode39PAS. |
| [get_DataLocation](./get_datalocation/)() const | Identifierar dataplats. |
| [GetBarcodeType](./getbarcodetype/)() override | Hämtar streckkodstyp. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Konstruerar kodtext |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [GetRecords](./getrecords/)() | Hämtar postlista |
| [HIBCPASCodetext](./hibcpascodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Initierar objektet från konstruerad kodtext. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Ställer in streckkodstyp. HIBC PAS-kodtext kan kodas med HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS och HIBCQRPAS kodningstyper. Standardvärde: HIBCCode39PAS. |
| [set_DataLocation](./set_datalocation/)(HIBCPASDataLocation) | Identifierar dataplats. |
## Anmärkningar


Detta exempel visar hur man kodar och avkodar HIBC PAS med hjälp av [HIBCPASCodetext](./).
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

## Se även

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
