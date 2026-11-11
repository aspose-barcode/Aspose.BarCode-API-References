---
title: "Pdf417Parameters.IsCode128Emulation"
second_title: "Aspose.BarCode for .NET API リファレンス"
description: "Pdf417Parameters プロパティ。MicroPdf417 と併用でき、Code 128 エミュレーションモードをエンコードします。第2位置に FNC1 をエンコードでき、モード 908 と 909、さらに 910 と 911 もエンコード可能です。これらは、認識された MicroPdf417 が Code 128 として解釈できることを示します"
type: docs
weight: 60
url: /ja/net/aspose.barcode.generation/pdf417parameters/iscode128emulation/
---
## Pdf417Parameters.IsCode128Emulation property

MicroPdf417 とだけ併用でき、Code 128 エミュレーションモードをエンコードします。FNC1 を第2位置でエンコードできるモード 908 と 909、また 910 と 911 もエンコードでき、これらは認識された MicroPdf417 が Code 128 として解釈できることを示すだけです。

```csharp
public bool IsCode128Emulation { get; set; }
```

## 例

このサンプルは、第2位置に FNC1 を含む場合と含まない場合の Code 128 エミュレーションモードのエンコード方法を示しています。この方法により、MicroPdf417 を Code 128 バーコードとしてデコードできます

```csharp
[C#]
//MicroPdf417 を Code 128 エミュレーションモードでエンコードし、第2位置に FNC1 とアプリケーションインジケータ "a" を設定、モード 908
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "a\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//MicroPdf417 を Code 128 エミュレーションモードでエンコードし、第2位置に FNC1 とアプリケーションインジケータ "99" を設定、モード 909
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "99\u001d1222322323");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());

//MicroPdf417 を Code 128 エミュレーションモードでエンコードします（モード 910、911）
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "123456789012345678");
generator.Parameters.Barcode.Pdf417.IsCode128Emulation = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsCode128Emulation:" + result.Extended.Pdf417.IsCode128Emulation.ToString());
```

### 関連項目

* class [Pdf417Parameters](../)
* namespace [Aspose.BarCode.Generation](../../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../../)


