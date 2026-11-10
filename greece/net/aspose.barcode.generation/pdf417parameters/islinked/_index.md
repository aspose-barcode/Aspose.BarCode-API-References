---
title: "Pdf417Parameters.IsLinked"
second_title: "Αναφορά API του Aspose.BarCode για .NET"
description: "Ιδιότητα Pdf417Parameters. Ορίζει συνδεδεμένες λειτουργίες με τα barcode GS1MicroPdf417, MicroPdf417 και Pdf417. Με τη συμβολική GS1MicroPdf417 κωδικοποιούνται οι λειτουργίες 906 907 912 913 914 915 UCC/EAN128 συνδεδεμένες. Με τις συμβολές MicroPdf417 και Pdf417 κωδικοποιείται η σημαία σύνδεσης 918 σε σχετικό γραμμικό στοιχείο εκτός του EAN.UCC."
type: docs
weight: 70
url: /el/net/aspose.barcode.generation/pdf417parameters/islinked/
---
## Pdf417Parameters.IsLinked property

Ορίζει συνδεδεμένες λειτουργίες με barcode GS1MicroPdf417, MicroPdf417 και Pdf417. Με τη συμβολή GS1MicroPdf417 κωδικοποιεί τις λειτουργίες “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Με τις συμβολές MicroPdf417 και Pdf417 κωδικοποιεί τη σημαία σύνδεσης 918 σε σχετικό γραμμικό στοιχείο εκτός του EAN.UCC.

```csharp
public bool IsLinked { get; set; }
```

## Παραδείγματα

Αυτά τα παραδείγματα δείχνουν πώς να κωδικοποιήσετε τις λειτουργίες "Linked" UCC/EAN-128 σε GS1MicroPdf417 και τη σημαία σύνδεσης (918) σε barcode MicroPdf417 και Pdf417.

```csharp
[C#]
//Κωδικοποιεί τη λειτουργία GS1 Linked 912 με πεδίο ημερομηνίας AI 11 (Ημερομηνία παραγωγής) και AI 10 (Αριθμός παρτίδας)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Κωδικοποιεί τη λειτουργία GS1 Linked 912 με πεδίο ημερομηνίας AI 13 (Ημερομηνία συσκευασίας) και AI 21 (Σειριακός αριθμός)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Κωδικοποιεί τη λειτουργία GS1 Linked 912 με πεδίο ημερομηνίας AI 15 (Ημερομηνία λήξης πώλησης) και AI 10 (Αριθμός παρτίδας)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Κωδικοποιεί τη συνδεδεμένη λειτουργία GS1 912 με το πεδίο ημερομηνίας AI 17 (Ημερομηνία λήξης) και AI 21 (Σειριακός αριθμός)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Κωδικοποιεί τη συνδεδεμένη λειτουργία GS1 914 με AI 10 (Αριθμός παρτίδας)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Κωδικοποιεί τη συνδεδεμένη λειτουργία GS1 915 με AI 21 (Σειριακός αριθμός)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Κωδικοποιεί τις συνδεδεμένες λειτουργίες GS1 906, 907 με οποιοδήποτε AI
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Κωδικοποιεί τη συνδεδεμένη λειτουργία MicroPdf417 NON EAN.UCC 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Κωδικοποιεί τη συνδεδεμένη λειτουργία Pdf417 NON EAN.UCC 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
```

### Δείτε επίσης

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


