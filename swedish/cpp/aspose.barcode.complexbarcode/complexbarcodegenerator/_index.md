---
title: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator klass"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator klass. ComplexBarcodeGenerator för generering av bilder av komplexa streckkoder i backend (t.ex. SwissQR) i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class


[ComplexBarcodeGenerator](./) for backend complex barcode (e.g. SwissQR) images generation.

```cpp
class ComplexBarcodeGenerator : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/)(System::SharedPtr\<IComplexCodetext\>) | Skapar en instans av [ComplexBarcodeGenerator](./). |
| [Dispose](./dispose/)() override | Rensa upp eventuella resurser som används. |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Genererar bild av komplex streckkod med aktuella inställningar. |
| [get_Parameters](./get_parameters/)() | [Generation](../../aspose.barcode.generation/) parametrar. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, Generation::BarCodeImageFormat) | Genererar och sparar bild av komplex streckkod med aktuella inställningar. |
| [Save](./save/)(System::String, Generation::BarCodeImageFormat) | Genererar och sparar bild av komplex streckkod med aktuella inställningar. |
| [Save](./save/)(System::String) | Genererar och sparar bild av komplex streckkod med aktuella inställningar. |
## Anmärkningar


Detta exempel visar hur man skapar och sparar en SwissQR-bild.
```cpp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // initiera resten av fälten
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

## Se även

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
