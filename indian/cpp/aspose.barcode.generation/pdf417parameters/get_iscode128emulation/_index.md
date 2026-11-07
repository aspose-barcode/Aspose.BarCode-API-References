---
title: "विधि"
linktitle: "get_IsCode128Emulation"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " मेथड। केवल MicroPdf417 के साथ उपयोग किया जा सकता है और Code 128 इम्यूलेशन मोड एन्कोड करता है। FNC1 को दूसरे स्थान पर मोड 908 और 909 में एन्कोड कर सकता है, साथ ही 910 और 911 को भी एन्कोड कर सकता है जो दर्शाता है कि पहचाना गया MicroPdf417 Code 128 के रूप में व्याख्यायित किया जा सकता है C++ में।"
type: docs
weight: 4300
url: /hi/cpp/aspose.barcode.generation/pdf417parameters/get_iscode128emulation/
---
## Pdf417Parameters::get_IsCode128Emulation method


केवल MicroPdf417 के साथ उपयोग किया जा सकता है और Code 128 अनुकरण मोड एन्कोड करता है। यह दूसरे स्थान पर FNC1 को मोड 908 और 909 में एन्कोड कर सकता है, साथ ही 910 और 911 को भी एन्कोड करता है, जो दर्शाते हैं कि पहचाना गया MicroPdf417 Code 128 के रूप में व्याख्यायित किया जा सकता है।

```cpp
bool Aspose::BarCode::Generation::Pdf417Parameters::get_IsCode128Emulation() const
```

## टिप्पणियाँ


ये नमूने दिखाते हैं कि कैसे Code 128 इम्यूलेशन मोड को FNC1 के साथ दूसरे स्थान पर और बिना एन्कोड किया जाए। इस प्रकार MicroPdf417 को Code 128 बारकोड के रूप में डिकोड किया जा सकता है।
```cpp
[C#]
//MicroPdf417 को Code 128 इम्यूलेशन मोड में एन्कोड करता है, जिसमें दूसरे स्थान पर FNC1 और एप्लिकेशन इंडिकेटर "a" है, मोड 908।
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//MicroPdf417 को Code 128 इम्यूलेशन मोड में एन्कोड करता है, जिसमें दूसरे स्थान पर FNC1 और एप्लिकेशन इंडिकेटर "99" है, मोड 909।
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//MicroPdf417 को Code 128 इम्यूलेशन मोड में एन्कोड करता है, मोड 910, 911
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

## और देखें

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
