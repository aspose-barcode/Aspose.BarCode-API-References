---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICSecondaryAndAdditionalDataCodetext klasse"
linktitle: "HIBCLICSecondaryAndAdditionalDataCodetext"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICSecondaryAndAdditionalDataCodetext klasse. Klasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC LIC codetext die secundaire gegevens opslaat in C++."
type: docs
weight: 1000
url: /nl/cpp/aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/
---
## HIBCLICSecondaryAndAdditionalDataCodetext class


Klasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC LIC‑code die secundaire gegevens opslaat.

```cpp
class HIBCLICSecondaryAndAdditionalDataCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [HIBCLICSecondaryAndAdditionalDataCodetext](./) waarde. |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | Haalt het type barcode op. HIBC LIC codetext kan worden gecodeerd met behulp van HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC en HIBCQRLIC codeertypen. Standaardwaarde: HIBCCode39LIC. |
| [get_Data](./get_data/)() const | Identificeert secundaire en aanvullende data. |
| [get_LinkCharacter](./get_linkcharacter/)() const | Identificeert koppelingsteken. |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | Haalt het type barcode op. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construeert codetext |
| [GetHashCode](./gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Initialiseert instantie vanuit geconstrueerde codetext. |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Stelt het type barcode in. HIBC LIC codetext kan worden gecodeerd met behulp van HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC en HIBCQRLIC codeertypen. Standaardwaarde: HIBCCode39LIC. |
| [set_Data](./set_data/)(System::SharedPtr\<SecondaryAndAdditionalData\>) | Identificeert secundaire en aanvullende data. |
| [set_LinkCharacter](./set_linkcharacter/)(char16_t) | Identificeert koppelingsteken. |
## Opmerkingen


///

Dit voorbeeld toont hoe HIBC LIC te coderen en decoderen met behulp van [HIBCLICSecondaryAndAdditionalDataCodetext](./).
```cpp
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

## Zie ook

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
