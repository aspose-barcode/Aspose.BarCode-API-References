---
title: "metod"
linktitle: "get_IsLinked"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Definierar länkade lägen med GS1MicroPdf417, MicroPdf417 och Pdf417‑streckkoder. Med GS1MicroPdf417‑symbologi kodas 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128‑lägen. Med MicroPdf417‑ och Pdf417‑symbologier kodas 918‑länkningsflagga till associerad linjär komponent annan än en EAN.UCC i C++."
type: docs
weight: 4100
url: /sv/cpp/aspose.barcode.generation/pdf417parameters/get_islinked/
---
## Pdf417Parameters::get_IsLinked method


Definierar länkade lägen med GS1MicroPdf417-, MicroPdf417- och Pdf417-streckkoder. Med GS1MicroPdf417-symbologi kodas 906, 907, 912, 913, 914, 915 “Länkade” UCC/EAN-128-lägen. Med MicroPdf417- och Pdf417-symbologier kodas 918-länkningsflagga till associerad linjär komponent annan än en EAN.UCC.

```cpp
bool Aspose::BarCode::Generation::Pdf417Parameters::get_IsLinked() const
```

## Anmärkningar


Dessa exempel visar hur man kodar "Linked" UCC/EAN-128‑lägen i GS1MicroPdf417 och länkningsflagga (918) i MicroPdf417‑ och Pdf417‑streckkoder.
```cpp
[C#]
//Kodar GS1 Linked mode 912 med datumfält AI 11 (Produktionsdatum) och AI 10 (Partinummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodar GS1 Linked mode 912 med datumfält AI 13 (Förpackningsdatum) och AI 21 (Serienummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodar GS1 Linked mode 912 med datumfält AI 15 (Säljdatum) och AI 10 (Partinummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodar GS1 Linked mode 912 med datumfält AI 17 (Utgångsdatum) och AI 21 (Serienummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodar GS1 Linked mode 914 med AI 10 (Partinummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodar GS1 Linked mode 915 med AI 21 (Serienummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodar GS1 Linked modes 906, 907 med valfri AI
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodar MicroPdf417 NON EAN.UCC Linked mode 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodar Pdf417 NON EAN.UCC Linked mode 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
```

## Se även

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
