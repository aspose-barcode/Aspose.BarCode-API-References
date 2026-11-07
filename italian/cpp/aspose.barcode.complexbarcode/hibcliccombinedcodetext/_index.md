---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICCombinedCodetext classe"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICCombinedCodetext classe. Classe per la codifica e decodifica del testo incorporato nel codice HIBC LIC che memorizza dati primari e secondari in C++."
type: docs
weight: 700
url: /it/cpp/aspose.barcode.complexbarcode/hibcliccombinedcodetext/
---
## HIBCLICCombinedCodetext class


Classe per la codifica e decodifica del testo incorporato nel codice HIBC LIC che memorizza dati primari e secondari.

```cpp
class HIBCLICCombinedCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Restituisce un valore che indica se questa istanza è uguale a un valore [HIBCLICCombinedCodetext](./) specificato. |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | Ottiene il tipo di codice a barre. Il codetext HIBC LIC può essere codificato usando i tipi di codifica HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC e HIBCQRLIC. Valore predefinito: HIBCCode39LIC. |
| [get_PrimaryData](./get_primarydata/)() const | Identifica i dati primari. |
| [get_SecondaryAndAdditionalData](./get_secondaryandadditionaldata/)() const | Identifica i dati secondari e supplementari aggiuntivi. |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | Ottiene il tipo di codice a barre. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Costruisce il codetext |
| [GetHashCode](./gethashcode/)() const override | Restituisce il codice hash per questa istanza. |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Inizializza l'istanza dal codetext costruito. |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Imposta il tipo di codice a barre. Il codetext HIBC LIC può essere codificato usando i tipi di codifica HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC e HIBCQRLIC. Valore predefinito: HIBCCode39LIC. |
| [set_PrimaryData](./set_primarydata/)(System::SharedPtr\<Aspose::BarCode::ComplexBarcode::PrimaryData\>) | Identifica i dati primari. |
| [set_SecondaryAndAdditionalData](./set_secondaryandadditionaldata/)(System::SharedPtr\<Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData\>) | Identifica i dati secondari e supplementari aggiuntivi. |
## Osservazioni


Questo esempio mostra come codificare e decodificare HIBC LIC usando [HIBCLICCombinedCodetext](./).
```cpp
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

## Vedi anche

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
