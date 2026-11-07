---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext klasse"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext klasse. Basisklasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC LIC-code in C++."
type: docs
weight: 800
url: /nl/cpp/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class


Basisklasse voor het coderen en decoderen van de tekst die is ingebed in de HIBC LIC‑code.

```cpp
class HIBCLICComplexCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_BarcodeType](./get_barcodetype/)() const | Haalt het type barcode op. HIBC LIC codetext kan worden gecodeerd met behulp van HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC en HIBCQRLIC codeertypen. Standaardwaarde: HIBCCode39LIC. |
| [GetBarcodeType](./getbarcodetype/)() override | Haalt het type barcode op. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | Construeert codetext |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/)() |  |
| virtual [InitFromString](./initfromstring/)(System::String) | Initialiseert instantie vanuit geconstrueerde codetext. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Stelt het type barcode in. HIBC LIC codetext kan worden gecodeerd met behulp van HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC en HIBCQRLIC codeertypen. Standaardwaarde: HIBCCode39LIC. |
## Opmerkingen


Deze voorbeeld toont hoe ruwe HIBC LIC codetekst te decoderen naar een [HIBCLICComplexCodetext](./) exemplaar.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.HIBCAztecLIC))
{
     foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        HIBCLICComplexCodetext resultHIBCLICComplexCodetext = ComplexCodetextReader.TryDecodeHIBCLIC(result.CodeText);
        Console.WriteLine("BarCode Type: " + resultMaxiCodeCodetext.GetBarcodeType());
        Console.WriteLine("BarCode CodeText: " + resultMaxiCodeCodetext.GetConstructedCodetext());
    }
}
```

## Zie ook

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
