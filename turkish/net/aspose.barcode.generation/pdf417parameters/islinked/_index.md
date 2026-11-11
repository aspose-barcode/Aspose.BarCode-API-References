---
title: "Pdf417Parameters.IsLinked"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Pdf417Parameters özelliği. GS1MicroPdf417, MicroPdf417 ve Pdf417 barkodlarıyla bağlantılı modları tanımlar. GS1MicroPdf417 sembolü 906 907 912 913 914 915 kodlarını, Bağlantılı UCC/EAN128 modlarını kodlar. MicroPdf417 ve Pdf417 sembolleri 918 bağlantı bayrağını, EAN.UCC dışındaki ilişkili doğrusal bileşene kodlar."
type: docs
weight: 70
url: /tr/net/aspose.barcode.generation/pdf417parameters/islinked/
---
## Pdf417Parameters.IsLinked property

GS1MicroPdf417, MicroPdf417 ve Pdf417 barkodlarıyla bağlantılı modları tanımlar. GS1MicroPdf417 sembolü 906, 907, 912, 913, 914, 915 “Bağlantılı” UCC/EAN-128 modlarını kodlar. MicroPdf417 ve Pdf417 sembolleri 918 bağlantı bayrağını EAN.UCC dışındaki ilişkili doğrusal bileşene kodlar.

```csharp
public bool IsLinked { get; set; }
```

## Örnekler

Bu örnekler, GS1MicroPdf417 içinde "Linked" UCC/EAN-128 modlarını ve MicroPdf417 ile Pdf417 barkodlarında Bağlantı Bayrağı (918)'i nasıl kodlayacağını gösterir.

```csharp
[C#]
//GS1 Bağlantılı mod 912'yi, tarih alanı AI 11 (Üretim tarihi) ve AI 10 (Lot numarası) ile kodlar
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 Bağlantılı mod 912'yi, tarih alanı AI 13 (Paketleme tarihi) ve AI 21 (Seri numarası) ile kodlar
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 Bağlantılı mod 912'yi, tarih alanı AI 15 (Satışa sunma tarihi) ve AI 10 (Lot numarası) ile kodlar
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 Bağlantılı mod 912'yi tarih alanı AI 17 (Son kullanma tarihi) ve AI 21 (Seri numarası) ile kodlar
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 Bağlantılı mod 914'ü AI 10 (Lot numarası) ile kodlar
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 Bağlantılı mod 915'i AI 21 (Seri numarası) ile kodlar
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 Bağlantılı modlar 906, 907'i herhangi bir AI ile kodlar
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//MicroPdf417 NON EAN.UCC Bağlantılı mod 918'i kodlar
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Pdf417 NON EAN.UCC Bağlantılı mod 918'i kodlar
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
```

### Ayrıca Bakınız

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


