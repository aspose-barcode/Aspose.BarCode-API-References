---
title: "metode"
linktitle: "set_IsLinked"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " method. Mendefinisikan mode terhubung dengan barcode GS1MicroPdf417, MicroPdf417, dan Pdf417. Dengan simbolologi GS1MicroPdf417 mengkodekan mode “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Dengan simbolologi MicroPdf417 dan Pdf417 mengkodekan flag tautan 918 ke komponen linear terkait selain EAN.UCC dalam C++."
type: docs
weight: 4200
url: /id/cpp/aspose.barcode.generation/pdf417parameters/set_islinked/
---
## Pdf417Parameters::set_IsLinked method


Mendefinisikan mode terhubung dengan kode batang GS1MicroPdf417, MicroPdf417, dan Pdf417. Dengan simbolologi GS1MicroPdf417 mengkodekan mode “Linked” UCC/EAN-128 906, 907, 912, 913, 914, 915. Dengan simbolologi MicroPdf417 dan Pdf417 mengkodekan flag tautan 918 ke komponen linear terkait selain EAN.UCC.

```cpp
void Aspose::BarCode::Generation::Pdf417Parameters::set_IsLinked(bool value)
```

## Catatan


Contoh-contoh ini menunjukkan cara mengkodekan mode "Linked" UCC/EAN-128 dalam GS1MicroPdf417 dan Flag Tautan (918) dalam barcode MicroPdf417 dan Pdf417.
```cpp
[C#]
//Mengkodekan mode GS1 Linked 912 dengan bidang tanggal AI 11 (Tanggal produksi) dan AI 10 (Nomor lot)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Mengkodekan mode GS1 Linked 912 dengan bidang tanggal AI 13 (Tanggal pengemasan) dan AI 21 (Nomor seri)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Mengkodekan mode GS1 Linked 912 dengan bidang tanggal AI 15 (Tanggal jual) dan AI 10 (Nomor lot)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Mengkodekan mode GS1 Linked 912 dengan bidang tanggal AI 17 (Tanggal kedaluwarsa) dan AI 21 (Nomor seri)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Mengkode mode Tertaut GS1 914 dengan AI 10 (Nomor lot)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Mengkode mode Tertaut GS1 915 dengan AI 21 (Nomor seri)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Mengkode mode Tertaut GS1 906, 907 dengan AI apa pun
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Mengkode mode Tertaut MicroPdf417 NON EAN.UCC 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Mengkode mode Tertaut Pdf417 NON EAN.UCC 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
```

## Lihat Juga

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
