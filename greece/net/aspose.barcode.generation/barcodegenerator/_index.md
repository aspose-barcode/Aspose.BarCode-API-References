---
title: "Κλάση BarcodeGenerator"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Κλάση Aspose.BarCode.Generation.BarcodeGenerator. BarcodeGenerator για δημιουργία εικόνων barcode στο backend"
type: docs
weight: 1000
url: /el/net/aspose.barcode.generation/barcodegenerator/
---
## BarcodeGenerator class

BarcodeGenerator για τη δημιουργία εικόνων barcode στο backend.

υποστηριζόμενοι συμβολισμοί: 1D: Codabar, Code11, Code128, Code39, Code39FullASCII Code93, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

```csharp
public sealed class BarcodeGenerator : Component
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [BarcodeGenerator](barcodegenerator/#constructor)(BaseEncodeType) | Δημιουργεί ένα στιγμιότυπο του BarcodeGenerator. |
| [BarcodeGenerator](barcodegenerator/#constructor_1)(BaseEncodeType, string) | Δημιουργεί ένα στιγμιότυπο του BarcodeGenerator. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BarcodeType](../../aspose.barcode.generation/barcodegenerator/barcodetype/) { get; set; } | Τύπος συμβολισμού Barcode. |
| [CodeText](../../aspose.barcode.generation/barcodegenerator/codetext/) { get; set; } | Κείμενο προς κωδικοποίηση. |
| [Parameters](../../aspose.barcode.generation/barcodegenerator/parameters/) { get; } | Παράμετροι δημιουργίας. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml)(Stream) | Εισάγει τις ιδιότητες BarCode από το καθορισμένο xml-stream και δημιουργεί ένα στιγμιότυπο του BarcodeGenerator. |
| static [ImportFromXml](../../aspose.barcode.generation/barcodegenerator/importfromxml/#importfromxml_1)(string) | Εισάγει τις ιδιότητες BarCode από το καθορισμένο xml-file και δημιουργεί ένα στιγμιότυπο του BarcodeGenerator. |
| [DrawWpf](../../aspose.barcode.generation/barcodegenerator/drawwpf/)(DrawingContext) | Σχεδιάζει την εικόνα barcode σε καμβά WPF. |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml)(Stream) | Εξάγει τις ιδιότητες BarCode στο καθορισμένο xml-stream |
| [ExportToXml](../../aspose.barcode.generation/barcodegenerator/exporttoxml/#exporttoxml_1)(string) | Εξάγει τις ιδιότητες BarCode στο καθορισμένο xml-file |
| [GenerateBarCodeImage](../../aspose.barcode.generation/barcodegenerator/generatebarcodeimage/)() | Δημιουργεί την εικόνα barcode με τις τρέχουσες ρυθμίσεις. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_1)(string) | Αποθηκεύει την εικόνα barcode σε συγκεκριμένο αρχείο. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save)(Stream, BarCodeImageFormat) | Αποθηκεύει την εικόνα barcode σε ροή σε συγκεκριμένη μορφή. |
| [Save](../../aspose.barcode.generation/barcodegenerator/save/#save_2)(string, BarCodeImageFormat) | Αποθηκεύει την εικόνα barcode σε συγκεκριμένο αρχείο σε συγκεκριμένη μορφή. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext)(byte[]) | Ορίζει το codetext ως ακολουθία byte. |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_1)(string, Encoding) | Κωδικοποιεί το Unicode **codeText** σε ακολουθία byte χρησιμοποιώντας την καθορισμένη **encoding**. Το UTF-8 είναι η πιο κοινή κωδικοποίηση. Εάν η κωδικοποίηση το υποστηρίζει, η λειτουργία εισάγει αυτόματα ένα [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding). |
| [SetCodeText](../../aspose.barcode.generation/barcodegenerator/setcodetext/#setcodetext_2)(string, Encoding, bool) | Κωδικοποιεί το Unicode **codeText** σε ακολουθία byte χρησιμοποιώντας την καθορισμένη **encoding**. Το UTF-8 είναι η πιο κοινή κωδικοποίηση. Εάν η κωδικοποίηση το υποστηρίζει και το **insertBOM** είναι ορισμένο σε `true`, η λειτουργία περιλαμβάνει ένα [byte order mark (BOM)](https://en.wikipedia.org/wiki/Byte_order_mark#Byte-order_marks_by_encoding). |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα barcode.

```csharp
[C#]
  using(var generator = new BarcodeGenerator(EncodeTypes.Code128))
  {
      generator.CodeText = "123ABC";
      generator.Save("code128.png");
  }
```

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


