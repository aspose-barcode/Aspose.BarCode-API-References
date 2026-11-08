---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICSecondaryAndAdditionalDataCodetext klass"
linktitle: "HIBCLICSecondaryAndAdditionalDataCodetext"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICSecondaryAndAdditionalDataCodetext klass. Klass för kodning och avkodning av texten som är inbäddad i HIBC LIC-koden som lagrar sekundär data i C++."
type: docs
weight: 1000
url: /sv/cpp/aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/
---
## HIBCLICSecondaryAndAdditionalDataCodetext class


Klass för kodning och avkodning av texten som är inbäddad i HIBC LIC‑koden som lagrar sekundära data.

```cpp
class HIBCLICSecondaryAndAdditionalDataCodetext : public Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat [HIBCLICSecondaryAndAdditionalDataCodetext](./) värde. |
| [get_BarcodeType](../hibcliccomplexcodetext/get_barcodetype/)() const | Hämtar streckkodstyp. HIBC LIC-kodtext kan kodas med HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC och HIBCQRLIC kodningstyper. Standardvärde: HIBCCode39LIC. |
| [get_Data](./get_data/)() const | Identifierar sekundär och ytterligare kompletterande data. |
| [get_LinkCharacter](./get_linkcharacter/)() const | Identifierar länktecken. |
| [GetBarcodeType](../hibcliccomplexcodetext/getbarcodetype/)() override | Hämtar streckkodstyp. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Konstruerar kodtext |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [HIBCLICComplexCodetext](../hibcliccomplexcodetext/hibcliccomplexcodetext/)() |  |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/)() |  |
| [InitFromString](./initfromstring/)(System::String) override | Initierar objektet från konstruerad kodtext. |
| [set_BarcodeType](../hibcliccomplexcodetext/set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Ställer in streckkodstyp. HIBC LIC-kodtext kan kodas med HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC och HIBCQRLIC kodningstyper. Standardvärde: HIBCCode39LIC. |
| [set_Data](./set_data/)(System::SharedPtr\<SecondaryAndAdditionalData\>) | Identifierar sekundär och ytterligare kompletterande data. |
| [set_LinkCharacter](./set_linkcharacter/)(char16_t) | Identifierar länktecken. |
## Anmärkningar


///

Detta exempel visar hur man kodar och avkodar HIBC LIC med hjälp av [HIBCLICSecondaryAndAdditionalDataCodetext](./).
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

## Se även

* Class [HIBCLICComplexCodetext](../hibcliccomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
