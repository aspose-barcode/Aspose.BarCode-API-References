---
title: "Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext class"
linktitle: "HIBCLICComplexCodetext"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::HIBCLICComplexCodetext class. Basisklasse für das Kodieren und Dekodieren des im HIBC LIC-Code eingebetteten Textes in C++."
type: docs
weight: 800
url: /de/cpp/aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
## HIBCLICComplexCodetext class


Basisklasse zum Kodieren und Dekodieren des in den HIBC‑LIC‑Code eingebetteten Textes.

```cpp
class HIBCLICComplexCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_BarcodeType](./get_barcodetype/)() const | Liest den Barcode-Typ. HIBC LIC Codetext kann mit den Kodierungstypen HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC und HIBCQRLIC codiert werden. Standardwert: HIBCCode39LIC. |
| [GetBarcodeType](./getbarcodetype/)() override | Liest den Barcode-Typ. |
| virtual [GetConstructedCodetext](./getconstructedcodetext/)() | Erstellt Codetext |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/)() |  |
| virtual [InitFromString](./initfromstring/)(System::String) | Initialisiert die Instanz aus dem erstellten Codetext. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<Generation::BaseEncodeType\>) | Setzt den Barcode-Typ. HIBC LIC Codetext kann mit den Kodierungstypen HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC und HIBCQRLIC codiert werden. Standardwert: HIBCCode39LIC. |
## Hinweise


Dieses Beispiel zeigt, wie man rohen HIBC LIC-Kodetext in eine [HIBCLICComplexCodetext](./)-Instanz dekodiert.
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

## Siehe auch

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
