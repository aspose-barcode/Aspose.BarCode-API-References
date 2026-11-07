---
title: "methode"
linktitle: "get_IsLinked"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Definieert gekoppelde modi met GS1MicroPdf417, MicroPdf417 en Pdf417‑barcodes. Met GS1MicroPdf417‑symbooltype codeert 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128‑modi. Met MicroPdf417‑ en Pdf417‑symbooltypes codeert 918 koppelings‑vlag naar een geassocieerd lineair component anders dan een EAN.UCC in C++."
type: docs
weight: 4100
url: /nl/cpp/aspose.barcode.generation/pdf417parameters/get_islinked/
---
## Pdf417Parameters::get_IsLinked method


Definieert gekoppelde modi met GS1MicroPdf417-, MicroPdf417- en Pdf417‑barcodes. Met GS1MicroPdf417‑symboolcode worden 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN‑128‑modi gecodeerd. Met MicroPdf417‑ en Pdf417‑symboolcodes wordt 918‑koppelingsvlag naar een geassocieerd lineair component anders dan een EAN.UCC gecodeerd.

```cpp
bool Aspose::BarCode::Generation::Pdf417Parameters::get_IsLinked() const
```

## Opmerkingen


Deze voorbeelden tonen hoe "Linked" UCC/EAN-128‑modi te coderen in GS1MicroPdf417 en de koppelings‑vlag (918) in MicroPdf417‑ en Pdf417‑barcodes.
```cpp
[C#]
//Codeert GS1‑Linked‑modus 912 met datumveld AI 11 (productiedatum) en AI 10 (partijnummer).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Codeert GS1‑Linked‑modus 912 met datumveld AI 13 (verpakkingsdatum) en AI 21 (serienummer).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Codeert GS1‑Linked‑modus 912 met datumveld AI 15 (verkoopdatum) en AI 10 (partijnummer).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Codeert GS1‑Linked‑modus 912 met datumveld AI 17 (vervaldatum) en AI 21 (serienummer).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Encodeert GS1 Linked-modus 914 met AI 10 (partijnummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Encodeert GS1 Linked-modus 915 met AI 21 (serienummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Encodeert GS1 Linked-modus 906, 907 met elke AI
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Encodeert MicroPdf417 NON EAN.UCC Linked-modus 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Encodeert Pdf417 NON EAN.UCC Linked-modus 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
```

## Zie ook

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
