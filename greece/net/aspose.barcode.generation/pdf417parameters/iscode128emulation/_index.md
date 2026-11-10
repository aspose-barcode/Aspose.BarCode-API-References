---
title: "Pdf417Parameters.IsCode128Emulation"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Ιδιότητα Pdf417Parameters. Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση σε λειτουργίες 908 και 909, καθώς επίσης και 910 και 911, που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128."
type: docs
weight: 60
url: /el/net/aspose.barcode.generation/pdf417parameters/iscode128emulation/
---
## Pdf417Parameters.IsCode128Emulation property

Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση σε λειτουργίες 908 και 909, καθώς επίσης μπορεί να κωδικοποιήσει 910 και 911, που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128.

```csharp
public bool IsCode128Emulation { get; set; }
```

## Παραδείγματα

Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε λειτουργίες προσομοίωσης Code 128 με FNC1 στη δεύτερη θέση και χωρίς αυτήν. Με αυτόν τον τρόπο το MicroPdf417 μπορεί να αποκωδικοποιηθεί ως barcode Code 128.

```csharp
[C#]
//Κωδικοποιεί το MicroPdf417 σε λειτουργία προσομοίωσης Code 128 με FNC1 στη δεύτερη θέση και Δείκτης Εφαρμογής "a", λειτουργία 908.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Κωδικοποιεί το MicroPdf417 σε λειτουργία προσομοίωσης Code 128 με FNC1 στη δεύτερη θέση και Δείκτης Εφαρμογής "99", λειτουργία 909.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Κωδικοποιεί το MicroPdf417 σε λειτουργία προσομοίωσης Code 128, λειτουργίες 910, 911
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

### Δείτε επίσης

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


