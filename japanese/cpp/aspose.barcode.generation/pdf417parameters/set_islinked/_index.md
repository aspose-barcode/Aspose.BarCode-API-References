---
title: "メソッド"
linktitle: "set_IsLinked"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。GS1MicroPdf417 シンボロジーでは 906、907、912、913、914、915 の “Linked” UCC/EAN-128 モードをエンコードします。MicroPdf417 と Pdf417 シンボロジーでは 918 リンケージフラグを、EAN.UCC 以外の関連線形コンポーネントに対してエンコードします。C++ で。"
type: docs
weight: 4200
url: /ja/cpp/aspose.barcode.generation/pdf417parameters/set_islinked/
---
## Pdf417Parameters::set_IsLinked method


GS1MicroPdf417、MicroPdf417、Pdf417 バーコードとのリンクモードを定義します。GS1MicroPdf417 シンボルでは 906、907、912、913、914、915 の「リンク」UCC/EAN-128 モードをエンコードします。MicroPdf417 および Pdf417 シンボルでは、EAN.UCC 以外の関連線形コンポーネントへのリンクフラグ 918 をエンコードします。

```cpp
void Aspose::BarCode::Generation::Pdf417Parameters::set_IsLinked(bool value)
```

## 備考


これらのサンプルは、GS1MicroPdf417 で \"Linked\" UCC/EAN-128 モードをエンコードし、MicroPdf417 と Pdf417 バーコードでリンケージフラグ (918) をエンコードする方法を示しています。
```cpp
[C#]
//AI 11（製造日）と AI 10（ロット番号）を含む GS1 リンクモード 912 をエンコードします。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(11)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//AI 13（包装日）と AI 21（シリアル番号）を含む GS1 リンクモード 912 をエンコードします。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(13)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//AI 15（賞味期限）と AI 10（ロット番号）を含む GS1 リンクモード 912 をエンコードします。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(15)991231(10)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//AI 17（有効期限）と AI 21（シリアル番号）を含む GS1 リンクモード 912 をエンコードします。
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(17)991231(21)ABCD");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//AI 10（ロット番号）でGS1リンクモード914をエンコードします
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(10)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//AI 21（シリアル番号）でGS1リンクモード915をエンコードします
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(21)ABCD12345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//任意のAIでGS1リンクモード906、907をエンコードします
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1MicroPdf417, "(240)123456789012345");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.GS1MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//MicroPdf417 NON EAN.UCCリンクモード918をエンコードします
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MicroPdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.MicroPdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());

//Pdf417 NON EAN.UCCリンクモード918をエンコードします
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Pdf417, "ABCDE123456789012345678");
generator.Parameters.Barcode.Pdf417.IsLinked = true;
using (BarCodeReader reader = new BarCodeReader(generator.GenerateBarCodeImage(), DecodeType.Pdf417))
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText + " IsLinked:" + result.Extended.Pdf417.IsLinked.ToString());
```

## 関連項目

* Class [Pdf417Parameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
