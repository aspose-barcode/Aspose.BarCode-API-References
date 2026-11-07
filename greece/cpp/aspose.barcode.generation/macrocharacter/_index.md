---
title: "enum"
linktitle: "MacroCharacter"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " enum. Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. Ο Macro χαρακτήρας 05 μεταφράζεται σε \"[)>\\u001E05\\u001D\" ως κεφαλίδα αποκωδικοποιημένων δεδομένων και \"\\u001E\\u0004\" ως υποσέλιδο αποκωδικοποιημένων δεδομένων. Ο Macro χαρακτήρας 06 μεταφράζεται σε \"[)>\\u001E06\\u001D\" ως κεφαλίδα αποκωδικοποιημένων δεδομένων και \"\\u001E\\u0004\" ως υποσέλιδο αποκωδικοποιημένων δεδομένων σε C++."
type: docs
weight: 7300
url: /el/cpp/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enum


Οι τιμές των Μακροχαρακτήρων 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. Ο Μακροχαρακτήρας 05 μεταφράζεται σε "[)>\u001E05\u001D" ως κεφαλίδα αποκωδικοποιημένων δεδομένων και "\u001E\u0004" ως υποσέλιδο αποκωδικοποιημένων δεδομένων. Ο Μακροχαρακτήρας 06 μεταφράζεται σε "[)>\u001E06\u001D" ως κεφαλίδα αποκωδικοποιημένων δεδομένων και "\u001E\u0004" ως υποσέλιδο αποκωδικοποιημένων δεδομένων.

```cpp
enum class MacroCharacter
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Κανένα | 0 | Κανένας από τους Macro Characters δεν προστίθεται στα δεδομένα του barcode. |
| Macro05 | 5 | Ο Macro χαρακτήρας 05 προστίθεται στα δεδομένα του barcode στην πρώτη θέση. Ο αναγνωριστής δεδομένων GS1 ISO 15434 μεταφράζεται σε "[)>\u001E05\u001D" ως κεφαλίδα αποκωδικοποιημένων δεδομένων και "\u001E\u0004" ως υποσέλιδο αποκωδικοποιημένων δεδομένων. |
| Macro06 | 6 | Ο Macro χαρακτήρας 06 προστίθεται στα δεδομένα του barcode στην πρώτη θέση. Ο αναγνωριστής δεδομένων ASC MH10 ISO 15434 μεταφράζεται σε "[)>\u001E06\u001D" ως κεφαλίδα αποκωδικοποιημένων δεδομένων και "\u001E\u0004" ως υποσέλιδο αποκωδικοποιημένων δεδομένων. |

## Σχόλια


Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε Macro Characters σε MicroPdf417 και DataMatrix.
```cpp
[C#]
//Για να δημιουργήσετε αυτόματα αναγνωρισμένο μήνυμα GS1 όπως αυτό "(10)123ABC(10)123ABC" σε μορφή ISO 15434, χρειάζεστε:
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "10123ABC\u001D10123ABC");
generator.Parameters.Barcode.DataMatrix.MacroCharacters = MacroCharacter.Macro05;
BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1DataMatrix);
foreach (BarCodeResult result in reader.ReadBarCodes())
    Console.WriteLine("BarCode CodeText: " + result.CodeText);

//Κωδικοποιεί το MicroPdf417 με Macro 05 τη συμβολοσειρά: "[)>\u001E05\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro05;
    using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
      foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);

//Κωδικοποιεί το MicroPdf417 με Macro 06 τη συμβολοσειρά: "[)>\u001E06\u001Dabcde1234\u001E\u0004"
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "abcde1234");
generator.Parameters.Barcode.Pdf417.MacroCharacters = MacroCharacter.Macro06;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
```

## Δείτε επίσης

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
