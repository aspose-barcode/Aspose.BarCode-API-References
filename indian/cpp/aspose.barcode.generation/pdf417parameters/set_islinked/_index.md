---
title: "विधि"
linktitle: "set_IsLinked"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " मेथड। GS1MicroPdf417, MicroPdf417 और Pdf417 बारकोड के साथ लिंक्ड मोड को परिभाषित करता है। GS1MicroPdf417 सिम्बोलॉजी 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 मोड एन्कोड करता है। MicroPdf417 और Pdf417 सिम्बोलॉजी 918 लिंकज फ़्लैग को संबंधित रैखिक घटक को एन्कोड करता है, जो EAN.UCC नहीं है, C++ में।"
type: docs
weight: 4200
url: /hi/cpp/aspose.barcode.generation/pdf417parameters/set_islinked/
---
## Pdf417Parameters::set_IsLinked method


GS1MicroPdf417, MicroPdf417 और Pdf417 बारकोड के साथ लिंक्ड मोड को परिभाषित करता है। GS1MicroPdf417 सिम्बोलॉजी में 906, 907, 912, 913, 914, 915 “Linked” UCC/EAN-128 मोड एन्कोड होते हैं। MicroPdf417 और Pdf417 सिम्बोलॉजी में 918 लिंकेज फ़्लैग एन्कोड होता है, जो EAN.UCC के अलावा जुड़े रैखिक घटक को दर्शाता है।

```cpp
void Aspose::BarCode::Generation::Pdf417Parameters::set_IsLinked(bool value)
```

## टिप्पणियाँ


ये नमूने दिखाते हैं कि कैसे "Linked" UCC/EAN-128 मोड को GS1MicroPdf417 में और लिंकज फ़्लैग (918) को MicroPdf417 और Pdf417 बारकोड में एन्कोड किया जाए।
```cpp
[C#]
//GS1 लिंक्ड मोड 912 को एआई 11 (उत्पादन तिथि) और एआई 10 (लॉट नंबर) के साथ एन्कोड करता है।
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 लिंक्ड मोड 912 को एआई 13 (पैकेजिंग तिथि) और एआई 21 (सीरियल नंबर) के साथ एन्कोड करता है।
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 लिंक्ड मोड 912 को एआई 15 (बेचने की तिथि) और एआई 10 (लॉट नंबर) के साथ एन्कोड करता है।
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//GS1 लिंक्ड मोड 912 को एआई 17 (समाप्ति तिथि) और एआई 21 (सीरियल नंबर) के साथ एन्कोड करता है।
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

//GS1 लिंक्ड मोड 906, 907 को किसी भी AI के साथ एन्कोड करता है
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

## और देखें

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
