---
title: "Απαρίθμηση MacroCharacter"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Απαρίθμηση Aspose.BarCode.Generation.MacroCharacter. Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. Ο χαρακτήρας Macro 05 μετατρέπεται σε u001E05u001D ως κεφαλίδα αποκωδικοποιημένων δεδομένων και u001Eu0004 ως υποσέλιδο δεδομένων. Ο χαρακτήρας Macro 06 μετατρέπεται σε u001E06u001D ως κεφαλίδα αποκωδικοποιημένων δεδομένων και u001Eu0004 ως υποσέλιδο δεδομένων."
type: docs
weight: 1450
url: /el/net/aspose.barcode.generation/macrocharacter/
---
## MacroCharacter enumeration

Οι τιμές των Μακροχαρακτήρων 05 και 06 χρησιμοποιούνται για να επιτευχθεί πιο συμπαγής κωδικοποίηση σε ειδικές λειτουργίες. Ο Μακροχαρακτήρας 05 μεταφράζεται σε "[)&gt;\u001E05\u001D" ως κεφαλίδα αποκωδικοποιημένων δεδομένων και "\u001E\u0004" ως υποσέλιδο αποκωδικοποιημένων δεδομένων. Ο Μακροχαρακτήρας 06 μεταφράζεται σε "[)&gt;\u001E06\u001D" ως κεφαλίδα αποκωδικοποιημένων δεδομένων και "\u001E\u0004" ως υποσέλιδο αποκωδικοποιημένων δεδομένων.

```csharp
public enum MacroCharacter
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| None | `0` | Κανένας από τους Macro Characters δεν προστίθεται στα δεδομένα του barcode. |
| Macro05 | `5` | Ο χαρακτήρας Macro 05 προστίθεται στα δεδομένα του barcode στην πρώτη θέση. Ο ταυτοποιητής δεδομένων GS1 ISO 15434 μετατρέπεται σε "[)&gt;\u001E05\u001D" ως κεφαλίδα αποκωδικοποιημένων δεδομένων και "\u001E\u0004" ως υποσέλιδο δεδομένων. |
| Macro06 | `6` | Ο χαρακτήρας Macro 06 προστίθεται στα δεδομένα του barcode στην πρώτη θέση. Ο ταυτοποιητής δεδομένων ASC MH10 ISO 15434 μετατρέπεται σε "[)&gt;\u001E06\u001D" ως κεφαλίδα αποκωδικοποιημένων δεδομένων και "\u001E\u0004" ως υποσέλιδο δεδομένων. |

## Παραδείγματα

Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε Macro Characters σε MicroPdf417 και DataMatrix.

```csharp
[C#]
//Για να δημιουργήσετε ένα αυτόματα αναγνωρισμένο μήνυμα GS1 όπως αυτό "(10)123ABC(10)123ABC" σε μορφή ISO 15434, χρειάζεστε:
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

### Δείτε επίσης

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


