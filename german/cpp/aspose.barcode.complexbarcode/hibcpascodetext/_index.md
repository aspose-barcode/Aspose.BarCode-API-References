---
title: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext Klasse"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::HIBCPASCodetext Klasse. Klasse zum Codieren und Dekodieren des in den HIBC PAS-Code eingebetteten Textes in C++."
type: docs
weight: 1100
url: /de/cpp/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class


Klasse zum Kodieren und Dekodieren des in den HIBC‑PAS‑Code eingebetteten Textes.

```cpp
class HIBCPASCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [AddRecord](./addrecord/)(HIBCPASDataType, System::String) | Fügt einen neuen Datensatz hinzu |
| [AddRecord](./addrecord/)(System::SharedPtr\<HIBCPASRecord\>) | Fügt einen neuen Datensatz hinzu |
| [Clear](./clear/)() | Leert die Datensatzliste |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [HIBCPASCodetext](./) Wert entspricht. |
| [get_BarcodeType](./get_barcodetype/)() const | Liest den Barcode-Typ. HIBC PAS-Codetext kann mit den Kodierungstypen HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS und HIBCQRPAS codiert werden. Standardwert: HIBCCode39PAS. |
| [get_DataLocation](./get_datalocation/)() const | Identifiziert den Datenort. |
| [GetBarcodeType](./getbarcodetype/)() override | Liest den Barcode-Typ. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Erstellt Codetext |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [GetRecords](./getrecords/)() | Liest die Datensatzliste |
| [HIBCPASCodetext](./hibcpascodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Initialisiert die Instanz aus dem erstellten Codetext. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Setzt den Barcode-Typ. HIBC PAS-Codetext kann mit den Kodierungstypen HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS und HIBCQRPAS codiert werden. Standardwert: HIBCCode39PAS. |
| [set_DataLocation](./set_datalocation/)(HIBCPASDataLocation) | Identifiziert den Datenort. |
## Hinweise


Dieses Beispiel zeigt, wie man HIBC PAS mit [HIBCPASCodetext](./) codiert und decodiert.
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

## Siehe auch

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
