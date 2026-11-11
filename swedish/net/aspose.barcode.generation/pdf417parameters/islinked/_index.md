---
title: "Pdf417Parameters.IsLinked"
second_title: "Aspose.BarCode för .NET API-referens"
description: "Pdf417Parameters property. Definierar länkade lägen med GS1MicroPdf417, MicroPdf417 och Pdf417 streckkoder. Med GS1MicroPdf417-symbologi kodas 906 907 912 913 914 915 Länkade UCC/EAN128-lägen. Med MicroPdf417 och Pdf417-symbologier kodas 918 länkningsflagga till associerad linjär komponent annan än en EAN.UCC"
type: docs
weight: 70
url: /sv/net/aspose.barcode.generation/pdf417parameters/islinked/
---
## Pdf417Parameters.IsLinked property

Definierar länkade lägen med GS1MicroPdf417, MicroPdf417 och Pdf417 streckkoder. Med GS1MicroPdf417-symbologi kodar 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128-lägen. Med MicroPdf417- och Pdf417-symbologier kodar 918 länkningsflagga till associerad linjär komponent annat än en EAN.UCC

```csharp
public bool IsLinked { get; set; }
```

## Exempel

Dessa exempel visar hur man kodar "Linked" UCC/EAN-128-lägen i GS1MicroPdf417 och länkningsflagga (918) i MicroPdf417 och Pdf417 streckkoder

```csharp
[C#]
//Kodar GS1 länkad läge 912 med datumfält AI 11 (Produktionsdatum) och AI 10 (Partinummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodar GS1 länkad läge 912 med datumfält AI 13 (Förpackningsdatum) och AI 21 (Serienummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodar GS1 länkad läge 912 med datumfält AI 15 (Säljdatum) och AI 10 (Partinummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodar GS1 länkad läge 912 med datumfält AI 17 (Utgångsdatum) och AI 21 (Serienummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodar GS1 länkad läge 914 med AI 10 (Partinummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodar GS1 länkad läge 915 med AI 21 (Serienummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodar GS1 länkade lägen 906, 907 med valfri AI
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodar MicroPdf417 NON EAN.UCC länkad läge 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodar Pdf417 NON EAN.UCC länkad läge 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
```

### Se även

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


