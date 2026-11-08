---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext klass"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext klass. Basisklass för kodning och avkodning av text som är inbäddad i HIBC LIC-koden i C++."
type: docs
weight: 800
url: /sv/cpp/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class


Bas‑klass för kodning och avkodning av texten som är inbäddad i HIBC LIC‑koden.

```cpp
class HIBCLICComplexCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_BarcodeType](./get_barcodetype/)() const | Hämtar streckkodstyp. HIBC LIC-kodtext kan kodas med HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC och HIBCQRLIC kodningstyper. Standardvärde: HIBCCode39LIC. |
| [GetBarcodeType](./getbarcodetype/)() override | Hämtar streckkodstyp. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | Konstruerar kodtext |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/)() |  |
| virtual [InitFromString](./initfromstring/)(System::String) | Initierar objektet från konstruerad kodtext. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Ställer in streckkodstyp. HIBC LIC-kodtext kan kodas med HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC och HIBCQRLIC kodningstyper. Standardvärde: HIBCCode39LIC. |
## Anmärkningar


Detta exempel visar hur man avkodar rå HIBC LIC-kodtext till en [HIBCLICComplexCodetext](./)-instans.
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

## Se även

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
