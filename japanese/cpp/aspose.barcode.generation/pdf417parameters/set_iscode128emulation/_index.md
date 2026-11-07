---
title: "メソッド"
linktitle: "set_IsCode128Emulation"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。MicroPdf417 のみで使用でき、Code 128 エミュレーションモードをエンコードします。FNC1 を第2位置でエンコードできるモード 908 と 909、さらに 910 と 911 もエンコードでき、これらは認識された MicroPdf417 が Code 128 として解釈できることを示します。C++ で。"
type: docs
weight: 4400
url: /ja/cpp/aspose.barcode.generation/pdf417parameters/set_iscode128emulation/
---
## Pdf417Parameters::set_IsCode128Emulation method


MicroPdf417 のみで使用でき、Code 128 エミュレーションモードをエンコードします。第2位置モード 908 と 909 で FNC1 をエンコードでき、さらに 910 と 911 をエンコードできますが、これは認識された MicroPdf417 が Code 128 として解釈できることを示すだけです。

```cpp
void Aspose::BarCode::Generation::Pdf417Parameters::set_IsCode128Emulation(bool value)
```

## 備考


これらのサンプルは、FNC1 を第2位置に入れる場合と入れない場合の Code 128 エミュレーションモードのエンコード方法を示しています。この方法により MicroPdf417 を Code 128 バーコードとしてデコードできます。
```cpp
[C#]
//FNC1 を第2位置に、アプリケーションインジケータ \"a\" を使用し、モード 908 で MicroPdf417 を Code 128 エミュレーションモードでエンコードします。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//FNC1 を第2位置に、アプリケーションインジケータ \"99\" を使用し、モード 909 で MicroPdf417 を Code 128 エミュレーションモードでエンコードします。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//モード 910、911 で MicroPdf417 を Code 128 エミュレーションモードでエンコードします。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

## 関連項目

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
