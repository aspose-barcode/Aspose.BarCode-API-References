---
title: "メソッド"
linktitle: "get_DetectEncoding"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " method. エンジンが Unicode コードセットのコードテキストエンコーディングを検出するよう強制するフラグです。デフォルト値は C++ では true です。"
type: docs
weight: 700
url: /ja/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_detectencoding/
---
## BarcodeSettings::get_DetectEncoding method


Unicode コードセットのコードテキストエンコーディングを検出するようエンジンに強制するフラグです。デフォルト値は true です。

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_DetectEncoding() const
```

## 備考


このサンプルは、DetectEncoding が有効な場合にテキストエンコーディングをリアルタイムで検出する方法を示しています。
```cpp
[C#]
using (MemoryStream ms = new MemoryStream())
{
    using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
    {
        generator.SetCodeText("Слово", Encoding.UTF8);
        generator.Save(ms, BarCodeImageFormat.Png);
    }
    //Unicode コードセットのエンコーディング検出が有効です
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    //エンコーディング検出は無効です
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = false;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using ms As New MemoryStream
    Using generator As New BarcodeGenerator(EncodeTypes.QR, "Слово")
        generator.SetCodeText("Слово", System.Text.Encoding.UTF8)
        generator.Save(ms, BarCodeImageFormat.Png)
    End Using
    'detects encoding for Unicode codesets is enabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = True
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
    'detect encoding is disabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = False
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```


エンジンが Unicode コードセットのコードテキストエンコーディングを検出するよう強制するフラグ
## 関連項目

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
