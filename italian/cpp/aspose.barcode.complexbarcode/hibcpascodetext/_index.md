---
title: "classe Aspose::BarCode::ComplexBarcode::HIBCPASCodetext"
linktitle: "HIBCPASCodetext"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "classe Aspose::BarCode::ComplexBarcode::HIBCPASCodetext. Classe per la codifica e decodifica del testo incorporato nel codice HIBC PAS in C++."
type: docs
weight: 1100
url: /it/cpp/aspose.barcode.complexbarcode/hibcpascodetext/
---
## HIBCPASCodetext class


Classe per la codifica e decodifica del testo incorporato nel codice HIBC PAS.

```cpp
class HIBCPASCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [AddRecord](./addrecord/)(HIBCPASDataType, System::String) | Aggiunge un nuovo record |
| [AddRecord](./addrecord/)(System::SharedPtr\<HIBCPASRecord\>) | Aggiunge un nuovo record |
| [Clear](./clear/)() | Cancella l'elenco dei record |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Restituisce un valore che indica se questa istanza è uguale a un valore [HIBCPASCodetext](./) specificato. |
| [get_BarcodeType](./get_barcodetype/)() const | Ottiene il tipo di codice a barre. Il codetext HIBC PAS può essere codificato usando i tipi di codifica HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS e HIBCQRPAS. Valore predefinito: HIBCCode39PAS. |
| [get_DataLocation](./get_datalocation/)() const | Identifica la posizione dei dati. |
| [GetBarcodeType](./getbarcodetype/)() override | Ottiene il tipo di codice a barre. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Costruisce il codetext |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [GetRecords](./getrecords/)() | Ottiene l'elenco dei record |
| [HIBCPASCodetext](./hibcpascodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Inizializza l'istanza dal codetext costruito. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Imposta il tipo di codice a barre. Il codetext HIBC PAS può essere codificato usando i tipi di codifica HIBCCode39PAS, HIBCCode128PAS, HIBCAztec:PAS, HIBCDataMatrixPAS e HIBCQRPAS. Valore predefinito: HIBCCode39PAS. |
| [set_DataLocation](./set_datalocation/)(HIBCPASDataLocation) | Identifica la posizione dei dati. |
## Osservazioni


Questo esempio mostra come codificare e decodificare HIBC PAS usando [HIBCPASCodetext](./).
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

## Vedi anche

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
