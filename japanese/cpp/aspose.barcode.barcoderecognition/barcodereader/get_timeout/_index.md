---
title: "メソッド"
linktitle: "get_Timeout"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。C++ で認識プロセスのタイムアウト（ミリ秒）を取得します。"
type: docs
weight: 300
url: /ja/cpp/aspose.barcode.barcoderecognition/barcodereader/get_timeout/
---
## BarCodeReader::get_Timeout method


認識プロセスのタイムアウト（ミリ秒）を取得します。

```cpp
int32_t Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_Timeout()
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
