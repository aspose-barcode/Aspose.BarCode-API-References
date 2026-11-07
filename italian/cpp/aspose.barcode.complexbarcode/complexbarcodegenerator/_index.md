---
title: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator classe"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator classe. ComplexBarcodeGenerator per la generazione di immagini di codici a barre complessi backend (ad es. SwissQR) in C++."
type: docs
weight: 300
url: /it/cpp/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class


[ComplexBarcodeGenerator](./) for backend complex barcode (e.g. SwissQR) images generation.

```cpp
class ComplexBarcodeGenerator : public System::IDisposable
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/)(System::SharedPtr\<IComplexCodetext\>) | Crea un'istanza di [ComplexBarcodeGenerator](./). |
| [Dispose](./dispose/)() override | Libera tutte le risorse in uso. |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Genera l'immagine del codice a barre complesso con le impostazioni correnti. |
| [get_Parameters](./get_parameters/)() | [Generation](../../aspose.barcode.generation/) parametri. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, Generation::BarCodeImageFormat) | Genera e salva l'immagine del codice a barre complesso con le impostazioni correnti. |
| [Save](./save/)(System::String, Generation::BarCodeImageFormat) | Genera e salva l'immagine del codice a barre complesso con le impostazioni correnti. |
| [Save](./save/)(System::String) | Genera e salva l'immagine del codice a barre complesso con le impostazioni correnti. |
## Osservazioni


Questo esempio mostra come creare e salvare un'immagine SwissQR.
```cpp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // inizializza il resto dei campi
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

## Vedi anche

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
