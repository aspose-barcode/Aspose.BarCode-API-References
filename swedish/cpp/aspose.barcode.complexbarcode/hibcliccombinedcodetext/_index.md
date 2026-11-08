---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICCombinedCodetext klass"
linktitle: "HIBCLICCombinedCodetext"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICCombinedCodetext klass. Klass för kodning och avkodning av texten som är inbäddad i HIBC LIC-koden som lagrar primär och sekundär data i C++."
type: docs
weight: 700
url: /sv/cpp/aspose.barcode.complexbarcode/hibcliccombinedcodetext/
---
## HIBCLICCombinedCodetext class


Klass för kodning och avkodning av texten som är inbäddad i HIBC LIC‑koden som lagrar primära och sekundära data.

```cpp
class HIBCLICCombinedCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat [HIBCLICCombinedCodetext](./) värde. |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | Hämtar streckkodstyp. HIBC LIC-kodtext kan kodas med HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC och HIBCQRLIC kodningstyper. Standardvärde: HIBCCode39LIC. |
| [get_PrimaryData](./get_primarydata/)() const | Identifierar primär data. |
| [get_SecondaryAndAdditionalData](./get_secondaryandadditionaldata/)() const | Identifierar sekundär och ytterligare kompletterande data. |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | Hämtar streckkodstyp. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Konstruerar kodtext |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Initierar objektet från konstruerad kodtext. |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Ställer in streckkodstyp. HIBC LIC-kodtext kan kodas med HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC och HIBCQRLIC kodningstyper. Standardvärde: HIBCCode39LIC. |
| [set_PrimaryData](./set_primarydata/)(System::SharedPtr\<Aspose::BarCode::ComplexBarcode::PrimaryData\>) | Identifierar primär data. |
| [set_SecondaryAndAdditionalData](./set_secondaryandadditionaldata/)(System::SharedPtr\<Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData\>) | Identifierar sekundär och ytterligare kompletterande data. |
## Anmärkningar


Detta exempel visar hur man kodar och avkodar HIBC LIC med hjälp av [HIBCLICCombinedCodetext](./).
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

## Se även

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
