---
title: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator class"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::ComplexBarcode::ComplexBarcodeGenerator class. ComplexBarcodeGenerator για δημιουργία εικόνων πολύπλοκου barcode (π.χ. SwissQR) στο backend σε C++."
type: docs
weight: 300
url: /el/cpp/aspose.barcode.complexbarcode/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class


[ComplexBarcodeGenerator](./) for backend complex barcode (e.g. SwissQR) images generation.

```cpp
class ComplexBarcodeGenerator : public System::IDisposable
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/)(System::SharedPtr\<IComplexCodetext\>) | Δημιουργεί μια παρουσία του [ComplexBarcodeGenerator](./). |
| [Dispose](./dispose/)() override | Καθαρίζει τυχόν πόρους που χρησιμοποιούνται. |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Δημιουργεί εικόνα πολύπλοκου barcode με τις τρέχουσες ρυθμίσεις. |
| [get_Parameters](./get_parameters/)() | [Δημιουργία](../../aspose.barcode.generation/) παράμετροι. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, Generation::BarCodeImageFormat) | Δημιουργεί και αποθηκεύει εικόνα πολύπλοκου barcode με τις τρέχουσες ρυθμίσεις. |
| [Save](./save/)(System::String, Generation::BarCodeImageFormat) | Δημιουργεί και αποθηκεύει εικόνα πολύπλοκου barcode με τις τρέχουσες ρυθμίσεις. |
| [Save](./save/)(System::String) | Δημιουργεί και αποθηκεύει εικόνα πολύπλοκου barcode με τις τρέχουσες ρυθμίσεις. |
## Σχόλια


Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα SwissQR.
```cpp
[C#]
  var swissQRCodetext = new SwissQRCodetext();
  swissQRCodetext.Bill.Account = "Account";
  swissQRCodetext.Bill.BillInformation = "BillInformation";
  // αρχικοποιήστε τα υπόλοιπα πεδία
  using (var cg = new ComplexBarcodeGenerator(swissQRCodetext))
  {
    var res = cg.GenerateBarCodeImage();
  }
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
