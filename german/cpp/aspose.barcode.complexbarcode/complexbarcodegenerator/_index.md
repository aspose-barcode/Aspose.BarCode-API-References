---
title: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator Klasse"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator Klasse. ComplexBarcodeGenerator für die Erzeugung von Backend-Komplex-Barcode-Bildern (z. B. SwissQR) in C++."
type: docs
weight: 300
url: /de/cpp/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class


[ComplexBarcodeGenerator](./) for backend complex barcode (e.g. SwissQR) images generation.

```cpp
class ComplexBarcodeGenerator : public System::IDisposable
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/)(System::SharedPtr\<IComplexCodetext\>) | Erstellt eine Instanz von [ComplexBarcodeGenerator](./). |
| [Dispose](./dispose/)() override | Räume alle verwendeten Ressourcen auf. |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Erzeugt ein komplexes Barcode-Bild mit den aktuellen Einstellungen. |
| [get_Parameters](./get_parameters/)() | [Generierung](../../aspose.barcode.generation/) Parameter. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, Generation::BarCodeImageFormat) | Erzeugt und speichert ein komplexes Barcode-Bild mit den aktuellen Einstellungen. |
| [Save](./save/)(System::String, Generation::BarCodeImageFormat) | Erzeugt und speichert ein komplexes Barcode-Bild mit den aktuellen Einstellungen. |
| [Save](./save/)(System::String) | Erzeugt und speichert ein komplexes Barcode-Bild mit den aktuellen Einstellungen. |
## Hinweise


Dieses Beispiel zeigt, wie man ein SwissQR-Bild erstellt und speichert.
```cpp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // Initialisiere die restlichen Felder
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

## Siehe auch

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
