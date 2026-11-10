---
title: "Pdf417Parameters.MacroCharacters"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Ιδιότητα Pdf417Parameters. Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για πιο συμπαγή κωδικοποίηση σε ειδικές λειτουργίες. Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί τις λειτουργίες 916 και 917 MicroPdf417. Προεπιλεγμένη τιμή MacroCharacters.None."
type: docs
weight: 90
url: /el/net/aspose.barcode.generation/pdf417parameters/macrocharacters/
---
## Pdf417Parameters.MacroCharacters property

Οι τιμές Macro Characters 05 και 06 χρησιμοποιούνται για την απόκτηση πιο συμπαγούς κωδικοποίησης σε ειδικές λειτουργίες. Μπορούν να χρησιμοποιηθούν μόνο με το MicroPdf417 και κωδικοποιούν τις λειτουργίες 916 και 917 του MicroPdf417. Προεπιλεγμένη τιμή: MacroCharacters.None.

```csharp
public MacroCharacter MacroCharacters { get; set; }
```

## Παραδείγματα

Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε Macro Characters σε MicroPdf417.

```csharp
[C#]
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

* enum [MacroCharacter](../../macrocharacter/)
* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


