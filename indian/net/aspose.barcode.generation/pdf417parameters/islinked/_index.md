---
title: "Pdf417Parameters.IsLinked"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Pdf417Parameters प्रॉपर्टी। GS1MicroPdf417, MicroPdf417 और Pdf417 बारकोड्स के साथ लिंक्ड मोड्स को परिभाषित करता है। GS1MicroPdf417 सिम्बोलॉजी 906, 907, 912, 913, 914, 915 को एन्कोड करता है, जो लिंक्ड UCC/EAN128 मोड्स हैं। MicroPdf417 और Pdf417 सिम्बोलॉजीज़ 918 लिंकज फ़्लैग को एन्कोड करते हैं, जो EAN.UCC के अलावा किसी अन्य रैखिक घटक से जुड़ा होता है।"
type: docs
weight: 70
url: /hi/net/aspose.barcode.generation/pdf417parameters/islinked/
---
## Pdf417Parameters.IsLinked property

GS1MicroPdf417, MicroPdf417 और Pdf417 बारकोड के साथ लिंक्ड मोड को परिभाषित करता है। GS1MicroPdf417 सिम्बोलॉजी 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 मोड को एन्कोड करता है। MicroPdf417 और Pdf417 सिम्बोलॉजी 918 लिंकज फ़्लैग को संबंधित रैखिक घटक (EAN.UCC के अलावा) को एन्कोड करती हैं।

```csharp
public bool IsLinked { get; set; }
```

## उदाहरण

ये नमूने दिखाते हैं कि कैसे "Linked" UCC/EAN-128 मोड्स को GS1MicroPdf417 में और लिंकज फ़्लैग (918) को MicroPdf417 और Pdf417 बारकोड्स में एन्कोड किया जाता है।

```csharp
[C#]
//GS1 लिंक्ड मोड 912 को डेट फ़ील्ड AI 11 (उत्पादन तिथि) और AI 10 (लॉट नंबर) के साथ एन्कोड करता है।
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 लिंक्ड मोड 912 को डेट फ़ील्ड AI 13 (पैकेजिंग तिथि) और AI 21 (सीरियल नंबर) के साथ एन्कोड करता है।
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 लिंक्ड मोड 912 को डेट फ़ील्ड AI 15 (बेचने की तिथि) और AI 10 (लॉट नंबर) के साथ एन्कोड करता है।
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 लिंक्ड मोड 912 को तिथि फ़ील्ड AI 17 (समाप्ति तिथि) और AI 21 (सीरियल नंबर) के साथ एन्कोड करता है
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 लिंक्ड मोड 914 को AI 10 (लॉट नंबर) के साथ एन्कोड करता है
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 लिंक्ड मोड 915 को AI 21 (सीरियल नंबर) के साथ एन्कोड करता है
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 लिंक्ड मोड्स 906, 907 को किसी भी AI के साथ एन्कोड करता है
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//MicroPdf417 NON EAN.UCC लिंक्ड मोड 918 को एन्कोड करता है
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Pdf417 NON EAN.UCC लिंक्ड मोड 918 को एन्कोड करता है
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
```

### और देखें

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


