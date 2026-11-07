---
title: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator class"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator class. ComplexBarcodeGenerator voor backend complexe barcode (bijv. SwissQR) afbeeldinggeneratie in C++."
type: docs
weight: 300
url: /nl/cpp/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class


[ComplexBarcodeGenerator](./) for backend complex barcode (e.g. SwissQR) images generation.

```cpp
class ComplexBarcodeGenerator : public System::IDisposable
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/)(System::SharedPtr\<IComplexCodetext\>) | Maakt een instantie van [ComplexBarcodeGenerator](./). |
| [Dispose](./dispose/)() override | Ruim eventuele gebruikte bronnen op. |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Genereert complexe barcode-afbeelding met de huidige instellingen. |
| [get_Parameters](./get_parameters/)() | [Generation](../../aspose.barcode.generation/) parameters. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, Generation::BarCodeImageFormat) | Genereert en slaat complexe barcode-afbeelding op met de huidige instellingen. |
| [Save](./save/)(System::String, Generation::BarCodeImageFormat) | Genereert en slaat complexe barcode-afbeelding op met de huidige instellingen. |
| [Save](./save/)(System::String) | Genereert en slaat complexe barcode-afbeelding op met de huidige instellingen. |
## Opmerkingen


Dit voorbeeld laat zien hoe je een SwissQR-afbeelding maakt en opslaat.
```cpp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // initialiseer de rest van de velden
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

## Zie ook

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
