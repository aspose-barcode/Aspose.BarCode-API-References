---
title: "μέθοδος"
linktitle: "get_IsLinked"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " method. Ορίζει συνδεδεμένες λειτουργίες με τα barcode GS1MicroPdf417, MicroPdf417 και Pdf417. Με τη συμβολική γραφή GS1MicroPdf417 κωδικοποιεί τις λειτουργίες 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128. Με τις συμβολικές γραφές MicroPdf417 και Pdf417 κωδικοποιεί τη σημαία σύνδεσης 918 σε συσχετισμένο γραμμικό στοιχείο εκτός του EAN.UCC σε C++."
type: docs
weight: 4100
url: /el/cpp/aspose.barcode.generation/pdf417parameters/get_islinked/
---
## Pdf417Parameters::get_IsLinked method


Ορίζει συνδεδεμένες λειτουργίες με τα barcodes GS1MicroPdf417, MicroPdf417 και Pdf417. Με τη συμβολική GS1MicroPdf417 κωδικοποιεί τις λειτουργίες 906, 907, 912, 913, 914, 915 «Linked» UCC/EAN-128. Με τις συμβολές MicroPdf417 και Pdf417 κωδικοποιεί τη σημαία σύνδεσης 918 σε συσχετισμένο γραμμικό στοιχείο εκτός του EAN.UCC.

```cpp
bool Aspose::BarCode::Generation::Pdf417Parameters::get_IsLinked() const
```

## Σχόλια


Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε τις λειτουργίες "Linked" UCC/EAN-128 στο GS1MicroPdf417 και τη σημαία σύνδεσης (918) στα barcode MicroPdf417 και Pdf417.
```cpp
[C#]
//Κωδικοποιεί τη συνδεδεμένη λειτουργία GS1 912 με πεδίο ημερομηνίας AI 11 (Ημερομηνία παραγωγής) και AI 10 (Αριθμός παρτίδας).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Κωδικοποιεί τη συνδεδεμένη λειτουργία GS1 912 με πεδίο ημερομηνίας AI 13 (Ημερομηνία συσκευασίας) και AI 21 (Αριθμός σειράς).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Κωδικοποιεί τη συνδεδεμένη λειτουργία GS1 912 με πεδίο ημερομηνίας AI 15 (Ημερομηνία λήξης πώλησης) και AI 10 (Αριθμός παρτίδας).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Κωδικοποιεί τη συνδεδεμένη λειτουργία GS1 912 με πεδίο ημερομηνίας AI 17 (Ημερομηνία λήξης) και AI 21 (Αριθμός σειράς).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Κωδικοποιεί GS1 Linked mode 914 με AI 10 (αριθμός παρτίδας)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Κωδικοποιεί GS1 Linked mode 915 με AI 21 (αριθμός σειράς)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Κωδικοποιεί τις λειτουργίες GS1 Linked modes 906, 907 με οποιοδήποτε AI
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Κωδικοποιεί MicroPdf417 NON EAN.UCC Linked mode 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Κωδικοποιεί Pdf417 NON EAN.UCC Linked mode 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
```

## Δείτε επίσης

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
