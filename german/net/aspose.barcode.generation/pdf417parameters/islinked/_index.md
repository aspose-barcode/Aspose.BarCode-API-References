---
title: "Pdf417Parameters.IsLinked"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "Pdf417Parameters property. Definiert verknüpfte Modi mit GS1MicroPdf417, MicroPdf417 und Pdf417‑Barcodes. Mit dem GS1MicroPdf417‑Symbol werden 906 907 912 913 914 915 kodiert (verknüpfte UCC/EAN128‑Modi). Mit den MicroPdf417‑ und Pdf417‑Symbolen wird 918 (Linkage‑Flag) kodiert, um eine zugehörige lineare Komponente zu verknüpfen, die nicht ein EAN.UCC ist."
type: docs
weight: 70
url: /de/net/aspose.barcode.generation/pdf417parameters/islinked/
---
## Pdf417Parameters.IsLinked property

Definiert verknüpfte Modi mit GS1MicroPdf417-, MicroPdf417- und Pdf417‑Barcodes. Mit der GS1MicroPdf417‑Symbolik werden die „Linked“ UCC/EAN‑128‑Modi 906, 907, 912, 913, 914, 915 kodiert. Mit den Symboliken MicroPdf417 und Pdf417 wird das Verknüpfungsflag 918 zum zugehörigen linearen Bauteil außer einem EAN.UCC kodiert.

```csharp
public bool IsLinked { get; set; }
```

## Beispiele

Diese Beispiele zeigen, wie "Linked"‑UCC/EAN‑128‑Modi in GS1MicroPdf417 und das Linkage‑Flag (918) in MicroPdf417‑ und Pdf417‑Barcodes kodiert werden.

```csharp
[C#]
//Kodiert GS1 Linked mode 912 mit dem Datumsfeld AI 11 (Produktionsdatum) und AI 10 (Losnummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodiert GS1 Linked mode 912 mit dem Datumsfeld AI 13 (Verpackungsdatum) und AI 21 (Seriennummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodiert GS1 Linked mode 912 mit dem Datumsfeld AI 15 (Verkaufsdatum) und AI 10 (Losnummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodiert GS1 Linked mode 912 mit dem Datumsfeld AI 17 (Verfallsdatum) und AI 21 (Seriennummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodiert GS1 Linked mode 914 mit AI 10 (Losnummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodiert GS1 Linked mode 915 mit AI 21 (Seriennummer)
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodiert GS1 Linked modes 906, 907 mit beliebigem AI
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodiert MicroPdf417 NON EAN.UCC Linked mode 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Kodiert Pdf417 NON EAN.UCC Linked mode 918
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
```

### Siehe auch

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


