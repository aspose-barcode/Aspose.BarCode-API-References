---
title: "メソッド"
linktitle: "get_FoundBarCodes"
second_title: "Aspose.BarCode for C++ API リファレンス"
description: " メソッド。C++ で認識された BarCodeResults 配列を取得します。"
type: docs
weight: 500
url: /ja/cpp/aspose.barcode.barcoderecognition/barcodereader/get_foundbarcodes/
---
## BarCodeReader::get_FoundBarCodes method


認識された [BarCodeResult](../../barcoderesult/) の配列を取得します

```cpp
System::ArrayPtr<System::SharedPtr<BarCodeResult>> Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_FoundBarCodes()
```

## 備考


認識された [BarCodeResult](../../barcoderesult/) の配列

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

* Class [BarCodeResult](../../barcoderesult/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
