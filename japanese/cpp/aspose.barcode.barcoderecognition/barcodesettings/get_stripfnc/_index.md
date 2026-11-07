---
title: "メソッド"
linktitle: "get_StripFNC"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " method. コードテキストから FNC1、FNC2、FNC3 文字を除去します。デフォルト値は false です（C++）。"
type: docs
weight: 300
url: /ja/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_stripfnc/
---
## BarcodeSettings::get_StripFNC method


コードテキストから FNC1、FNC2、FNC3 文字を除去します。デフォルト値は false です。

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_StripFNC() const
```

## 備考


このサンプルは FNC 文字の除去方法を示しています
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1Code128, "(02)04006664241007(37)1(400)7019590754"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC 無効
    reader.BarcodeSettings.StripFNC = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC 有効
    reader.BarcodeSettings.StripFNC = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.GS1Code128, "(02)04006664241007(37)1(400)7019590754")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    'StripFNC disabled
    reader.BarcodeSettings.StripFNC = False
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    'StripFNC enabled
    reader.BarcodeSettings.StripFNC = True
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```


コードテキストから FNC1、FNC2、FNC3 文字を除去します。デフォルト値は false です。
## 関連項目

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
