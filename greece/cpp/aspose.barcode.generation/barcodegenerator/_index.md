---
title: "Aspose::BarCode::Generation::BarcodeGenerator κλάση"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::Generation::BarcodeGenerator κλάση. BarcodeGenerator για τη δημιουργία εικόνων barcode backend σε C++."
type: docs
weight: 400
url: /el/cpp/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class


[BarcodeGenerator](./) for backend barcode images generation.

```cpp
class BarcodeGenerator : public System::IDisposable
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>) | Δημιουργεί μια παρουσία του [BarcodeGenerator](./). |
| [BarcodeGenerator](./barcodegenerator/)(System::SharedPtr\<BaseEncodeType\>, System::String) | Δημιουργεί μια παρουσία του [BarcodeGenerator](./). |
| [Dispose](./dispose/)() override | Καθαρίζει τυχόν πόρους που χρησιμοποιούνται. |
| [ExportToXml](./exporttoxml/)(System::String) | Εξάγει τις ιδιότητες του [BarCode](../../aspose.barcode/) σε καθορισμένο αρχείο xml |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | Εξάγει τις ιδιότητες του [BarCode](../../aspose.barcode/) σε καθορισμένη ροή xml |
| [GenerateBarCodeImage](./generatebarcodeimage/)() | Δημιουργήστε την εικόνα barcode σύμφωνα με τις τρέχουσες ρυθμίσεις. |
| [get_BarcodeType](./get_barcodetype/)() | Τύπος συμβολισμού barcode. |
| [get_CodeText](./get_codetext/)() | Κείμενο προς κωδικοποίηση. |
| [get_Parameters](./get_parameters/)() const | Παράμετροι [Generation](../). |
| static [ImportFromXml](./importfromxml/)(System::String) | Εισάγει τις ιδιότητες [BarCode](../../aspose.barcode/) από το καθορισμένο αρχείο xml και δημιουργεί ένα αντικείμενο [BarcodeGenerator](./). |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Εισάγει τις ιδιότητες [BarCode](../../aspose.barcode/) από το καθορισμένο ροή xml και δημιουργεί ένα αντικείμενο [BarcodeGenerator](./). |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>, BarCodeImageFormat) | Αποθηκεύστε την εικόνα barcode σε ροή σε συγκεκριμένη μορφή. |
| [Save](./save/)(System::String, BarCodeImageFormat) | Αποθηκεύστε την εικόνα barcode σε συγκεκριμένο αρχείο σε συγκεκριμένη μορφή. |
| [Save](./save/)(System::String) | Αποθηκεύστε την εικόνα barcode σε συγκεκριμένο αρχείο. |
| [set_BarcodeType](./set_barcodetype/)(System::SharedPtr\<BaseEncodeType\>) | Τύπος συμβολισμού barcode. |
| [set_CodeText](./set_codetext/)(System::String) | Κείμενο προς κωδικοποίηση. |
| [SetCodeText](./setcodetext/)(System::ArrayPtr\<uint8_t\>) | Ορίστε το codetext ως ακολουθία byte. |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>) |  |
| [SetCodeText](./setcodetext/)(System::String, System::SharedPtr\<System::Text::Encoding\>, bool) |  |
## Σχόλια


υποστηριζόμενοι συμβολισμοί: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα barcode.
```cpp
[C#]
      using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
      {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
