---
title: "μέθοδος"
linktitle: "get_IsCode128Emulation"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " method. Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση σε λειτουργίες 908 και 909, επίσης μπορεί να κωδικοποιήσει 910 και 911 που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128 σε C++."
type: docs
weight: 4300
url: /el/cpp/aspose.barcode.generation/pdf417parameters/get_iscode128emulation/
---
## Pdf417Parameters::get_IsCode128Emulation method


Μπορεί να χρησιμοποιηθεί μόνο με MicroPdf417 και κωδικοποιεί λειτουργίες προσομοίωσης Code 128. Μπορεί να κωδικοποιήσει FNC1 στη δεύτερη θέση σε λειτουργίες 908 και 909, καθώς επίσης και 910 και 911, που απλώς υποδεικνύουν ότι το αναγνωρισμένο MicroPdf417 μπορεί να ερμηνευθεί ως Code 128.

```cpp
bool Aspose::BarCode::Generation::Pdf417Parameters::get_IsCode128Emulation() const
```

## Σχόλια


Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε λειτουργίες προσομοίωσης Code 128 με FNC1 στη δεύτερη θέση και χωρίς αυτήν. Με αυτόν τον τρόπο το MicroPdf417 μπορεί να αποκωδικοποιηθεί ως γραμμωτός κώδικας Code 128.
```cpp
[C#]
//Κωδικοποιεί το MicroPdf417 σε λειτουργία προσομοίωσης Code 128 με FNC1 στη δεύτερη θέση και Δείκτη Εφαρμογής "a", λειτουργία 908.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//Κωδικοποιεί το MicroPdf417 σε λειτουργία προσομοίωσης Code 128 με FNC1 στη δεύτερη θέση και Δείκτη Εφαρμογής "99", λειτουργία 909.
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

## Δείτε επίσης

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
