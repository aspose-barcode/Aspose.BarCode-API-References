---
title: "Pdf417Parameters.IsCode128Emulation"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Pdf417Parameters प्रॉपर्टी। केवल MicroPdf417 के साथ उपयोग किया जा सकता है और Code 128 इम्यूलेशन मोड को एन्कोड करता है। दूसरे स्थान पर FNC1 को एन्कोड कर सकता है (मोड 908 और 909) तथा 910 और 911 को भी एन्कोड कर सकता है, जो दर्शाते हैं कि पहचाना गया MicroPdf417 Code 128 के रूप में व्याख्यायित किया जा सकता है।"
type: docs
weight: 60
url: /hi/net/aspose.barcode.generation/pdf417parameters/iscode128emulation/
---
## Pdf417Parameters.IsCode128Emulation property

केवल MicroPdf417 के साथ उपयोग किया जा सकता है और Code 128 एमुलेशन मोड को एन्कोड करता है। यह मोड 908 और 909 में दूसरे स्थान पर FNC1 को एन्कोड कर सकता है, साथ ही 910 और 911 को भी एन्कोड कर सकता है, जो केवल यह दर्शाते हैं कि पहचाना गया MicroPdf417 कोड 128 के रूप में व्याख्यायित किया जा सकता है।

```csharp
public bool IsCode128Emulation { get; set; }
```

## उदाहरण

ये नमूने दिखाते हैं कि Code 128 इम्यूलेशन मोड को दूसरे स्थान पर FNC1 के साथ और बिना कैसे एन्कोड किया जाए। इस प्रकार MicroPdf417 को Code 128 बारकोड के रूप में डिकोड किया जा सकता है।

```csharp
[C#]
//MicroPdf417 को कोड 128 अनुकरण मोड में एन्कोड करता है, जिसमें दूसरे स्थान पर FNC1 और एप्लिकेशन इंडिकेटर "a" होता है, मोड 908।
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//MicroPdf417 को कोड 128 अनुकरण मोड में एन्कोड करता है, जिसमें दूसरे स्थान पर FNC1 और एप्लिकेशन इंडिकेटर "99" होता है, मोड 909।
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//MicroPdf417 को कोड 128 अनुकरण मोड में एन्कोड करता है, मोड 910, 911
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

### और देखें

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


