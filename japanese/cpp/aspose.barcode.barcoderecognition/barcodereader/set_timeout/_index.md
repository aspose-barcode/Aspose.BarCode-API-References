---
title: "メソッド"
linktitle: "set_Timeout"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。C++ で認識プロセスのタイムアウトをミリ秒単位で設定します。"
type: docs
weight: 400
url: /ja/cpp/aspose.barcode.barcoderecognition/barcodereader/set_timeout/
---
## BarCodeReader::set_Timeout method


認識プロセスのタイムアウト（ミリ秒）を設定します。

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::set_Timeout(int32_t value)
```

## 備考


タイムアウトです。

このサンプルは、大きな画像でタイムアウトによる認識ハングを回避する方法を示しています
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png"))
{
    reader.Timeout = 5000;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png")
    reader.Timeout = 5000
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## 関連項目

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
