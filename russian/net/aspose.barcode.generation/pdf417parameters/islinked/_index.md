---
title: "Pdf417Parameters.IsLinked"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Свойство Pdf417Parameters. Определяет связанные режимы с штрихкодами GS1MicroPdf417, MicroPdf417 и Pdf417. Символика GS1MicroPdf417 кодирует 906, 907, 912, 913, 914, 915 — связанные режимы UCC/EAN128. Символика MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC."
type: docs
weight: 70
url: /ru/net/aspose.barcode.generation/pdf417parameters/islinked/
---
## Pdf417Parameters.IsLinked property

Определяет связанные режимы с штрих‑кодами GS1MicroPdf417, MicroPdf417 и Pdf417. При символьной системе GS1MicroPdf417 кодирует 906, 907, 912, 913, 914, 915 «связанные» режимы UCC/EAN-128. При символьных системах MicroPdf417 и Pdf417 кодирует флаг связи 918 к связанному линейному компоненту, отличному от EAN.UCC.

```csharp
public bool IsLinked { get; set; }
```

## Примеры

Эти примеры показывают, как кодировать "Связанные" режимы UCC/EAN-128 в GS1MicroPdf417 и флаг связи (918) в штрихкодах MicroPdf417 и Pdf417.

```csharp
[C#]
//Кодирует связанный режим GS1 912 с полем даты AI 11 (дата производства) и AI 10 (номер партии).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Кодирует связанный режим GS1 912 с полем даты AI 13 (дата упаковки) и AI 21 (серийный номер).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Кодирует связанный режим GS1 912 с полем даты AI 15 (дата продажи) и AI 10 (номер партии).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Кодирует связанный режим GS1 912 с полем даты AI 17 (дата истечения срока) и AI 21 (серийный номер).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Кодирует связанный режим GS1 914 с AI 10 (номер партии).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Кодирует связанный режим GS1 915 с AI 21 (серийный номер).
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Кодирует связанные режимы GS1 906, 907 с любым AI.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Кодирует связанный режим 918 MicroPdf417, не относящийся к EAN.UCC.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Кодирует связанный режим 918 Pdf417, не относящийся к EAN.UCC.
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
```

### См. также

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


