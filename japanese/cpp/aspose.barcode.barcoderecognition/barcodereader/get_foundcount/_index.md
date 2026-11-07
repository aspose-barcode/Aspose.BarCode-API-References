---
title: "メソッド"
linktitle: "get_FoundCount"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。C++ で認識されたバーコードの数を取得します。"
type: docs
weight: 600
url: /ja/cpp/aspose.barcode.barcoderecognition/barcodereader/get_foundcount/
---
## BarCodeReader::get_FoundCount method


認識されたバーコードの数を取得します

```cpp
int32_t Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_FoundCount()
```

## 備考


認識されたバーコードの数

このサンプルは、[BarCodeReader](../) を使用してバーコードを読み取る方法を示しています
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    reader.ReadBarCodes();
    for(int i = 0; reader.FoundCount > i; ++i)
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes[i].CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    reader.ReadBarCodes()
    For i As Integer = 0 To reader.FoundCount - 1 Step 1
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes(i).CodeText)
    Next
End Using
```

## 関連項目

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
